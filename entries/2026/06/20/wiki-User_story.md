---
source: sources/wiki-User_story.md
source_url: https://en.wikipedia.org/wiki/User_story
---

## User Stories in Agile Software Development

User stories are informal, natural language descriptions of software system features, written from the perspective of an end user. Originating in Extreme Programming (XP) in 1997, they serve as boundary objects that facilitate sensemaking and communication between stakeholders, and help teams document their understanding of the system and its context.

## Key Concepts

- **Definition**: An informal, natural language description of a software feature written from the user's perspective
- **Three Cs** (Ron Jeffries, 2001): **Card** (physical token holding the concept), **Conversation** (verbal discussion between stakeholders), **Confirmation** (verification that objectives were reached)
- **Boundary object**: User stories bridge communication between different stakeholder groups (developers, customers, managers)
- **Acceptance criteria**: Notes defining what a story must do for the product owner to accept it as complete; all must be met for a story to be "done"
- **Story points**: Estimation technique using Fibonacci sequence values (1, 2, 3, 5, 8, 13) to rate complexity
- **Product owner** (in Scrum) or **product manager** is primarily responsible for writing and prioritizing user stories in the product backlog
- User stories are deliberately incomplete — they are "a promise for a conversation" (Alistair Cockburn)
- No strong evidence that user stories increase software success or productivity, but they facilitate sensemaking without premature problem structuring

## Commands and Syntax

**Connextra Template** (most common):
```
As a <role> I can <capability>, so that <receive benefit>
```
Note: The "so that" clause is optional (Mike Cohn).

**Feature Injection Template** (Chris Matts — value-first):
```
In order to <receive benefit> as a <role>, I can <goal/desire>
```

**Five Ws Template**:
```
As <who> <when> <where>, I want <what> because <why>
```

**Evil/Abuse User Story** (security-focused):
```
As a <malicious actor>, I want to <attack action> to <negative outcome>
```

**Given-When-Then** format for acceptance criteria (referenced but not detailed).

## Relationships

- **Hierarchy**: Stories < Epics < Themes < Initiatives/Programs (in tools like Jira; definitions vary across frameworks)
  - **Epic**: Large body of work spanning multiple sprints; groups related stories
  - **Theme**: Cross-cutting grouping that can span different hierarchy levels; used for tracking effort across categories
  - **Initiative/Program**: Highest-level grouping of epics (used in scaled agile frameworks like SAFe)
- **Story mapping** (Jeff Patton): Two-dimensional visualization — horizontal axis shows product objective coverage (epics/activities), vertical axis shows user needs ordered by priority; top row is the "walking skeleton"
- **User journey map**: Focuses on a single user category's chronological experience, mapping emotions and friction points
- **User stories vs. use cases**: Stories are brief, informal, conversation starters; use cases are detailed, structured narratives with main success scenarios and extensions
- Connected to: **Extreme Programming** (planning game), **Scrum** (product backlog, sprint planning), **Kanban** (board visualization), **Personas** (user archetypes driving stories)

## Exam-Relevant Points

- The Connextra template ("As a... I can... so that...") is the most prevalent format — know it by name
- Three Cs: Card, Conversation, Confirmation (Ron Jeffries, 2001)
- User stories originated with Kent Beck at the Chrysler C3 project (1997); Mike Cohn's 2004 book is the standard reference
- Acceptance criteria define the boundary of "done" — all criteria must be met
- **Limitations to know**: scale-up problems, vagueness/informality, lack of non-functional requirements, may not reflect technical constraints
- Story points use Fibonacci sequence for estimation
- Story maps have horizontal axis (product coverage/workflow) and vertical axis (priority/sophistication)
- User stories differ from use cases: stories are conversation starters; use cases are self-contained with structured flows
- Evil user stories are used for security threat modeling (OWASP context)
- The "so that" benefit clause is optional but recommended
- Stories can be written by any stakeholder — not exclusively the product owner
