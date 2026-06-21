---
source: sources/wiki-Progressive_disclosure.md
source_url: https://en.wikipedia.org/wiki/Progressive_disclosure
---

## Progressive Disclosure in Interaction Design

Progressive disclosure is an interaction design pattern that reduces complexity by initially presenting only essential features and information, then revealing advanced or rarely-used options on demand. It makes applications easier to learn and less error-prone by deferring secondary content to subsequent screens or expandable sections, showing information only when it becomes relevant to the user's current task.

## Key Concepts

- **Core principle**: Hide complexity until the user needs it — show a simplified default view, with advanced options available on request
- **Purpose**: Reduces learning curve, lowers error rates, and prevents cognitive overload
- **Mechanism**: Uses secondary screens, expandable sections, or disclosure widgets to layer information
- **Classic example**: macOS print dialog shows basic options by default; "Show Details" reveals advanced settings
- **Physical-world analogy**: Theme park queue design — only a small segment of the line is visible from any point, making waits feel more bearable
- **Origin**: Concept traces to Kristina Hooper Woolsey (Apple Human Interface Group, 1985), who advocated "selectively informing a user about a particular system, providing well-chosen bits and pieces that can constitute a general understanding"

## Commands and Syntax

Not applicable — this is a design pattern, not a technical specification. Implementation involves UI elements such as:
- **Disclosure widgets** (expanders, accordions, "Show more" buttons)
- **Staged dialogs** (wizard-style multi-step flows)
- **Contextual reveal** (showing options only when a prerequisite is met)

## Relationships

- **Interaction design**: Progressive disclosure is a subpattern within the broader field of interaction design
- **Disclosure widgets**: The primary UI control used to implement this pattern (expandable/collapsible sections)
- **Chunking**: Related writing/information architecture technique — breaking content into digestible pieces
- **Information architecture**: Progressive disclosure is an information-layering strategy
- **Learnability and error prevention**: Directly supports Nielsen's usability heuristics around recognition over recall and error prevention
- **Wizard pattern**: Multi-step workflows are a form of progressive disclosure applied to task completion

## Exam-Relevant Points

- Progressive disclosure **defers advanced features to secondary screens** and **reveals information contextually** as it becomes relevant
- The pattern serves two goals: **easier learning** and **fewer errors**
- Kristina Hooper Woolsey of the **Apple Human Interface Group** articulated the foundational idea in **1985**
- The macOS **print dialog** is the canonical example (basic view with "Show Details" expansion)
- Progressive disclosure applies beyond software — the **theme park queue** analogy demonstrates the principle in physical design
- The pattern is distinct from **responsible disclosure** (a security concept) — do not confuse the two
