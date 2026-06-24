# Expeditionary Learning (EL) Education Skill Architecture

This repository contains the formalized skill definitions and structural blueprints for the **Expeditionary Learning Workshop Model and Expedition Planner**. It acts as a semantic engine and behavioral prompt layer that allows Large Language Models (LLMs) to ingest, understand, and generate highly aligned curriculum assets based on official EL Education design parameters.

The primary skill rules are defined in `skills.md`, which maps out the backwards planning methodology, the 4 Ts framework, case study architecture, and the iterative Workshop 2.0 daily lesson structure.

---

## Skill Capabilities & Core Mechanics

When an AI model initializes with `skills.md` embedded into its system context, it gains specialized competencies across two operational layers:

### 1. Macro-Level: Long-Term Expedition Design
The model utilizes structural frameworks from EL Education Learning Expedition Planner to assist educators with high-level curriculum mapping:
* **The 4 Ts Alignment Matrix:** Iteratively structures the core
* **Topic** (science/social studies content standards),
* **Targets** (assessable ELA/literacy and math standards),
* **Texts** (deep anchor text selection),
* and **Tasks** (performance products).
* **Case Study Scaffolding:** Breaks down comprehensive semester-long expeditions into targeted sub-units, explicitly generating unique case study guiding questions, fieldwork/expert integration logs, and separate diagnostic metrics for literacy and content targets.
* **Ongoing Skills Mapping:** Constructs continuous routines for independent reading volume, explicit academic/domain vocabulary building, reading fluency, and writing development (Standards W.4–W.10).

### 2. Micro-Level: Workshop 2.0 Instructional Execution
The model utilizes structural frameworks from Workshop 2.0 Lesson Template to build precise daily lesson blueprints. It rejects rigid linear delivery in favor of a flexible, responsive instructional flow:
* **Grapple & Discuss Architecture:** Generates text-dependent or problem-based prompts that force students to independently struggle with complex material *before* explicit teacher instruction.
* **Focus & Apply Iteration Cycles:** Generates modular lesson sections where the AI can split a standard period into multiple brief mini-lessons immediately followed by student application, directly adapting to the cognitive load of the targets.

---

## Target Use Cases

### Use Case 1: Automated Curriculum Generation
* **Context:** A school district adoption requires translating state science or social studies standards into authentic learning expeditions.
* **Execution:** Input your target state standards and available local resources. The AI model applies the backwards planning sequence to deliver a complete Expedition Plan, generating compelling guiding questions, anchoring text recommendations, and a scaffolded performance task sequence.

### Use Case 2: High-Alignment Lesson Scripting (Workshop 2.0)
* **Context:** An instructional coach or classroom teacher needs a detailed lesson plan for a highly technical anchor text.
* **Execution:** Provide the text selection and target standard. The AI outputs a complete 50-to-60 minute Workshop 2.0 plan, complete with precise timing windows, explicit teacher monitoring strategies for the **Grapple** phase, text-dependent discussion questions, and an independent **Apply** task.

### Use Case 3: Curriculum Auditing & Alignment Checks
* **Context:** An administrator wants to verify if existing school curriculum units match the rigor and non-linear flexibility of the EL model.
* **Execution:** Paste an existing unit or weekly lesson plan into the AI system. The skill parses the material against the criteria in `skills.md`, auditing the text complexity, checking if content and literacy assessments are cleanly separated, and identifying if the daily layout incorrectly uses static lecture structures instead of iterative focus/apply loops.

---

## Technical Integration & Linting

This skill specification is optimized for automated parsing and LLM system prompt injection:
* **Linter Validation:** Clean markdown separation ensures complete compatibility with standard markdown markdown-lint rules (`npx @google/design.md lint DESIGN.md`).
* **Format:** Plain language formatting ensures low-token overhead and high conceptual density when parsed as a system tool file or vector embedding asset.

---
## Acknowledgments & Attributions
This AI skill architecture is an original, transformative implementation derived from public pedagogical frameworks developed by EL Education Inc.. It references and cites structural definitions from:
EL Education Learning Expedition Planner 
and the Workshop 2.0 Lesson Template

