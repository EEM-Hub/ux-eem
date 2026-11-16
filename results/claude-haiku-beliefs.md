# Exam Results: ux-design.md

**Date:** 2026-06-23 10:44
**Model:** claude:haiku
**Score:** 37/45 (82%)

## Per-Question Results

- **Q1**: CORRECT — What is Fitts's law and how does it apply to web UI design?
- **Q2**: CORRECT — How does Hick's law relate to information architecture and navigation design?
- **Q3**: CORRECT — Explain the expertise reversal effect and its implications for progressive disclosure in web interfaces.
- **Q4**: CORRECT — How do Gestalt principles of proximity and similarity apply to visual hierarchy in web layouts?
- **Q5**: CORRECT — What is cognitive load theory and how do its three types map to UI design decisions?
- **Q6**: CORRECT — What are the usability problems with carousels in web design?
- **Q7**: WRONG — When is infinite scrolling appropriate versus pagination?
  - Expected: Infinite scrolling suits discovery-oriented tasks (social feeds, image browsing) where users don't need to reach specific content. Pagination is better for goal-directed tasks (search results, product listings) where users need to reference specific positions, compare items, or return to a known location.
  - Got: Based on the available beliefs, infinite scrolling is generally NOT recommended due to significant accessibility barriers and UX drawbacks; server-side pagination is preferred for large datasets, while hybrid approaches (load-more buttons or pagination indicators integrated with infinite scroll) can mitigate some of infinite scrolling's issues.
- **Q8**: CORRECT — What is progressive disclosure and what cognitive principles justify its use?
- **Q9**: WRONG — What are the usability concerns with modal windows?
  - Expected: Modal windows block interaction with the underlying page, disrupting user flow and potentially causing loss of context. They can trap keyboard focus creating accessibility problems, they interrupt task completion, and on mobile they often have dismiss targets that are too small to tap reliably.
  - Got: Modal dialogs fail across three independent dimensions: cognitive (habituation causes dismissal without reading, and modals can cover information needed to complete the modal's own task), security (focus-stealing intercepts input intended for other programs), and load management (split-attention effect from separating related information across modal and parent). Modal warning dialogs are particularly self-defeating because habituation causes users to dismiss without reading, and modals can block clipboard operations needed to complete the decision the modal requests.
- **Q10**: CORRECT — Why is the hamburger menu controversial in UX design?
- **Q11**: CORRECT — What are the four WCAG principles (POUR) and what does each require?
- **Q12**: CORRECT — How does WAI-ARIA complement semantic HTML for web accessibility?
- **Q13**: CORRECT — What is the most common cause of screen reader inaccessibility?
- **Q14**: CORRECT — How does progressive enhancement serve as an accessibility strategy?
- **Q15**: CORRECT — What does the WebAIM survey data show about the accessibility training gap?
- **Q16**: CORRECT — What caused the flat design usability crisis and how was it resolved?
- **Q17**: WRONG — How do grid systems support cognitive load management in web layouts?
  - Expected: Grid systems systematize spatial relationships through consistent margins, gutters, and column spacing, which leverage Gestalt proximity to create visual chunking. This reduces extraneous cognitive load by giving content a predictable spatial structure that users can process without conscious effort.
  - Got: Not directly established in provided beliefs
- **Q18**: CORRECT — What role does white space play in visual hierarchy according to Gestalt principles?
- **Q19**: CORRECT — How does responsive web design differ from adaptive design?
- **Q20**: CORRECT — What is the relationship between color theory and accessibility in web design?
- **Q21**: CORRECT — What is the difference between heuristic evaluation and cognitive walkthrough?
- **Q22**: CORRECT — How does A/B testing complement qualitative usability testing?
- **Q23**: CORRECT — What is Simpson's paradox and why does it matter for A/B test analysis?
- **Q24**: CORRECT — How does card sorting support information architecture design?
- **Q25**: WRONG — What does eye tracking reveal about user attention and the concept of the fold?
  - Expected: Eye tracking shows significantly more fixation on above-fold content, with studies suggesting an 84% attention differential. However, covert attention (processing without fixation) means fixation maps may overstate the difference, and there is no universal pixel definition for the fold across devices, limiting prescriptive application.
  - Got: Eye tracking validates the fold through fixation-based information processing: the 84% attention differential and 77% no-scroll behavior are explained by eye-tracking fixation data showing that content above the fold receives significantly more fixations and cognitive processing than content below the fold.
- **Q26**: CORRECT — What is user-centered design and what are its core principles?
- **Q27**: CORRECT — How do personas help close the mental-model gap between designers and users?
- **Q28**: CORRECT — What role do wireframes play in the UX design process?
- **Q29**: WRONG — What is a design system and how does it differ from a style guide?
  - Expected: A design system is a comprehensive collection of reusable components, design tokens, patterns, and guidelines that encode design decisions as implementable constraints. A style guide documents visual rules (colors, typography, spacing) but lacks the component architecture and enforcement mechanisms that make design systems programmatically enforceable.
  - Got: Based on the provided beliefs, I can define a design system but cannot directly compare it to a style guide, as style guides are not explicitly addressed in the knowledge base.
- **Q30**: CORRECT — How does design thinking's abductive reasoning approach apply to wicked problems in UX?
- **Q31**: CORRECT — What UX challenges do single-page applications introduce?
- **Q32**: WRONG — How do progressive web apps balance capabilities with accessibility?
  - Expected: PWAs use web standards (service workers, manifests) to provide native-like capabilities (offline access, push notifications, home screen installation) while maintaining the web's inherent accessibility advantages — URL addressability, progressive enhancement, and standards-based rendering.
  - Got: PWAs balance capabilities with accessibility through their dramatic size advantage (1-3% of native app size), which creates digital-access equity for developing markets with bandwidth constraints. This architectural efficiency—delivering offline support, push notifications, and hardware access with minimal file size—amplifies accessibility for populations most constrained by bandwidth and device storage.
- **Q33**: CORRECT — What is the relationship between web performance and user experience?
- **Q34**: CORRECT — How does above the fold apply in responsive web design?
- **Q35**: WRONG — What is the dual quality mandate in modern web architecture?
  - Expected: Modern web architecture has two complementary quality channels: remedial (design systems treating existing design debt, especially in SPAs) and preventive (progressive enhancement eliminating accessibility gaps by starting from an accessible baseline). Together they provide both corrective and preventive quality assurance.
  - Got: Performance optimization and visual affordance (signifier richness)
- **Q36**: CORRECT — How do design systems encode cognitive constraints like Fitts's law and Gestalt principles?
- **Q37**: CORRECT — What is the role of design tokens in enforcing visual standards?
- **Q38**: WRONG — How do design systems relate to ISO 9241 usability standards?
  - Expected: Design systems can implement ISO 9241's three quality dimensions at the component level: dialogue principles map to component behavior patterns, presentation attributes map to visual design rules, and usability factors map to measurable performance targets — making standards compliance systematic rather than ad hoc.
  - Got: Not directly established in the knowledge base
- **Q39**: CORRECT — What historical precedent exists for design system backlash?
- **Q40**: CORRECT — How does Material Design address the flat design signifier problem?
- **Q41**: CORRECT — What is Don Norman's affordance-signifier framework and why is it foundational?
- **Q42**: CORRECT — What are Jakob Nielsen's key contributions to usability?
- **Q43**: CORRECT — How did Three Mile Island influence HCI and usability thinking?
- **Q44**: CORRECT — You are reviewing a web application that uses infinite scrolling, hamburger navigation, and auto-playing carousels. What specific UX concerns would you raise?
- **Q45**: CORRECT — How would you evaluate whether a design system adequately addresses cognitive load management and accessibility?

## Wrong Answers (Detail)

### Q7: When is infinite scrolling appropriate versus pagination?
- **Expected:** Infinite scrolling suits discovery-oriented tasks (social feeds, image browsing) where users don't need to reach specific content. Pagination is better for goal-directed tasks (search results, product listings) where users need to reference specific positions, compare items, or return to a known location.
- **Got:** Based on the available beliefs, infinite scrolling is generally NOT recommended due to significant accessibility barriers and UX drawbacks; server-side pagination is preferred for large datasets, while hybrid approaches (load-more buttons or pagination indicators integrated with infinite scroll) can mitigate some of infinite scrolling's issues.

**Model response:**

```
```json
{
  "answer": "Based on the available beliefs, infinite scrolling is generally NOT recommended due to significant accessibility barriers and UX drawbacks; server-side pagination is preferred for large datasets, while hybrid approaches (load-more buttons or pagination indicators integrated with infinite scroll) can mitigate some of infinite scrolling's issues.",
  "explanation": "The knowledge base emphasizes infinite scrolling's substantial drawbacks: it creates accessibility barriers (users cannot easily reach footers or navigate via keyboard/screen readers), removes natural stopping cues (contributing to compulsive doomscrolling), and loses page addressability and deep-link capability. In contrast, server-side pagination is preferred for large datasets because it provides faster initial page load, better accessibility (works without JavaScript), and supports complex business logic. Pagination also maintains addressability through permanent deep links and page parameters. Client-side pagination is appropriate only for very small datasets. While infinite scrolling provides seamless browsing, the beliefs indicate that hybrid variations (load-more buttons or integrated pagination indicators) are recommended to mitigate its accessibility and UX drawbacks. AJAX hybrid pagination combines the efficiency benefits of server-side pagination with the feel of client-side seamlessness, offering a middle ground that addresses both performance and user experience concerns."
}
```
```

### Q9: What are the usability concerns with modal windows?
- **Expected:** Modal windows block interaction with the underlying page, disrupting user flow and potentially causing loss of context. They can trap keyboard focus creating accessibility problems, they interrupt task completion, and on mobile they often have dismiss targets that are too small to tap reliably.
- **Got:** Modal dialogs fail across three independent dimensions: cognitive (habituation causes dismissal without reading, and modals can cover information needed to complete the modal's own task), security (focus-stealing intercepts input intended for other programs), and load management (split-attention effect from separating related information across modal and parent). Modal warning dialogs are particularly self-defeating because habituation causes users to dismiss without reading, and modals can block clipboard operations needed to complete the decision the modal requests.

**Model response:**

```
```json
{
  "answer": "Modal dialogs fail across three independent dimensions: cognitive (habituation causes dismissal without reading, and modals can cover information needed to complete the modal's own task), security (focus-stealing intercepts input intended for other programs), and load management (split-attention effect from separating related information across modal and parent). Modal warning dialogs are particularly self-defeating because habituation causes users to dismiss without reading, and modals can block clipboard operations needed to complete the decision the modal requests.",
  "explanation": "Modal windows create multiple, structurally independent usability failures. The cognitive dimension is especially problematic: users habituate to modals and dismiss them without reading their content, and modals often cover the very information users need to make the decision the modal requests (e.g., a confirmation dialog blocking the data it asks about). The split-attention effect compounds this by forcing users to integrate information across a separated modal and parent window, increasing extraneous cognitive load. Usability experts recommend replacing modal warning dialogs with undo functionality instead, since undo avoids the modal interaction pattern entirely while providing better user experience."
}
```
```

### Q17: How do grid systems support cognitive load management in web layouts?
- **Expected:** Grid systems systematize spatial relationships through consistent margins, gutters, and column spacing, which leverage Gestalt proximity to create visual chunking. This reduces extraneous cognitive load by giving content a predictable spatial structure that users can process without conscious effort.
- **Got:** Not directly established in provided beliefs

**Model response:**

```
```json
{
  "answer": "Not directly established in provided beliefs",
  "explanation": "While the beliefs contain information about grids as structural frameworks and extensive detail about cognitive load management (extraneous load reduction, white space effects through Gestalt proximity, visual hierarchy, and chunking), they do not explicitly connect grid systems to cognitive load management. Plausible connections exist: grids organize white space (which manages working memory load through perceptual chunking), support visual hierarchy (reducing extraneous load), and enable consistent spacing that groups related information—but these relationships are inferred rather than directly stated. The beliefs treat grids as organizational structures separate from the cognitive load theories they separately describe."
}
```
```

### Q25: What does eye tracking reveal about user attention and the concept of the fold?
- **Expected:** Eye tracking shows significantly more fixation on above-fold content, with studies suggesting an 84% attention differential. However, covert attention (processing without fixation) means fixation maps may overstate the difference, and there is no universal pixel definition for the fold across devices, limiting prescriptive application.
- **Got:** Eye tracking validates the fold through fixation-based information processing: the 84% attention differential and 77% no-scroll behavior are explained by eye-tracking fixation data showing that content above the fold receives significantly more fixations and cognitive processing than content below the fold.

**Model response:**

```
```json
{
  "answer": "Eye tracking validates the fold through fixation-based information processing: the 84% attention differential and 77% no-scroll behavior are explained by eye-tracking fixation data showing that content above the fold receives significantly more fixations and cognitive processing than content below the fold.",
  "explanation": "Eye tracking reveals that most visual information is processed during fixations (brief pauses), not during rapid eye movements (saccades). The eye-mind hypothesis (Just & Carpenter 1980) provides the theoretical foundation linking where users look to what they cognitively process. Through this framework, eye-tracking fixation analysis empirically validates the fold concept: above-fold content receives substantially more fixations, explaining the documented 84% attention differential and Nielsen's finding that 77% of users do not scroll below the fold. However, eye tracking has a limitation: covert attention means users can attend to items they are not directly looking at, so fixation maps show eye location, not necessarily where attention was directed. Despite this caveat, eye tracking serves as the field's unified validation instrument for the fold effect at the macro-level layout scale."
}
```
```

### Q29: What is a design system and how does it differ from a style guide?
- **Expected:** A design system is a comprehensive collection of reusable components, design tokens, patterns, and guidelines that encode design decisions as implementable constraints. A style guide documents visual rules (colors, typography, spacing) but lacks the component architecture and enforcement mechanisms that make design systems programmatically enforceable.
- **Got:** Based on the provided beliefs, I can define a design system but cannot directly compare it to a style guide, as style guides are not explicitly addressed in the knowledge base.

**Model response:**

```
```json
{
  "answer": "Based on the provided beliefs, I can define a design system but cannot directly compare it to a style guide, as style guides are not explicitly addressed in the knowledge base.",
  "explanation": "A design system is a comprehensive framework of standards, reusable components, and documentation that serves as a single source of truth for consistent digital product development within an organization. It differs from a UI kit (which contains only components with no explicit usage rules) by adding rules, guidelines, and rationale on top of components. The provided beliefs establish a three-tier hierarchy where a design system occupies the middle ground between UI kits (components only) and pattern languages (more flexible patterns). However, the specific definition of a style guide and how it compares to a design system is not addressed in the available beliefs, so I cannot make that distinction with certainty."
}
```
```

### Q32: How do progressive web apps balance capabilities with accessibility?
- **Expected:** PWAs use web standards (service workers, manifests) to provide native-like capabilities (offline access, push notifications, home screen installation) while maintaining the web's inherent accessibility advantages — URL addressability, progressive enhancement, and standards-based rendering.
- **Got:** PWAs balance capabilities with accessibility through their dramatic size advantage (1-3% of native app size), which creates digital-access equity for developing markets with bandwidth constraints. This architectural efficiency—delivering offline support, push notifications, and hardware access with minimal file size—amplifies accessibility for populations most constrained by bandwidth and device storage.

**Model response:**

```
```json
{
  "answer": "PWAs balance capabilities with accessibility through their dramatic size advantage (1-3% of native app size), which creates digital-access equity for developing markets with bandwidth constraints. This architectural efficiency—delivering offline support, push notifications, and hardware access with minimal file size—amplifies accessibility for populations most constrained by bandwidth and device storage.",
  "explanation": "PWAs represent a convergence of mobile web and native capabilities while maintaining the web's lightweight distribution model. The size advantage is not incidental but foundational to accessibility: populations with limited bandwidth and storage are exactly those served by PWAs' 1-3% native app size ratio, making PWAs a digital-access equity mechanism. However, this capability-accessibility balance creates architectural tensions: PWAs depend on service workers and client-side routing (SPA patterns) for capabilities, while accessible implementation requires semantic HTML and platform defaults that SPAs can break, requiring explicit compensatory mechanisms (History API, accessibility tree management) to maintain accessibility alongside capabilities."
}
```
```

### Q35: What is the dual quality mandate in modern web architecture?
- **Expected:** Modern web architecture has two complementary quality channels: remedial (design systems treating existing design debt, especially in SPAs) and preventive (progressive enhancement eliminating accessibility gaps by starting from an accessible baseline). Together they provide both corrective and preventive quality assurance.
- **Got:** Performance optimization and visual affordance (signifier richness)

**Model response:**

```
```json
{
  "answer": "Performance optimization and visual affordance (signifier richness)",
  "explanation": "SPA architecture creates an inherent design tension requiring designers to satisfy two competing quality mandates simultaneously: aggressive code optimization for performance (reducing file size, minimizing JavaScript) and visual signifier richness for usability (affording action possibilities through visual depth and contrast). This dual mandate arises because SPAs intensify the frontend performance challenge while affordance theory demonstrates that the minimalist visual approaches such optimization encourages produce measurable usability degradation (22% slower task completion with flat design). Designers must find patterns that are simultaneously performance-efficient and signifier-rich—a constraint unique to modern web architecture where mobile dominance and SPA complexity compound the platform's inherent frontend performance bottleneck."
}
```
```

### Q38: How do design systems relate to ISO 9241 usability standards?
- **Expected:** Design systems can implement ISO 9241's three quality dimensions at the component level: dialogue principles map to component behavior patterns, presentation attributes map to visual design rules, and usability factors map to measurable performance targets — making standards compliance systematic rather than ad hoc.
- **Got:** Not directly established in the knowledge base

**Model response:**

```
```json
{
  "answer": "Not directly established in the knowledge base",
  "explanation": "While the beliefs describe design systems as comprehensive frameworks providing standards, reusable components, and documentation for consistent development, and ISO 9241 as a formal standard addressing interface quality across three dimensions (dialogue principles, presentation attributes, and usability factors), the specific relationship between design systems and ISO 9241 is not explicitly documented in the available beliefs. However, a logical connection exists: design systems—particularly through design tokens and documented rules—provide the implementation mechanism for operationalizing ISO 9241's requirements (consistency, suitability for task, clarity, etc.) as enforceable, reusable design decisions across products, though this relationship is inferred rather than directly stated in the knowledge base."
}
```
```


## By Objective

- **None**: 37/45 (82%)
