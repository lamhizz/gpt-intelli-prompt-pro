<<<<<<< Updated upstream
# gpt-intelli-prompt-pro

**Master your AI conversations with a professional library of high-leverage GPT prompt snippets.**

---

## 2. Table of Contents

1.  [1. gpt-intelli-prompt-pro: High-Leverage GPT Prompt Snippets](#1-gpt-intelli-prompt-pro-high-leverage-gpt-prompt-snippets)
2.  [2. Quick Start: Core Starter Pack](#2-quick-start-core-starter-pack)
3.  [3. Features & Organization](#3-features--organization)
    * [3.1. Groups List](#31-groups-list)
4.  [4. Cheat Sheet](#4-cheat-sheet)
    * [4.1. Refinement & Iteration Prompts](#41-refinement--iteration-prompts)
    * [4.2. Critical Thinking & Problem Framing](#42-critical-thinking--problem-framing)
    * [4.3. Summarization & Clarity Prompts](#43-summarization--clarity-prompts)
    * [4.4. Planning & Organization Prompts](#44-planning--organization-prompts)
    * [4.5. Evaluation & Comparison Prompts](#45-evaluation--comparison-prompts)
    * [4.6. Simulation & Role-Playing Prompts](#46-simulation--role-playing-prompts)
    * [4.7. GPT Management & Interaction](#47-gpt-management--interaction)
    * [4.8. Specialized Frameworks & Models](#48-specialized-frameworks--models)
5.  [5. Installation](#5-installation)
6.  [6. Contributing & Extending](#6-contributing--extending)
7.  [7. Usage Examples](#7-usage-examples)
8.  [8. License & Contact](#8-license--contact)

---

## 2. Quick Start: Core Starter Pack

Jump right into enhancing your GPT interactions with these essential triggers. Just type them into any text field where Espanso is active, followed by a space or enter.

* **`:grefine`**
    * **Description:** Updates GPT's previous response with added context for better accuracy and relevance.
    * **When to Use:** When you need GPT to rework its last output based on new information or conversation history.

* **`:gthink`**
    * **Description:** Instructs GPT to approach a problem step-by-step, prioritizing clarity and explaining its reasoning.
    * **When to Use:** When facing complex problems and needing a structured, transparent thought process from GPT.

* **`:gsummary`**
    * **Description:** Gets a concise summary of key points, stripped of fluff but retaining depth.
    * **When to Use:** When you need to quickly grasp the essence of a long conversation or document from GPT.

* **`:gsimrole`**
    * **Description:** Commands GPT to roleplay as a specific persona (e.g., CEO, mentor) and respond from that perspective.
    * **When to Use:** For gaining insights from specific viewpoints or preparing for interactions with different stakeholders.

* **`:gupdate`**
    * **Description:** Updates GPT's internal memory with new information for future recall in current and subsequent chats.
    * **When to Use:** To establish persistent context, preferences, or project details for GPT to remember.

* **`:gddiamond`**
    * **Description:** Guides GPT through the structured problem-solving process of the Double Diamond framework (Discover, Define, Develop, Deliver).
    * **When to Use:** For tackling product, UX, or strategic challenges with a structured design thinking approach.

* **`:gcritique`**
    * **Description:** Instructs GPT to critique its own output, identifying strengths, weaknesses, and areas for improvement.
    * **When to Use:** For self-correction, expert review of GPT's responses, or sharpening ideation.

* **`:gask`**
    * **Description:** Prompts GPT to ask clarifying questions to better understand your goals, context, or constraints.
    * **When to Use:** Before expecting a final response, to ensure GPT has all necessary information for a tailored answer.

---

## 3. Features & Organization

The `gpt-intelli-prompt-pro` toolkit transforms your GPT interactions into a high-leverage workflow by codifying best-practice prompts into simple, memorable triggers. Snippets are organized by their primary intent into distinct logical units, designed to be easily discoverable and reusable.
All these snippets are housed within a single YAML file: `match/gpt-intelli-prompt-pro.yml`. This consolidated structure makes it easy to manage and integrate into your Espanso setup.

### 3.1. Groups List

The toolkit is structured into the following major logical units, each serving a distinct purpose in guiding GPT's behavior:

1.  **Refinement & Iteration Prompts**: For improving, enhancing, and iterating on previous GPT responses.
2.  **Critical Thinking & Problem Framing**: For deeper thinking, identifying issues, exploring alternative perspectives, and structuring complex problems.
3.  **Summarization & Clarity Prompts**: For distilling information into clear, concise, and understandable formats.
4.  **Planning & Organization Prompts**: For structuring ideas, breaking down tasks, prioritizing efforts, and planning workflows.
5.  **Evaluation & Comparison Prompts**: For detailed assessment of ideas, options, and responses through structured comparisons and critical analysis.
6.  **Simulation & Role-Playing Prompts**: For guiding GPT to simulate real-world scenarios, role-play personas, and explore outcomes.
7.  **GPT Management & Interaction**: For managing GPT's state, context, memory, and generating instructions.
8.  **Specialized Frameworks & Models**: For applying specific analytical or design frameworks to guide GPT's structured problem-solving.

---

## 4. Cheat Sheet

Here's a comprehensive overview of all `gpt-intelli-prompt-pro` triggers and their details, organized by their logical units:

---

### 4.1. Refinement & Iteration Prompts
These snippets are designed to refine, enhance, and iterate on previous GPT responses, ensuring accuracy, clarity, and relevance. They focus on improving the quality and focus of ongoing conversations.

| Trigger | ID | Name | Tags | Use Cases |
| :--------- | :--- | :------------------------- | :---------------------------------- | :--------------------------------------------------------------------- |
| `:grefine` | ID001 | Refine Previous Response | Refinement, Feedback, Iteration | Improving output, making responses better, clarifying previous answers |
| `:genhance` | ID002 | Enhance Output for Fit | Refinement, Adaptation, Clarity | Tailoring output, aligning with goals, improving fit |
| `:gloop` | ID055 | Improvement Loop | Iteration, Improvement, Quality Control | Refining output, continuous improvement, self-correction |
| `:greview` | ID097 | Review Own Output | Review, Self-Correction, Quality Control | Improving response quality, critical self-assessment, ensuring coherence |
| `:gpolish` | ID098 | Polish to Final-Ready Copy | Polish, Finalization, Professionalism | Preparing content for publication, formal communication, high-quality output |
| `:gupgrade` | ID132 | Automatic Output Upgrade | Self-Correction, Quality Control, Improvement | Before final output, continuous improvement, enhancing clarity and actionability |

---

### 4.2. Critical Thinking & Problem Framing
These snippets encourage GPT to think more deeply, identify potential issues, explore alternative perspectives, and structure complex problems using established mental models and frameworks.

| Trigger | ID | Name | Tags | Use Cases |
| :------------- | :--- | :------------------------------------ | :-------------------------------------- | :--------------------------------------------------------------------------------------------------------- |
| `:gblind` | ID003 | Check for Overlooks and Biases | Feedback, Critical Thinking, Blind Spots | Identifying omissions, checking for bias, comprehensive review |
| `:gthink` | ID005 | Step-by-Step Thinking | Thinking, Logic, Reasoning | Structured problem-solving, detailed explanations, avoiding assumptions |
| `:gframe` | ID006 | Reframe Problem Perspective | Framing, Perspective, Strategy | Alternative views, creative problem-solving, strategic thinking |
| `:gwhy` | ID007 | Explain Reasoning or Assumption | Clarity, Reasoning, Justification | Understanding rationale, uncovering hidden assumptions, logical transparency |
| `:gspot` | ID012 | Identify Assumptions and Blind Spots | Critical Thinking, Assumptions, Risks | Risk assessment, comprehensive analysis, identifying overlooked factors |
| `:gperspectives` | ID013 | Alternative Perspectives | Perspectives, Brainstorming, Problem-Solving | Generating new ideas, understanding different viewpoints, creative solutions |
| `:gbias` | ID045 | Identify Biases (Markup) | Bias, Markup, Critical Thinking | Uncovering prejudice, balanced analysis, improving objectivity |
| `:glens` | ID046 | Reframe from Another Point of View (Markup) | Perspective, Markup, Reframing | Creative problem-solving, empathy building, diverse thinking |
| `:gsocratic` | ID056 | Socratic Method | Questioning, Socratic Method, Deep Inquiry | Guiding exploration, uncovering true needs, avoiding assumptions |
| `:gredteam` | ID058 | Red Team/Devil's Advocate | Red Team, Critical Analysis, Risk Assessment | Identifying flaws, stress-testing plans, counter-argument generation |
| `:gdigdeep` | ID064 | Dig Deeper Insight | Deep Dive, Insight, Critical Thinking | Uncovering core principles, cutting through noise, identifying high-leverage directions |
| `:gcore` | ID065 | Core Insight & Next Steps | Insight, Next Steps, Conciseness | Quick decision-making, identifying priorities, focused action |
| `:gecavate` | ID066 | Excavate Deeper Levels | Deep Dive, Exploration, Fundamental Principles | Root cause analysis, philosophical inquiry, uncovering hidden truths |
| `:grecursive` | ID071 | Recursive Questioning Framework | Questioning, Depth, Iteration | Uncovering subtle truths, mapping nuance, iterative exploration |
| `:gdeepq` | ID072 | Keep Going Deeper | Depth, Questioning, Exploration | Root cause analysis, detailed inquiry, uncovering hidden issues |
| `:g5whys` | ID078 | 5 Whys Technique | 5 Whys, Root Cause Analysis, Problem-Solving | Identifying underlying issues, continuous improvement, debugging problems |
| `:greverse` | ID079 | Reverse the Goal/Assumption | Creativity, Reverse Thinking, Problem-Solving | Unconventional ideation, overcoming stagnation, extracting inverse insights |
| `:gperspect` | ID080 | Reframe from 3 Perspectives | Perspectives, Reframing, Critical Thinking | Exploring diverse viewpoints, understanding implications, creative analysis |
| `:gparadox` | ID100 | Explore Core Paradox | Paradox, Critical Thinking, Systems Thinking | Ethics, innovation, philosophy, positioning, uncovering deep tensions |
| `:gabyss` | ID104 | Question Flawed Premise | Critical Thinking, Assumptions, Blind Spot Detection | Escaping echo chambers, deep critical thinking, blind spot detection, re-evaluating core problems |
| `:gdice` | ID108 | Random Lens Reframe (Dice) | Creativity, Perspective, Problem-Solving | Breaking ruts, unblocking, shifting strategy view, generating diverse solutions |
| `:g1principle` | ID131 | First Principles Thinking | First Principles, Problem-Solving, Innovation | Fundamental analysis, unconventional problem-solving, building from scratch |

---

### 4.3. Summarization & Clarity Prompts
These snippets focus on distilling information into clear, concise, and understandable formats, adapting the output for different levels of detail and audience comprehension.

| Trigger | ID | Name | Tags | Use Cases |
| :---------- | :--- | :------------------------------ | :---------------------------------- | :--------------------------------------------------------------------- |
| `:gclarify` | ID008 | Simplify and Clarify | Clarity, Summarization, Simplification | Making complex topics understandable, general communication, educational content |
| `:gsummary` | ID009 | Concise Key Point Summary | Summarization, Conciseness, Key Points | Quick overviews, recaps, executive summaries |
| `:gtldr` | ID010 | TLDR Summary | Summarization, Brevity, TLDR | Very quick summaries, highlighting main takeaways, fast information consumption |
| `:gsimplify` | ID011 | Explain in Simpler Terms | Simplification, Explanation, Accessibility | Explaining complex topics to beginners, general audiences, quick learning |
| `:gtldrm` | ID034 | TLDR Summary (Markup) | Summarization, Markup, Conciseness | Quick overviews, recapping long conversations, fast information retrieval |
| `:gclarity` | ID053 | Rewrite at Three Clarity Levels | Clarity, Rewriting, Audience Adaptation | Tailoring content for different audiences, educational materials, multi-level communication |
| `:gladder` | ID060 | Explanation Abstraction Ladder | Abstraction, Explanation, Layered Understanding | Explaining complex topics, educational content, structured communication |
| `:gdensity` | ID070 | Chain of Density Prompting | Conciseness, Density, Information Richness | Maximizing impact per word, efficient communication, cutting filler |
| `:glayers` | ID076 | Structured Layers Response | Structure, Summarization, Readability | Progressive disclosure, quick consumption, detailed understanding |
| `:gcompact` | ID096 | Compact Essential Points | Conciseness, Brevity, Efficiency | Quick answers, avoiding fluff, direct communication |
| `:ghaiku` | ID106 | Explain with Constraints (Haiku) | Brevity, Clarity, Communication | Training brevity, edge-case communication, testing clarity, creative writing exercises |

---

### 4.4. Planning & Organization Prompts
These snippets help structure ideas, break down complex tasks, prioritize efforts, and plan out workflows, ensuring clarity and efficiency in project execution.

| Trigger | ID | Name | Tags | Use Cases |
| :----------- | :--- | :---------------------------- | :---------------------------------- | :--------------------------------------------------------------------- |
| `:gsteps` | ID014 | Break Down into Steps | Process, Step-by-Step, Planning | Project planning, task breakdown, logical sequencing |
| `:gprioritize` | ID015 | Prioritize by Impact and Effort | Prioritization, Decision-Making, Strategy | Task management, project planning, resource allocation |
| `:gaction` | ID018 | Translate to Action Plan | Action Planning, Implementation, Strategy | Converting insights to steps, practical application, project execution |
| `:gnext` | ID036 | Next Logical Step (Markup) | Action, Markup, Next Steps | Guiding conversation, planning next actions, task sequencing |
| `:gmap` | ID039 | High-Level Overview (Markup) | Overview, Markup, Structure | Understanding complex ideas, conceptual mapping, high-level planning |
| `:gcheckpoint` | ID040 | List Current Checkpoints (Markup) | Progress, Markup, Checkpoints | Tracking progress, summarizing key insights, maintaining context |
| `:goutline` | ID044 | Generate Structured Outline (Markup) | Outline, Markup, Structure | Content creation, planning, organizing thoughts |
| `:gflow` | ID061 | Decision Tree/Flow | Decision-Making, Flowchart, Planning | Guiding decisions, process mapping, understanding complex scenarios |
| `:gdeepplan` | ID067 | GPT-Driven Deep Research Plan | Research, Planning, Strategy | Structured research, identifying high-value questions, synthesizing findings |
| `:gbreakdown` | ID073 | Modular Breakdown Prompting | Structure, Modularity, Organization | Content creation, technical documentation, easy navigation |
| `:gmodular` | ID074 | Modular Section Breakdown | Structure, Modularity, Organization | Simplifying complex topics, structured writing, easy content navigation |
| `:gmixin` | ID089 | Mixin Structure | Structure, Formatting, Decision-Making | Standardized reporting, clear communication, structured problem-solving |
| `:gblueprint` | ID094 | Structure with Known Pattern | Structure, Patterns, Organization | Consistent formatting, applying design principles, structured problem-solving |
| `:gapi` | ID095 | API-like Structure | Structure, API, Formatting | Standardized data exchange, consistent output, programmatic interaction |

---

### 4.5. Evaluation & Comparison Prompts
These snippets enable detailed assessment of ideas, options, and responses, facilitating informed decision-making through structured comparisons, scoring, and critical analysis.

| Trigger | ID | Name | Tags | Use Cases |
| :------------- | :--- | :------------------------------------ | :-------------------------------------- | :--------------------------------------------------------------------------------------------------------- |
| `:gcompare` | ID019 | Compare Against Alternatives | Comparison, Evaluation, Trade-offs | Decision-making, benchmarking, understanding pros and cons |
| `:gdebate` | ID037 | Show Opposing Viewpoints (Markup) | Debate, Markup, Perspectives | Balanced discussion, understanding controversies, exploring different sides |
| `:gcompare2` | ID077 | Compare Two Responses | Comparison, Evaluation, Analysis | Reviewing GPT variants, comparing ideas, selecting best options |
| `:gweights` | ID081 | Score with Weighted Criteria | Prioritization, Scoring, Decision-Making | Objective evaluation, complex decision support, transparent selection |
| `:gice` | ID082 | ICE Framework Prioritization | Prioritization, Framework, Decision-Making | Product management, initiative selection, rapid prototyping |
| `:grice` | ID083 | RICE Framework Prioritization | Prioritization, Framework, Decision-Making | Product roadmap planning, feature prioritization, resource allocation |
| `:grank` | ID084 | Rank by Value | Ranking, Prioritization, Evaluation | Selecting best options, strategic alignment, justifying choices |
| `:ggrade` | ID085 | Grading Rubric Assessment | Grading, Rubric, Assessment | Evaluating performance, quality control, objective feedback |
| `:gfilter` | ID086 | Filter Options by Criteria | Filtering, Prioritization, Shortlisting | Quick decision-making, narrowing down choices, urgent tasks |
| `:gwhyall` | ID087 | Justify All Suggestions | Justification, Reasoning, Transparency | Explaining decisions, building trust, structured communication |
| `:gjustify` | ID088 | Justify Each Option/Step | Justification, Reasoning, Conciseness | Explaining choices, ensuring logical flow, brief insights |
| `:gscore` | ID110 | Score Output by Criteria | Scoring, Evaluation, Quality Assessment | Grading ideas, comparing answers, reviewing copy, objective feedback |
| `:grubric` | ID111 | Evaluate Using Rubric | Rubric, Evaluation, Quality Control | Structured assessment, comparing performance, identifying improvement areas |
| `:gcritique` | ID112 | Critique Own Output | Critique, Self-Correction, Expert Review | Expert reviews, second passes, ideation sharpening, continuous improvement |
| `:gassess` | ID114 | Assess Key Assumptions | Assumptions, Risk Assessment, Validation | Strategy, forecasting, critical thinking, reducing project risk |
| `:gtruth` | ID115 | Fact-Checker/Peer Reviewer | Fact-Checking, Review, Skepticism | Ensuring accuracy, verifying claims, objective reporting |
| `:gmeasurelang` | ID116 | Use Measurement-Based Language | Measurement, Data-Driven, Persuasion | Data-driven writing, strategy, persuasive reasoning, objective reporting |
| `:gfitness` | ID117 | Fitness Score Evaluation | Scoring, Fitness, Quality Assessment | Grading output, comparing solutions, optimizing for specific goals |

---

### 4.6. Simulation & Role-Playing Prompts
These snippets instruct GPT to simulate real-world scenarios, role-play different personas, and explore various outcomes, enhancing understanding and strategic foresight.

| Trigger | ID | Name | Tags | Use Cases |
| :------------- | :--- | :-------------------------------- | :---------------------------------- | :--------------------------------------------------------------------- |
| `:gsimthink` | ID021 | Simulate Thoughtful Approach | Simulation, Thinking, Reasoning | Understanding complex decision processes, learning from simulated experts, strategic foresight |
| `:gsimrole` | ID022 | Roleplay Simulation | Simulation, Roleplay, Perspective | Understanding stakeholder views, preparing for interactions, empathy building |
| `:gsimchat` | ID023 | Simulate Realistic Conversation | Simulation, Conversation, Communication | Scriptwriting, dialogue practice, understanding interpersonal dynamics |
| `:gsimchoices` | ID024 | Simulate Realistic Choices | Simulation, Decision-Making, Options | Exploring possibilities, understanding motivations, preparing for scenarios |
| `:gsimerror` | ID025 | Simulate Potential Errors | Simulation, Risk Assessment, Error Analysis | Preventing mistakes, pre-mortem analysis, training for potential issues |
| `:gsimdebate` | ID026 | Simulate Brief Debate | Simulation, Debate, Critical Thinking | Exploring pros and cons, understanding controversies, exploring different sides |
| `:gsimjourney` | ID027 | Simulate Experience Journey | Simulation, Journey Mapping, User Experience | Understanding user flows, product design, empathizing with user struggles |
| `:gsimsystem` | ID028 | Simulate System Behavior | Simulation, Systems Thinking, Risk Analysis | Stress testing, understanding complex systems, identifying emergent behaviors |
| `:gsimscenario` | ID029 | Simulate Full Scenario | Simulation, Scenario Planning, Foresight | Strategic planning, crisis preparation, exploring future possibilities |
| `:gsimmentor` | ID030 | Simulate Wise Mentor Guidance | Simulation, Mentorship, Guidance | Personal development, decision support, learning from experienced perspectives |
| `:gsim` | ID041 | Simulate Realistic Response (Markup) | Simulation, Markup, Realism | Understanding human behavior, system response, realistic scenario planning |
| `:gtimeshift` | ID062 | Timeshift Simulation | Simulation, Foresight, Evolution | Future planning, predicting trends, understanding long-term impacts |
| `:gvillain` | ID101 | Villain Exploitation & Protection | Risk, Security, Dark Patterns | Cybersecurity, legal, UX, dark patterns, propaganda awareness, proactive defense |
| `:gtimeless` | ID107 | Timeless Perspectives | Foresight, Historical Analysis, Product Durability | Future-back thinking, historical analysis, product durability, understanding long-term trends |

---

### 4.7. GPT Management & Interaction
These snippets manage the state and behavior of the GPT model, including memory updates, context handling, instruction generation, and managing structured interactions.

| Trigger | ID | Name | Tags | Use Cases |
| :------------- | :--- | :------------------------------------ | :---------------------------------- | :--------------------------------------------------------------------- |
| `:gask` | ID004 | Ask Clarifying Questions | Clarity, Understanding, Context | Ensuring relevance, getting more information, tailoring responses |
| `:gconstraints` | ID017 | Improve Under Constraints | Constraints, Optimization, Problem-Solving | Resource limitations, efficiency improvement, creative constraint challenges |
| `:gselect` | ID051 | Numbered Output for Selection | Interaction, Numbering, Selection | Interactive prompts, option selection, structured feedback |
| `:gnumberify` | ID052 | Reformat as Numbered List | Formatting, Numbering, Readability | Structuring past responses, easy referencing, improving organization |
| `:gframework` | ID054 | Use Known Framework | Frameworks, Structure, Problem-Solving | Structured analysis, applying methodologies, consistent approach |
| `:gusecases` | ID057 | List Use Cases | Use Cases, Brainstorming, Application | Product development, understanding utility, identifying market opportunities |
| `:gboiler` | ID059 | Boilerplate Template | Template, Reusability, Formatting | Creating standardized documents, automating content, quick starts |
| `:ginstructify` | ID063 | Generate Custom GPT Instructions | Custom GPT, Instructions, AI Management | Creating personalized AI assistants, saving interaction preferences, building AI personas |
| `:grecalibrate` | ID068 | Recalibrate Research Path | Research, Recalibration, Strategy | Course correction, ensuring relevance, optimizing research efforts |
| `:glensresearch` | ID069 | Apply New Research Lens | Research, Perspective, Critical Thinking | Exploring diverse viewpoints, uncovering new insights, challenging assumptions |
| `:gdials` | ID075 | Apply Dials to Output | Customization, Tone, Style | Adjusting communication style, tailoring content, experimenting with voice |
| `:gversion` | ID090 | Version Control Note | Versioning, Tracking, Documentation | Tracking prompt changes, collaborative work, historical context |
| `:gtest` | ID091 | Self-Check Output | Self-Correction, Quality Control, Review | Ensuring accuracy, avoiding errors, improving response quality |
| `:ginject` | ID092 | Minimal Context Injection | Context, Input, Efficiency | Providing focused information, streamlining AI responses, setting clear parameters |
| `:glint` | ID093 | Linter for Prompt Review | Prompt Engineering, Review, Clarity | Improving prompt quality, identifying issues in instructions, refining AI input |
| `:glog` | ID099 | Log Internal Reasoning Process | Reasoning, Transparency, Logging | Debugging AI output, understanding AI decision-making, auditing AI responses |
| `:gmutate` | ID102 | Mutate Idea to Extreme | Creativity, Ideation, Innovation | Creative ideation, testing startup ideas, pushing originality, breaking conventional thinking |
| `:garchitecture` | ID103 | Design Concept Like an Architect | Architecture, Frameworks, Systems Design | Designing frameworks, systems design, teaching, product logic, structural understanding |
| `:gjump` | ID105 | Connect to Unrelated Idea | Creativity, Metaphor, Interdisciplinary | Creativity, interdisciplinary strategy, storytelling, generating fresh perspectives |
| `:gdeathbed` | ID109 | Deathbed Summary | Purpose, Storytelling, Values | Purpose clarity, storytelling, values-based prioritization, profound reflection |
| `:gupdate` | ID118 | Update GPT Memory | GPT Management, Memory, Context | Custom GPT memory syncing, preference setting, team context, long-term conversations |
| `:gfilecontext` | ID119 | GPT File Context | File Upload, Context, Data Extraction | Onboarding PDFs, CSVs, transcripts, strategy docs, quick analysis of documents |
| `:greset` | ID120 | Reset Conversation Context | Reset, Context, Reframing | Pivoting projects, context bloat, chat clutter cleanup, starting fresh |
| `:gpin` | ID121 | Pin Context for Session | Context, Persistence, Focus | Long projects, writing assistants, simulated team roles, maintaining consistent parameters |
| `:gsnapshot` | ID122 | Snapshot for GPT Handoff | Handoff, Summarization, Portability | Custom GPT handoffs, exportable briefings, prompt portability, team collaboration |
| `:gmeta` | ID123 | Generate Custom GPT Instructions (Meta) | GPT Management, Persona, AI Behavior | Building GPT personas, evolving role behaviors |
| `:gasklimits` | ID124 | Ask About GPT Limits | Boundaries, Clarity, Troubleshooting | Boundary awareness, dynamic prompting, troubleshooting confusion |
| `:greflect` | ID125 | GPT Self-Reflection | Reflection, Self-Correction, Performance Improvement | Meta-cognition triggering, GPT performance steering |

---

### 4.8. Specialized Frameworks & Models
These snippets apply specific analytical or design frameworks (like Double Diamond, JTBD, LIFT, First Principles) to guide GPT's thinking and output for structured problem-solving.

| Trigger | ID | Name | Tags | Use Cases |
| :----------- | :--- | :---------------------------- | :---------------------------------- | :--------------------------------------------------------------------- |
| `:gddiamond` | ID126 | Double Diamond Framework | Framework, Problem-Solving, Design Thinking | Product and UX challenges, strategy brainstorms, bottleneck busting, team ideation prep |
| `:gddfast` | ID127 | Compact Double Diamond | Framework, Problem-Solving, Conciseness | Quick problem clarification, rapid ideation, concise strategic thinking |
| `:gjtbd` | ID129 | Jobs to Be Done Analysis | JTBD, User Needs, Product Analysis | Product development, understanding user motivations, identifying market opportunities |
| `:glift` | ID130 | LIFT Model Evaluation | LIFT Model, Conversion, Optimization | Marketing, UX design, conversion rate optimization, improving persuasive communication |

---

## 5. Installation

To get started with `gpt-intelli-prompt-pro`, simply follow these steps:
1.  **Locate your Espanso `match` directory:**
    * **macOS:** `~/Library/Application Support/espanso/match/`
    * **Linux:** `~/.config/espanso/match/`
    * **Windows:** `%APPDATA%\espanso\match\`
2.  **Save the file:** Copy the entire YAML content from `gpt-intelli-prompt-pro.yml` into a new file named `gpt-intelli-prompt-pro.yml` inside your `match` directory.
3.  **Restart Espanso:** Run `espanso restart` in your terminal to load the new snippets.

---

## 6. Contributing & Extending

We welcome contributions to expand and improve the `gpt-intelli-prompt-pro` toolkit!
If you feel like there's any important tag/snippet missing, feel free to create a Pull Request or open an [Issue](https://github.com/lamhizz/gpt-intelli-prompt-pro/issues/new).

* **Adding New Snippets**:
    * Ensure your new snippet fits into one of the existing logical units. If it introduces a new major theme, consider proposing a new group.
    * **Follow the Metadata Format**: Before each snippet, include these comments:
        ```yaml
        # ---
        # Name: [Has unique ID, and Name that in short defines what it is, e.g. "IDXXX - Name lorem ipsum"]
        # Tags: [Comma separated tags]
        # Use cases: [Comma separated, short labels of use-cases that answer "when to use"]
        # Description: Explains in one short paragraph how it works.
        ```
    * **Assign a Unique ID**: Increment the `ID` from the last snippet in the file.
    * **Trigger Convention**: All new triggers should start with `:g` followed by a short, intuitive, and descriptive name (e.g., `:gnewfeature`).

* **Detecting and Handling Duplicates**: Before submitting, please check for existing triggers with similar functionality. If a duplicate exists, propose how your new snippet improves upon or replaces the existing one based on the toolkit's goal of being a comprehensive, high-leverage prompt library.

---

## 7. Usage Examples

Here are a few ways you can combine `gpt-intelli-prompt-pro` snippets to create powerful GPT interactions:

* **Code Review & Refinement Flow:**
    1.  Start by pasting your code.
    2.  Type `:gthink` to ask GPT to analyze it step-by-step.
    3.  Follow with `:gcritique` to make GPT review its own analysis for flaws.
    4.  Then use `:grefine` to integrate your feedback or new context.

* **Strategic Problem-Solving:**
    1.  Describe your challenge.
    2.  Type `:gddiamond` to initiate a structured discovery process.
    3.  As GPT guides you through stages, use `:gask` if you need more clarity, or `:gblind` to check for overlooked aspects.
    4.  Conclude with `:gaction` to translate the defined solution into concrete next steps.

---

## 8. License & Contact

This project is licensed under the MIT License. See the [LICENSE](LICENSE-file-link) file for details.

For any issues, bug reports, or requests for new triggers, please file an issue on the GitHub repository.