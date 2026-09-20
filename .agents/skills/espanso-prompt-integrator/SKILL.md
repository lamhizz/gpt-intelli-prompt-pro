---
name: espanso-prompt-integrator
description: >-
  Standardized workflow for analyzing, formatting, testing, and integrating new text expansions and prompt snippets into Espanso configurations (specifically gpt-intelli-prompt-pro). Use whenever the user asks to add, integrate, create, or modify an Espanso prompt snippet, text expansion, or match YAML file.
---

# Espanso Prompt Integrator

A standardized, reliable workflow for turning raw prompt templates and system instructions into production-ready Espanso text expansions, maintaining metadata consistency, repository documentation, and live daemon synchronization.

---

## 1. When to Use This Skill

Activate this skill when:
- The user provides prompt text, system prompts, or macros to turn into an Espanso text expansion.
- Adding new snippets to `gpt-intelli-prompt-pro.yml` or creating new Espanso match configurations.
- Documenting new triggers in `README.md` and keeping documentation in sync with the codebase.
- Syncing repository match files with the local active Espanso runtime (`~/Library/Application Support/espanso/match/`).

---

## 2. Step-by-Step Integration Workflow

### Step 1: Analyze & Clarify Prompt Requirements

1. **Extract Metadata**:
   - **Title/Name**: Short, distinct name defining what the prompt accomplishes.
   - **Tags**: 3–5 comma-separated categorization keywords (e.g., `Architecture, Full-Stack, Prioritization`).
   - **Use Cases**: 2–4 concrete scenarios answering "when to use this" (e.g., `Codebase health assessment, sprint improvement planning`).
   - **Description**: A 1–2 sentence summary of the persona, task, lenses, and output schema.
2. **Determine the Trigger**:
   - If the user did not specify a trigger keyword, propose a concise, memorable trigger adhering to the `:g<action>` naming convention (e.g., `:gimprove`, `:gaudit`, `:garchitect`).
   - Use `ask_question` to let the user select their preferred trigger if multiple good candidates exist.
   - Verify the trigger does not collide with existing triggers in the target YAML.

### Step 2: Allocate Unique ID & Choose Category

1. **Check Highest ID**:
   - Search the YAML file for existing IDs:
     ```bash
     grep -o 'ID[0-9]\+' gpt-intelli-prompt-pro.yml | sed 's/ID//' | sort -n | tail -n 5
     ```
   - Assign the next sequential ID with zero-padding (e.g., `ID132` -> `ID133`).
2. **Assign Category Group**:
   - Map the prompt to one of the 8 established groups in `gpt-intelli-prompt-pro.yml`:
     1. `Refinement & Iteration Prompts` (reworking, looping, polishing, upgrading answers)
     2. `Critical Thinking & Problem Framing` (blind spots, first principles, socratic method, red teaming)
     3. `Summarization & Clarity Prompts` (TL;DR, simplification, density, multi-level explanations)
     4. `Planning & Organization Prompts` (roadmaps, breakdowns, action plans, checklists)
     5. `Evaluation & Comparison Prompts` (benchmarks, scoring rubrics, ICE/RICE, trade-off analysis)
     6. `Simulation & Role-Playing Prompts` (expert personas, roleplay, debate, system behavior)
     7. `GPT Management & Interaction` (context injection, custom instructions, memory updates, resets)
     8. `Specialized Frameworks & Models` (Double Diamond, JTBD, LIFT, comprehensive audit frameworks)

### Step 3: Format the YAML Snippet

Follow the exact indentation and comment structure:

```yaml
  # ---
  # Name: IDXXX - Prompt Title
  # Tags: Tag1, Tag2, Tag3
  # Use cases: Use case 1, Use case 2
  # Description: Concise description of what the prompt instructs the model to do.
  - trigger: ":gtrigger"
    replace: |
      Role: ...

      Task: ...
```

#### Critical Formatting Rules:
- **Indent with 6 Spaces**: Every content line under `replace: |` must be indented by **exactly 6 spaces** (`      `).
- **Web Parser Compatibility**: The web dashboard (`index.html`) parses the YAML dynamically using `lines[j].substring(6)`. Incorrect indentation will break the UI card rendering.
- **Clean Whitespace**: Ensure empty lines inside the multiline block contain only `\n` (no trailing garbage spaces) and ensure the file ends with a trailing newline.

### Step 4: Update Documentation (`README.md`)

Locate the corresponding section in `README.md` (e.g., `### 4.8. Specialized Frameworks & Models`) and add the snippet to the table:

```markdown
| `:gtrigger` | IDXXX | Prompt Title | Tag1, Tag2, Tag3 | Use case 1, Use case 2 |
```

### Step 5: Sync with Active Espanso Installation

1. **Locate Active Espanso Match Directory**:
   - **macOS**: `~/Library/Application Support/espanso/match/`
   - **Linux**: `~/.config/espanso/match/`
   - **Windows**: `%APPDATA%\espanso\match\`
2. **Copy the Updated Configuration**:
   ```bash
   cp gpt-intelli-prompt-pro.yml "$HOME/Library/Application Support/espanso/match/gpt-intelli-prompt-pro.yml"
   ```
3. **Verify Daemon & Match Registration**:
   - Check if Espanso is active:
     ```bash
     espanso status
     ```
   - Verify the new trigger is compiled and recognized:
     ```bash
     espanso match list | grep "gtrigger"
     ```
   - Inspect daemon logs if any errors are reported:
     ```bash
     espanso log | tail -n 25
     ```

---

## 3. Verification Checklist

Before finishing:
- [ ] Unique `IDXXX` confirmed (no duplicate IDs).
- [ ] Unique trigger shortcut `:g...` checked against all existing triggers.
- [ ] 6-space indentation strictly maintained on all multiline prompt lines.
- [ ] `README.md` table updated with trigger, ID, title, tags, and use cases.
- [ ] Local Espanso match directory updated and verified via `espanso match list`.
- [ ] Git status verified clean or showing only intentional modifications.
