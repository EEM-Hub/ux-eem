---
source: sources/wiki-Heuristic_evaluation.md
source_url: https://en.wikipedia.org/wiki/Heuristic_evaluation
---

## Heuristic Evaluation: Usability Inspection Method

Heuristic evaluation is a usability inspection method where evaluators examine a user interface and judge its compliance with recognized usability principles ("heuristics"). Developed by Rolf Molich and Jakob Nielsen, it is one of the most informal and cost-effective methods in human-computer interaction for identifying usability problems without requiring user recruitment. Multiple heuristic frameworks exist (Nielsen, Gerhardt-Powals, Shneiderman, Weinschenk & Barker), each offering a different lens on interface quality.

## Key Concepts

- **Definition**: Evaluators judge an interface against established usability principles; problems are typically rated on a numeric severity scale.
- **Optimal evaluator count**: 3–5 evaluators recommended; more than 5 adds cost without proportional benefit (Nielsen).
- **Individual-first process**: Each evaluator must examine the interface independently before group discussion to reduce confirmation bias.
- **Observer trade-off**: Adding an observer reduces evaluator workload (verbal analysis vs. written reports) but increases overhead cost.
- **Strengths**: Fast (days, not weeks), inexpensive, no user recruitment needed, useful at early design stages and before user-based testing.
- **Weaknesses**: Results are highly influenced by evaluator expertise; no empirical user data produced; findings differ from what performance testing reveals — each method uncovers different problem sets.
- **Use case context**: Often conducted within typical user task scenarios to assess interface compatibility with user needs.
- **Domain/culture limitations**: General heuristic sets may miss domain-specific or culture-specific usability issues; specialized heuristic sets can be developed to address this gap.

## Commands and Syntax

Not applicable (this is a methodology, not a tool). However, the procedural steps are:

1. **Select 3–5 evaluators** with usability expertise.
2. **Each evaluator independently** reviews the interface against a chosen heuristic set.
3. **Document findings** — either via written reports (no observer) or verbal analysis transcribed by an observer.
4. **Aggregate results** across evaluators in a group session.
5. **Rate severity** of each identified problem on a numeric scale.
6. **Report** consolidated findings to the design/development team.

## Relationships

- **Parent method**: Usability inspection (heuristic evaluation is one type).
- **Complements user-based testing**: Best used before user testing to eliminate obvious issues and focus subsequent testing scope.
- **Differs from software performance testing**: Each uncovers different problem sets — they are complementary, not substitutive.
- **Related to cognitive engineering**: Gerhardt-Powals' principles bridge HCI heuristics and cognitive load theory.
- **Connected to progressive disclosure**: Nielsen's heuristic #8 (aesthetic/minimalist design) links directly to progressive disclosure as a design pattern.
- **Confirmation bias**: The individual-first methodology requirement is a direct countermeasure to cognitive bias in group evaluation.
- **Use cases**: Evaluation is often structured around use cases to ground the review in realistic user tasks.

## Exam-Relevant Points

- **Nielsen's 10 Heuristics** (memorize all 10):
  1. Visibility of system status
  2. Match between system and real world
  3. User control and freedom (undo/redo, "emergency exit")
  4. Consistency and standards
  5. Error prevention (eliminate error-prone conditions or confirm before commit)
  6. Recognition rather than recall (minimize memory load)
  7. Flexibility and efficiency of use (accelerators for experts)
  8. Aesthetic and minimalist design (remove irrelevant information)
  9. Help users recognize, diagnose, and recover from errors (plain language, no codes)
  10. Help and documentation (searchable, task-focused, concrete steps)

- **Shneiderman's 8 Golden Rules** (1986, predates Nielsen's final set):
  1. Strive for consistency
  2. Enable shortcuts for frequent users
  3. Offer informative feedback
  4. Design dialog to yield closure
  5. Offer simple error handling
  6. Permit easy reversal of actions
  7. Support internal locus of control
  8. Reduce short-term memory load

- **Gerhardt-Powals' 10 Cognitive Engineering Principles**: Focus on reducing cognitive load — automate unwanted workload, reduce uncertainty, fuse data, use meaningful names, group data consistently, limit data-driven tasks, practice judicious redundancy.

- **Weinschenk & Barker (2000)**: 20 categories synthesized from multiple providers — notable additions beyond Nielsen include modal integrity, cultural propriety, suitable tempo, and interpretation (system guesses user intent).

- **3–5 evaluators** is the research-backed recommendation; individual evaluators are "mostly quite bad" alone (Nielsen's own finding).

- **Individual before group** is mandatory to avoid confirmation bias — this is a testable procedural requirement.

- **Key limitation to know**: Heuristic evaluation produces expert opinion, not empirical user data. It is "one-sided" and finds different problems than user testing or performance testing.

- **Origin**: Molich and Nielsen, 1989–1990; Nielsen's updated set 1994; final set 2005.
