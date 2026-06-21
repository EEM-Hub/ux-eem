---
source: sources/wiki-Usability.md
source_url: https://en.wikipedia.org/wiki/Usability
---

## Usability: Principles, Evaluation Methods, and Design Standards

Usability is the capacity of a system to enable users to perform tasks safely, effectively, and efficiently while enjoying the experience. This foundational UX concept encompasses measurable quality attributes—learnability, efficiency, memorability, error rate, and satisfaction—and is governed by ISO standards. The page covers definitions, design principles, cognitive models, inspection methods, inquiry methods, and Nielsen's ten heuristics.

## Key Concepts

- **ISO definition**: "The extent to which a product can be used by specified users to achieve specified goals with effectiveness, efficiency, and satisfaction in a specified context of use."
- **Five usability components** (Nielsen/Shneiderman): Learnability, Efficiency, Memorability, Errors, Satisfaction
- **Usability vs. Utility**: Usability is how easy/pleasant the interface is; utility is whether it provides needed functionality. Together they form "usefulness."
- **Usability is a non-functional requirement** — cannot be measured directly, only through indirect measures (e.g., reported problems, task completion time, error rates)
- **"Intuitive" means "familiar"** — Jef Raskin argued intuitive interaction relies on prior exposure to similar systems, not innate understanding. The pause icon "||" is conventional, not intuitive.
- **Prototypicality**: Users prefer designs that conform to recognized norms — deviation from shared expectations reduces perceived usability.
- **Usability testing vs. usability engineering**: Testing measures ease of use; engineering is the research/design process ensuring good usability.

## Three Core Design Principles (Gould & Lewis)

1. **Early focus on end users and tasks** — use personas, cognitive modeling, contextual inquiry; maintain direct contact with potential users
2. **Empirical measurement** — test on real users with behavioral measurements (time, errors, task completion); avoid reviewing/demonstrating the system before user tests
3. **Iterative design** — cyclic process of prototyping, testing, analyzing, refining; requires identification of changes, ability to make them, and willingness to do so

## Nielsen's Ten Heuristics

1. **Visibility of system status** — keep users informed with timely feedback
2. **Match between system and real world** — use user language, follow real-world conventions
3. **User control and freedom** — provide "emergency exits," support undo/redo
4. **Consistency and standards** — follow platform conventions
5. **Error prevention** — eliminate error-prone conditions or confirm before committing
6. **Recognition rather than recall** — make objects/actions/options visible; minimize memory load
7. **Flexibility and efficiency of use** — provide accelerators for expert users
8. **Aesthetic and minimalist design** — remove irrelevant information that competes with relevant content
9. **Help users recognize, diagnose, and recover from errors** — plain language, precise problem indication, constructive solutions
10. **Help and documentation** — searchable, task-focused, concrete steps

## Evaluation Methods

**Cognitive Modeling**:
- **GOMS** (Goals, Operators, Methods, Selection rules) — analyzes user complexity of interactive systems
- **Human Processor Model** — breaks tasks into perceptual (100ms), cognitive (70ms), and motor (70ms) processing cycles
- **Keystroke Level Model** — simplified GOMS with assumptions to reduce calculation complexity
- **Parallel Design** — multiple designers independently create solutions from same requirements, then cross-pollinate best ideas

**Inspection Methods**:
- **Heuristic evaluation** — most popular; quick, cheap; experts evaluate against heuristic principles
- **Card sorting** — users group content into categories to reveal mental models for information architecture
- **Tree testing** — evaluates findability/labeling separate from visual design
- **Ethnographic analysis** — field observations of artifacts, workflows, and interruptions in users' environments
- **Pluralistic inspection** — users, developers, and HF experts walk through scenarios together
- **Consistency inspection** — cross-product consistency review

**Inquiry Methods**:
- **Task analysis** — understanding user goals, workflows, and environments (physical, social, cultural, technological)
- **Focus groups** — 6–10 users discuss desires; used in product definition stage

## ISO Standards

| Standard | Scope |
|----------|-------|
| **ISO 9241** | Multi-part standard on ergonomics of human-system interaction (originally VDT office work) |
| **ISO/TR 16982:2002** | Usability methods supporting human-centered design; aimed at project managers |
| **IEC 62366** | Usability engineering specific to medical devices |

## Relationships

- **User-Centered Design / Participatory Design** — usability is operationalized through these design paradigms
- **Human-Computer Interaction** — parent discipline; usability is a core quality attribute
- **Ergonomics / Human Factors** — debated relationship; ergonomics = physiological, usability = psychological (some view usability as a software specialization of ergonomics)
- **Accessibility** — overlapping but distinct concept; "user friendly" sometimes conflated with accessible
- **Web Usability** — domain-specific application; Nielsen emphasizes zero tolerance for slow/difficult web experiences
- **User Experience** — usability is a component of UX, improved through iterative design
- **Information Architecture** — card sorting and tree testing directly inform IA decisions

## Exam-Relevant Points

- Know the **ISO definition of usability** verbatim: effectiveness, efficiency, satisfaction in a specified context of use
- **Five components**: Learnability, Efficiency, Memorability, Errors, Satisfaction — be able to define each
- **Nielsen's 10 heuristics** — memorize all ten with their core principle
- **Three design principles** (Gould & Lewis): early user focus, empirical measurement, iterative design
- **Usability testing ≠ usability engineering** — testing is measurement; engineering is the full design process
- **Human Processor Model timing**: perceptual ~100ms, cognitive ~70ms, motor ~70ms
- **GOMS** = Goals, Operators, Methods, Selection rules
- **Heuristic evaluation** is the most popular inspection method (quick, cheap, easy)
- **"Intuitive" = "familiar"** — based on prior experience, not innate understanding
- **Usability is a non-functional requirement** that must be quantified through indirect measures
- **Card sorting** reveals user mental models; **tree testing** evaluates information hierarchy independent of visual design
- **ISO 9241** covers human-system interaction broadly; **IEC 62366** is specific to medical devices
