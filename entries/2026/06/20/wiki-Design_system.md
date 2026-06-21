---
source: sources/wiki-Design_system.md
source_url: https://en.wikipedia.org/wiki/Design_system
---

## Design Systems: Frameworks for Consistent Digital Product Development

A design system is a comprehensive framework of standards, reusable components, and documentation that guides consistent development of digital products within an organization. It serves as a single source of truth for designers and developers, encompassing pattern/component libraries, style guides (font, color, spacing, dimensions, placement), design languages, coded components, brand languages, and documentation. Design systems establish common understanding between design, engineering, and product teams to ensure consistent user experiences.

## Key Concepts

- **Definition**: A comprehensive framework of standards, reusable components, and documentation guiding consistent digital product development
- **Single source of truth**: Serves as the canonical reference for all design and development decisions across an organization
- **Core components**: Pattern libraries, component libraries, style guides, design languages, coded components, brand languages, documentation
- **Design tokens**: Named variables storing specific design attributes (color, typography, spacing) — design decisions expressed in code; provide abstraction, flexibility, scalability, and consistency
- **Pattern language vs. design system**: A pattern language allows patterns to exist in many visual forms (e.g., a login form can have green or purple buttons); a design system constrains visual presentation with specific guidelines
- **UI kit vs. design system**: A UI kit is simply a set of UI components with no explicit usage rules; a design system includes rules, guidelines, and rationale
- **Atomic Design**: Brad Frost's 2016 methodology describing component-based layout design that popularized the term "design system"
- **W3C Design Tokens Community Group**: Working on open standards for design tokens

## Commands and Syntax

No CLI commands or configuration syntax are described in this source. Design tokens are referenced as named variables, typically implemented as:
- Key-value pairs mapping semantic names to design values (e.g., `color-primary: #0052CC`)
- Consumed across platforms via tools like Amazon's Style Dictionary
- Notable implementations: Google Material Design tokens, Adobe Spectrum tokens, Atlassian Design System tokens

## Relationships

- **User interface design**: Design systems are a tool within the broader UI design discipline
- **Design language**: Design systems often contain or implement a design language (specific visual guidelines for colors, typography)
- **Brand language**: Design systems encode brand identity into reusable components
- **Software design patterns**: Design systems evolved from the software pattern movement (Christopher Alexander's "A Pattern Language," 1977)
- **Digital product design**: Design systems directly support mobile application and website development
- **Component libraries / UI kits**: Design systems are a superset — they add rules, guidelines, and rationale on top of raw components
- **BEM methodology**: A systematic CSS naming approach (2010s) that addressed large-scale web project challenges alongside design systems

## Exam-Relevant Points

- **Notable design systems**: Lightning (Salesforce), Material Design (Google), Carbon (IBM), Fluent (Microsoft)
- **Historical origin**: Christopher Alexander's pattern language concept (1960s NATO conference), formalized in "A Pattern Language" (1977) with Silverstein and Ishikawa
- **Key milestone**: Yahoo! Design Pattern Library (2006) + YUI Library reopened mainstream interest in UI pattern languages
- **Google Material Design (2014)**: First to be called a "design language" by its creator (previously "Holo Theme")
- **Atomic Design (2016)**: Brad Frost's book popularized the term "design system"
- **Six advantages**: Streamlined workflows, unified language across teams, faster builds via reuse, cohesive UX, improved maintenance/scalability, stronger product focus
- **Design tokens**: Named variables for design attributes; exist in Material Design, Amazon Style Dictionary, Adobe Spectrum, Atlassian Design System; W3C community group developing open standards
- **Three-tier distinction**: Pattern language (flexible patterns) > Design system (patterns + visual rules + documentation) > UI kit (components only, no rules)
- **Risk**: Poorly implemented/maintained design systems become disorganized and reduce efficiency rather than improving it
