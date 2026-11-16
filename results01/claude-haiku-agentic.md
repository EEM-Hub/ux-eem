# Exam Results: ux-design.md

**Date:** 2026-06-22 16:50
**Model:** claude:haiku
**Score:** 36/45 (80%)

## Per-Question Results

- **Q1**: CORRECT — What is Fitts's law and how does it apply to web UI design?
- **Q2**: CORRECT — How does Hick's law relate to information architecture and navigation design?
- **Q3**: CORRECT — Explain the expertise reversal effect and its implications for progressive disclosure in web interfaces.
- **Q4**: WRONG — How do Gestalt principles of proximity and similarity apply to visual hierarchy in web layouts?
  - Expected: Proximity causes elements placed close together to be perceived as a group, enabling white space to create visual chunking that reduces cognitive load. Similarity causes elements sharing visual properties (color, size, shape) to be perceived as related, supporting consistent visual hierarchies.
  - Got: Let me search the belief database using the available tools directly.

{"tool": "search_beliefs", "q
- **Q5**: CORRECT — What is cognitive load theory and how do its three types map to UI design decisions?
- **Q6**: WRONG — What are the usability problems with carousels in web design?
  - Expected: Carousels combine multiple usability anti-patterns: they violate user control by auto-advancing, create banner blindness, hide content behind interaction, distribute attention across panels reducing engagement with each, and introduce timing pressure that conflicts with self-paced reading.
  - Got: Carousels are harmful to usability because they auto-advance and steal user attention (causing habituation), hide content behind sequential navigation without user control, violate progressive disclosure principles by concealing content without user agency, remove stopping cues, and combine the worst properties of both modal dialogs and infinite scrolling.
- **Q7**: CORRECT — When is infinite scrolling appropriate versus pagination?
- **Q8**: WRONG — What is progressive disclosure and what cognitive principles justify its use?
  - Expected: Progressive disclosure stages information reveal to show only what is needed at each step. It is justified by working memory limits (reducing visible options reduces extraneous cognitive load), Gestalt grouping (fewer elements create clearer visual hierarchy), and Hick's law (fewer visible choices speed decision-making).
  - Got: Progressive disclosure is a design pattern that initially presents only essential features and information, then reveals advanced or rarely-used options on demand. It is justified by cognitive science through a complete mechanism chain: working memory limits (Miller's 7±2 chunks) necessitate extraneous cognitive load reduction, which is the only load type under designer control. Progressive disclosure achieves this reduction by staging information across interaction steps rather than overwhelming users with all options simultaneously. This approach is further validated by the 84% above-fold attention differential from eye-tracking research, which determines where disclosure stages should be positioned. The pattern reduces both learning curves and error rates while avoiding the habituation and information-blocking failures of modal alternatives.
- **Q9**: CORRECT — What are the usability concerns with modal windows?
- **Q10**: CORRECT — Why is the hamburger menu controversial in UX design?
- **Q11**: CORRECT — What are the four WCAG principles (POUR) and what does each require?
- **Q12**: CORRECT — How does WAI-ARIA complement semantic HTML for web accessibility?
- **Q13**: CORRECT — What is the most common cause of screen reader inaccessibility?
- **Q14**: CORRECT — How does progressive enhancement serve as an accessibility strategy?
- **Q15**: CORRECT — What does the WebAIM survey data show about the accessibility training gap?
- **Q16**: WRONG — What caused the flat design usability crisis and how was it resolved?
  - Expected: Flat design removed visual signifiers (shadows, gradients, dimensionality) that communicated interactivity, making interactive elements indistinguishable from decorative ones. This caused measurable usability degradation. Material Design resolved it by reintroducing controlled depth cues while maintaining a modern aesthetic.
  - Got: Let me try using the Tool format to search beliefs directly:

{"tool": "search_beliefs", "query": "f
- **Q17**: CORRECT — How do grid systems support cognitive load management in web layouts?
- **Q18**: CORRECT — What role does white space play in visual hierarchy according to Gestalt principles?
- **Q19**: CORRECT — How does responsive web design differ from adaptive design?
- **Q20**: CORRECT — What is the relationship between color theory and accessibility in web design?
- **Q21**: CORRECT — What is the difference between heuristic evaluation and cognitive walkthrough?
- **Q22**: CORRECT — How does A/B testing complement qualitative usability testing?
- **Q23**: CORRECT — What is Simpson's paradox and why does it matter for A/B test analysis?
- **Q24**: WRONG — How does card sorting support information architecture design?
  - Expected: Card sorting has users organize content items into categories that make sense to them, revealing their mental models for information grouping. Open card sorts discover natural categories; closed card sorts validate proposed structures. This grounds IA in user mental models rather than organizational assumptions.
  - Got: Let me search the belief database directly for relevant information.

{"tool": "search_beliefs", "qu
- **Q25**: CORRECT — What does eye tracking reveal about user attention and the concept of the fold?
- **Q26**: CORRECT — What is user-centered design and what are its core principles?
- **Q27**: WRONG — How do personas help close the mental-model gap between designers and users?
  - Expected: Personas synthesize user research into representative archetypes that make user needs concrete and communicable across a team. They help designers maintain empathy with users who have different mental models, preventing the team from unconsciously designing for themselves rather than their actual audience.
  - Got: I'll search the belief database for relevant knowledge about personas and the designer-user gap.

``
- **Q28**: CORRECT — What role do wireframes play in the UX design process?
- **Q29**: CORRECT — What is a design system and how does it differ from a style guide?
- **Q30**: CORRECT — How does design thinking's abductive reasoning approach apply to wicked problems in UX?
- **Q31**: WRONG — What UX challenges do single-page applications introduce?
  - Expected: SPAs break browser platform defaults including back button behavior, URL-based navigation, history management, and progressive enhancement. They must compensate for these broken defaults, creating design debt across multiple dimensions. Screen readers face particular challenges because content changes without page loads.
  - Got: SPAs create design debt across multiple dimensions: (1) performance optimization pressure drives minimalist aesthetics that degrade affordances/signifiers, (2) broken platform defaults (navigation, analytics, crawling) require explicit compensatory mechanisms (History API, manual tracking, SSR), and (3) addressability and content findability problems. These dimensions compound rather than merely add, creating multiplicative tension between functionality and aesthetics.
- **Q32**: WRONG — How do progressive web apps balance capabilities with accessibility?
  - Expected: PWAs use web standards (service workers, manifests) to provide native-like capabilities (offline access, push notifications, home screen installation) while maintaining the web's inherent accessibility advantages — URL addressability, progressive enhancement, and standards-based rendering.
  - Got: PWAs balance capabilities and accessibility through inherent architectural tension: gaining offline support, push notifications, and hardware access requires adopting the App Shell Model (an SPA pattern), which creates compounding accessibility barriers unless designers implement deliberate compensatory mechanisms for navigation, SEO, and content discoverability.
- **Q33**: CORRECT — What is the relationship between web performance and user experience?
- **Q34**: CORRECT — How does above the fold apply in responsive web design?
- **Q35**: CORRECT — What is the dual quality mandate in modern web architecture?
- **Q36**: CORRECT — How do design systems encode cognitive constraints like Fitts's law and Gestalt principles?
- **Q37**: CORRECT — What is the role of design tokens in enforcing visual standards?
- **Q38**: CORRECT — How do design systems relate to ISO 9241 usability standards?
- **Q39**: CORRECT — What historical precedent exists for design system backlash?
- **Q40**: CORRECT — How does Material Design address the flat design signifier problem?
- **Q41**: CORRECT — What is Don Norman's affordance-signifier framework and why is it foundational?
- **Q42**: WRONG — What are Jakob Nielsen's key contributions to usability?
  - Expected: Nielsen established usability as a systematic discipline through his 10 usability heuristics, the discount usability engineering methodology (including the finding that 5 users reveal ~85% of usability problems), founding the Nielsen Norman Group with Don Norman, and decades of evidence-based usability research and advocacy.
  - Got: {"tool": "search_beliefs", "query": "Nielsen usability heuristics principles methodology"}

Tool res
- **Q43**: CORRECT — How did Three Mile Island influence HCI and usability thinking?
- **Q44**: CORRECT — You are reviewing a web application that uses infinite scrolling, hamburger navigation, and auto-playing carousels. What specific UX concerns would you raise?
- **Q45**: CORRECT — How would you evaluate whether a design system adequately addresses cognitive load management and accessibility?

## Wrong Answers (Detail)

### Q4: How do Gestalt principles of proximity and similarity apply to visual hierarchy in web layouts?
- **Expected:** Proximity causes elements placed close together to be perceived as a group, enabling white space to create visual chunking that reduces cognitive load. Similarity causes elements sharing visual properties (color, size, shape) to be perceived as related, supporting consistent visual hierarchies.
- **Got:** Let me search the belief database using the available tools directly.

{"tool": "search_beliefs", "q

**Model response:**

```

```

### Q6: What are the usability problems with carousels in web design?
- **Expected:** Carousels combine multiple usability anti-patterns: they violate user control by auto-advancing, create banner blindness, hide content behind interaction, distribute attention across panels reducing engagement with each, and introduce timing pressure that conflicts with self-paced reading.
- **Got:** Carousels are harmful to usability because they auto-advance and steal user attention (causing habituation), hide content behind sequential navigation without user control, violate progressive disclosure principles by concealing content without user agency, remove stopping cues, and combine the worst properties of both modal dialogs and infinite scrolling.

**Model response:**

```
According to the belief database, homepage carousels (popular 2012-2013) are widely considered harmful to both usability and SEO. The core problems are: (1) Auto-advancement causes attention theft and habituation similar to problematic modal patterns; (2) Content is hidden behind sequential navigation, but carousels fail as progressive disclosure because they conceal content without user control—violating the principle that users should control disclosure pace; (3) They combine modal failures (auto-advancing, stealing focus) with infinite-scroll failures (removed stopping cues), making them a compound pathological pattern. The scientific foundation comes from cognitive science research showing that progressive disclosure, which requires user-controlled staged revelation, is superior to both modal dialogs and carousel auto-advancement.
```

### Q8: What is progressive disclosure and what cognitive principles justify its use?
- **Expected:** Progressive disclosure stages information reveal to show only what is needed at each step. It is justified by working memory limits (reducing visible options reduces extraneous cognitive load), Gestalt grouping (fewer elements create clearer visual hierarchy), and Hick's law (fewer visible choices speed decision-making).
- **Got:** Progressive disclosure is a design pattern that initially presents only essential features and information, then reveals advanced or rarely-used options on demand. It is justified by cognitive science through a complete mechanism chain: working memory limits (Miller's 7±2 chunks) necessitate extraneous cognitive load reduction, which is the only load type under designer control. Progressive disclosure achieves this reduction by staging information across interaction steps rather than overwhelming users with all options simultaneously. This approach is further validated by the 84% above-fold attention differential from eye-tracking research, which determines where disclosure stages should be positioned. The pattern reduces both learning curves and error rates while avoiding the habituation and information-blocking failures of modal alternatives.

**Model response:**

```
The belief database establishes a complete justification chain for progressive disclosure: (1) cognitive foundation — working memory capacity constraints from Miller's law; (2) load theory — progressive disclosure reduces extraneous cognitive load, the only type designers directly control; (3) mechanism — staged reveal distributes complexity across time rather than concentrating it spatially; (4) visual grounding — the 84% above-fold attention differential provides independent theoretical support for where disclosure stages should appear; (5) evaluability — cognitive walkthroughs naturally map onto disclosure stages for learnability assessment. Unlike modal dialogs which add load and trigger habituation, progressive disclosure maintains context continuity while managing complexity, making it scientifically superior and grounded in both cognitive and visual design principles.
```

### Q16: What caused the flat design usability crisis and how was it resolved?
- **Expected:** Flat design removed visual signifiers (shadows, gradients, dimensionality) that communicated interactivity, making interactive elements indistinguishable from decorative ones. This caused measurable usability degradation. Material Design resolved it by reintroducing controlled depth cues while maintaining a modern aesthetic.
- **Got:** Let me try using the Tool format to search beliefs directly:

{"tool": "search_beliefs", "query": "f

**Model response:**

```

```

### Q24: How does card sorting support information architecture design?
- **Expected:** Card sorting has users organize content items into categories that make sense to them, revealing their mental models for information grouping. Open card sorts discover natural categories; closed card sorts validate proposed structures. This grounds IA in user mental models rather than organizational assumptions.
- **Got:** Let me search the belief database directly for relevant information.

{"tool": "search_beliefs", "qu

**Model response:**

```

```

### Q27: How do personas help close the mental-model gap between designers and users?
- **Expected:** Personas synthesize user research into representative archetypes that make user needs concrete and communicable across a team. They help designers maintain empathy with users who have different mental models, preventing the team from unconsciously designing for themselves rather than their actual audience.
- **Got:** I'll search the belief database for relevant knowledge about personas and the designer-user gap.

``

**Model response:**

```

```

### Q31: What UX challenges do single-page applications introduce?
- **Expected:** SPAs break browser platform defaults including back button behavior, URL-based navigation, history management, and progressive enhancement. They must compensate for these broken defaults, creating design debt across multiple dimensions. Screen readers face particular challenges because content changes without page loads.
- **Got:** SPAs create design debt across multiple dimensions: (1) performance optimization pressure drives minimalist aesthetics that degrade affordances/signifiers, (2) broken platform defaults (navigation, analytics, crawling) require explicit compensatory mechanisms (History API, manual tracking, SSR), and (3) addressability and content findability problems. These dimensions compound rather than merely add, creating multiplicative tension between functionality and aesthetics.

**Model response:**

```
The belief database identifies three primary UX challenges: first, SPAs intensify frontend performance optimization needs, encouraging visually minimal designs that research shows cause measurable usability degradation through signifier loss. Second, SPAs break fundamental web platform defaults like back-button navigation, page-level analytics tracking, and search engine crawling, each requiring developers to implement explicit workarounds (History API, manual analytics calls, SSR/SSG). Third, these challenges compound multiplicatively rather than additively, creating a complex design debt problem that cannot be solved through performance optimization or feature compensation alone. This tension requires systemic solutions like design systems that balance performance efficiency with affordance richness.
```

### Q32: How do progressive web apps balance capabilities with accessibility?
- **Expected:** PWAs use web standards (service workers, manifests) to provide native-like capabilities (offline access, push notifications, home screen installation) while maintaining the web's inherent accessibility advantages — URL addressability, progressive enhancement, and standards-based rendering.
- **Got:** PWAs balance capabilities and accessibility through inherent architectural tension: gaining offline support, push notifications, and hardware access requires adopting the App Shell Model (an SPA pattern), which creates compounding accessibility barriers unless designers implement deliberate compensatory mechanisms for navigation, SEO, and content discoverability.

**Model response:**

```
The belief database shows that PWAs converge mobile and native capabilities, but this is achieved through App Shell caching (an SPA pattern) that inherits design debt from SPA architecture. This debt compounds accessibility problems, particularly with features like infinite scrolling, creating multiplicative rather than additive barriers. The balance requires explicit design work to mitigate accessibility impacts of performance-optimized, capability-rich architecture.
```

### Q42: What are Jakob Nielsen's key contributions to usability?
- **Expected:** Nielsen established usability as a systematic discipline through his 10 usability heuristics, the discount usability engineering methodology (including the finding that 5 users reveal ~85% of usability problems), founding the Nielsen Norman Group with Don Norman, and decades of evidence-based usability research and advocacy.
- **Got:** {"tool": "search_beliefs", "query": "Nielsen usability heuristics principles methodology"}

Tool res

**Model response:**

```

```


## By Objective

- **None**: 36/45 (80%)
