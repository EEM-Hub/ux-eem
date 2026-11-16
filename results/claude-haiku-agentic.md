# Exam Results: ux-design.md

**Date:** 2026-06-23 11:18
**Model:** claude:haiku
**Score:** 37/45 (82%)

## Per-Question Results

- **Q1**: CORRECT — What is Fitts's law and how does it apply to web UI design?
- **Q2**: CORRECT — How does Hick's law relate to information architecture and navigation design?
- **Q3**: CORRECT — Explain the expertise reversal effect and its implications for progressive disclosure in web interfaces.
- **Q4**: CORRECT — How do Gestalt principles of proximity and similarity apply to visual hierarchy in web layouts?
- **Q5**: CORRECT — What is cognitive load theory and how do its three types map to UI design decisions?
- **Q6**: CORRECT — What are the usability problems with carousels in web design?
- **Q7**: CORRECT — When is infinite scrolling appropriate versus pagination?
- **Q8**: WRONG — What is progressive disclosure and what cognitive principles justify its use?
  - Expected: Progressive disclosure stages information reveal to show only what is needed at each step. It is justified by working memory limits (reducing visible options reduces extraneous cognitive load), Gestalt grouping (fewer elements create clearer visual hierarchy), and Hick's law (fewer visible choices speed decision-making).
  - Got: The reasons tool is not available in this context. Let me search the belief database directly using
- **Q9**: WRONG — What are the usability concerns with modal windows?
  - Expected: Modal windows block interaction with the underlying page, disrupting user flow and potentially causing loss of context. They can trap keyboard focus creating accessibility problems, they interrupt task completion, and on mobile they often have dismiss targets that are too small to tap reliably.
  - Got: Modal dialogs fail across three independent dimensions: cognitive (habituation causes dismissal without reading, and covering needed content creates information blocking), security (focus-stealing intercepts input intended for other applications), and load management (split-attention from separating related information across modal and parent window)
- **Q10**: CORRECT — Why is the hamburger menu controversial in UX design?
- **Q11**: WRONG — What are the four WCAG principles (POUR) and what does each require?
  - Expected: Perceivable (content must be presentable in ways users can perceive), Operable (UI components must be operable by all users), Understandable (content and UI must be understandable), Robust (content must be interpretable by assistive technologies). Together they cover the full spectrum of accessibility requirements.
  - Got: The four WCAG principles (POUR) are: (1) Perceivable — information and UI components must be presentable to users in ways they can perceive, including text alternatives, adaptable content, and distinguishable presentations; (2) Operable — UI components and navigation must be operable through keyboard access, sufficient time, seizure prevention, and navigability; (3) Understandable — information and UI operation must be understandable through readable text, predictable behavior, and input assistance; (4) Robust — content must be interpretable reliably by diverse user agents and assistive technologies through valid code and accessibility compatibility.
- **Q12**: CORRECT — How does WAI-ARIA complement semantic HTML for web accessibility?
- **Q13**: CORRECT — What is the most common cause of screen reader inaccessibility?
- **Q14**: CORRECT — How does progressive enhancement serve as an accessibility strategy?
- **Q15**: CORRECT — What does the WebAIM survey data show about the accessibility training gap?
- **Q16**: WRONG — What caused the flat design usability crisis and how was it resolved?
  - Expected: Flat design removed visual signifiers (shadows, gradients, dimensionality) that communicated interactivity, making interactive elements indistinguishable from decorative ones. This caused measurable usability degradation. Material Design resolved it by reintroducing controlled depth cues while maintaining a modern aesthetic.
  - Got: I'll search the belief database for information about flat design and usability issues.

```json
{"t
- **Q17**: CORRECT — How do grid systems support cognitive load management in web layouts?
- **Q18**: CORRECT — What role does white space play in visual hierarchy according to Gestalt principles?
- **Q19**: CORRECT — How does responsive web design differ from adaptive design?
- **Q20**: WRONG — What is the relationship between color theory and accessibility in web design?
  - Expected: Color theory provides rules for contrast, depth perception (warm colors advance, cool recede), and hue relationships that directly serve accessibility requirements. WCAG contrast ratios translate these perceptual principles into enforceable thresholds. However, color harmony has no universal formula, limiting what can be systematically enforced.
  - Got: Color theory provides the specific perceptual science and enforceable implementation rules that complete design systems' accessibility encoding. It bridges WCAG accessibility standards (contrast ratios, minimum thresholds) and practical design implementation through three key mechanisms: warm-advance/cool-recede spatial perception for visual hierarchy and depth signaling, hue-shift awareness for accessible color darkening in dark themes, and contrast ratio enforcement through design tokens. Together, these color-theory-informed rules ensure that the visual cognition chain (Gestalt chunking → visual hierarchy → working memory → signifier requirements) is both perceptually sound and systematically accessible across an entire product, making accessibility compliance a built-in property of the design system rather than an afterthought.
- **Q21**: CORRECT — What is the difference between heuristic evaluation and cognitive walkthrough?
- **Q22**: CORRECT — How does A/B testing complement qualitative usability testing?
- **Q23**: CORRECT — What is Simpson's paradox and why does it matter for A/B test analysis?
- **Q24**: CORRECT — How does card sorting support information architecture design?
- **Q25**: CORRECT — What does eye tracking reveal about user attention and the concept of the fold?
- **Q26**: CORRECT — What is user-centered design and what are its core principles?
- **Q27**: CORRECT — How do personas help close the mental-model gap between designers and users?
- **Q28**: CORRECT — What role do wireframes play in the UX design process?
- **Q29**: CORRECT — What is a design system and how does it differ from a style guide?
- **Q30**: CORRECT — How does design thinking's abductive reasoning approach apply to wicked problems in UX?
- **Q31**: CORRECT — What UX challenges do single-page applications introduce?
- **Q32**: CORRECT — How do progressive web apps balance capabilities with accessibility?
- **Q33**: WRONG — What is the relationship between web performance and user experience?
  - Expected: Web performance directly affects user perception and engagement. Slow load times increase bounce rates, reduce conversions, and degrade perceived quality. Performance optimization (compression, caching, lazy loading) serves UX by reducing the time between user intent and interface response.
  - Got: Web performance directly impacts user experience by affecting efficiency (resources/time expended) and satisfaction (user acceptance). Faster load times, responsive interactions (measured by Core Web Vitals), and optimized rendering reduce cognitive friction and improve perceived usability, making performance a measurable component of the ISO 9241 usability framework rather than a separate concern.
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
  - Got: Jakob Nielsen's key contributions to usability include: (1) the 10 Usability Heuristics developed with Rolf Molich (1989–1990, finalized 1994 and 2005), which identify core principles like visibility of system status, user control, error prevention, and aesthetic design; (2) heuristic evaluation as a systematic expert inspection methodology; (3) the 5-user testing principle; and (4) co-founding Nielsen Norman Group (1998) with Donald Norman to institutionalize empirical evaluation methodology within a comprehensive design theory framework.
- **Q43**: CORRECT — How did Three Mile Island influence HCI and usability thinking?
- **Q44**: CORRECT — You are reviewing a web application that uses infinite scrolling, hamburger navigation, and auto-playing carousels. What specific UX concerns would you raise?
- **Q45**: WRONG — How would you evaluate whether a design system adequately addresses cognitive load management and accessibility?
  - Expected: Check cognitive load: does it enforce minimum target sizes (Fitts's law), consistent spacing (Gestalt proximity), progressive disclosure patterns, and information hierarchy? Check accessibility: does it encode WCAG contrast ratios in design tokens, provide ARIA patterns in components, support keyboard navigation, and maintain semantic HTML? The gap is usually at the API compliance layer — the design system may specify correctly but applications may implement incorrectly.
  - Got: Conduct comprehensive user testing with cognitive load measurement (task completion time, error rates, mental effort scales), perform accessibility audits against WCAG standards, evaluate information hierarchy and visual clarity through design review, test with assistive technology users, and gather feedback on component consistency and predictability

## Wrong Answers (Detail)

### Q8: What is progressive disclosure and what cognitive principles justify its use?
- **Expected:** Progressive disclosure stages information reveal to show only what is needed at each step. It is justified by working memory limits (reducing visible options reduces extraneous cognitive load), Gestalt grouping (fewer elements create clearer visual hierarchy), and Hick's law (fewer visible choices speed decision-making).
- **Got:** The reasons tool is not available in this context. Let me search the belief database directly using

**Model response:**

```

```

### Q9: What are the usability concerns with modal windows?
- **Expected:** Modal windows block interaction with the underlying page, disrupting user flow and potentially causing loss of context. They can trap keyboard focus creating accessibility problems, they interrupt task completion, and on mobile they often have dismiss targets that are too small to tap reliably.
- **Got:** Modal dialogs fail across three independent dimensions: cognitive (habituation causes dismissal without reading, and covering needed content creates information blocking), security (focus-stealing intercepts input intended for other applications), and load management (split-attention from separating related information across modal and parent window)

**Model response:**

```
The belief database establishes that modal windows are fundamentally problematic not as a single fixable issue but as a pattern with pervasive, structurally independent failure modes. Cognitively, users habituate to modal interruptions and dismiss them without reading, while modals often cover the very information needed to complete the modal's task. Securitionally, modals can steal focus from other applications. From a load-management perspective, modals force users to split attention between the modal and parent window, violating principles of spatial integration and creating unnecessary cognitive burden.
```

### Q11: What are the four WCAG principles (POUR) and what does each require?
- **Expected:** Perceivable (content must be presentable in ways users can perceive), Operable (UI components must be operable by all users), Understandable (content and UI must be understandable), Robust (content must be interpretable by assistive technologies). Together they cover the full spectrum of accessibility requirements.
- **Got:** The four WCAG principles (POUR) are: (1) Perceivable — information and UI components must be presentable to users in ways they can perceive, including text alternatives, adaptable content, and distinguishable presentations; (2) Operable — UI components and navigation must be operable through keyboard access, sufficient time, seizure prevention, and navigability; (3) Understandable — information and UI operation must be understandable through readable text, predictable behavior, and input assistance; (4) Robust — content must be interpretable reliably by diverse user agents and assistive technologies through valid code and accessibility compatibility.

**Model response:**

```
These four principles form the foundation of WCAG accessibility guidelines and organize all success criteria by concern. They address the core needs for digital content to be accessible: users must be able to perceive it, interact with it, understand it, and access it with various technologies. Each principle encompasses multiple guidelines and success criteria at different conformance levels (A, AA, AAA) that provide specific, measurable requirements for achieving that principle's goal.
```

### Q16: What caused the flat design usability crisis and how was it resolved?
- **Expected:** Flat design removed visual signifiers (shadows, gradients, dimensionality) that communicated interactivity, making interactive elements indistinguishable from decorative ones. This caused measurable usability degradation. Material Design resolved it by reintroducing controlled depth cues while maintaining a modern aesthetic.
- **Got:** I'll search the belief database for information about flat design and usability issues.

```json
{"t

**Model response:**

```

```

### Q20: What is the relationship between color theory and accessibility in web design?
- **Expected:** Color theory provides rules for contrast, depth perception (warm colors advance, cool recede), and hue relationships that directly serve accessibility requirements. WCAG contrast ratios translate these perceptual principles into enforceable thresholds. However, color harmony has no universal formula, limiting what can be systematically enforced.
- **Got:** Color theory provides the specific perceptual science and enforceable implementation rules that complete design systems' accessibility encoding. It bridges WCAG accessibility standards (contrast ratios, minimum thresholds) and practical design implementation through three key mechanisms: warm-advance/cool-recede spatial perception for visual hierarchy and depth signaling, hue-shift awareness for accessible color darkening in dark themes, and contrast ratio enforcement through design tokens. Together, these color-theory-informed rules ensure that the visual cognition chain (Gestalt chunking → visual hierarchy → working memory → signifier requirements) is both perceptually sound and systematically accessible across an entire product, making accessibility compliance a built-in property of the design system rather than an afterthought.

**Model response:**

```
The belief database establishes that color theory and accessibility are not separate concerns but interdependent: color theory's perceptual science (warm/cool spatial perception, hue-shift effects) fills the gap between abstract accessibility frameworks and concrete implementation, while WCAG provides the minimum contrast thresholds that color theory operationalizes. Design tokens then enforce these color rules systematically. This creates a complete chain from perceptual science → accessibility standards → enforceable design-system rules, making color theory essential to translating accessibility requirements into practical, visually-coherent interfaces.
```

### Q33: What is the relationship between web performance and user experience?
- **Expected:** Web performance directly affects user perception and engagement. Slow load times increase bounce rates, reduce conversions, and degrade perceived quality. Performance optimization (compression, caching, lazy loading) serves UX by reducing the time between user intent and interface response.
- **Got:** Web performance directly impacts user experience by affecting efficiency (resources/time expended) and satisfaction (user acceptance). Faster load times, responsive interactions (measured by Core Web Vitals), and optimized rendering reduce cognitive friction and improve perceived usability, making performance a measurable component of the ISO 9241 usability framework rather than a separate concern.

**Model response:**

```
The belief database establishes that ISO 9241 defines usability (core to UX) through three factors: effectiveness, efficiency, and satisfaction. Web performance optimization—particularly frontend-focused techniques and Core Web Vitals metrics—directly improves efficiency (reducing time/resources) and indirectly improves satisfaction through smoother interactions. Design systems encode cognitive constraints that align performance improvements with load management mechanisms, showing that performance and UX quality are intrinsically connected through the field's established quality frameworks rather than being independent concerns.
```

### Q42: What are Jakob Nielsen's key contributions to usability?
- **Expected:** Nielsen established usability as a systematic discipline through his 10 usability heuristics, the discount usability engineering methodology (including the finding that 5 users reveal ~85% of usability problems), founding the Nielsen Norman Group with Don Norman, and decades of evidence-based usability research and advocacy.
- **Got:** Jakob Nielsen's key contributions to usability include: (1) the 10 Usability Heuristics developed with Rolf Molich (1989–1990, finalized 1994 and 2005), which identify core principles like visibility of system status, user control, error prevention, and aesthetic design; (2) heuristic evaluation as a systematic expert inspection methodology; (3) the 5-user testing principle; and (4) co-founding Nielsen Norman Group (1998) with Donald Norman to institutionalize empirical evaluation methodology within a comprehensive design theory framework.

**Model response:**

```
Nielsen is recognized as a pioneer of empirical usability evaluation methodology. His 10 heuristics represent one of the field's most widely adopted design frameworks, developed through independent derivation that converged with Shneiderman's 8 Golden Rules (1986) and ISO 9241 standards—establishing robustly validated interaction principles. Beyond specific heuristics, Nielsen contributed systematic evaluation methods (heuristic evaluation and iterative user testing) that became foundational practices in UX design. His institutional partnership with Norman at Nielsen Norman Group merged evaluation methodology with design theory, making usability evaluation an operationalized discipline rather than abstract research. Additionally, Nielsen's critique of flat design (2013) demonstrated the persistence of his empirical approach—identifying measurable usability degradation when design trends violate foundational principles like signifier visibility.
```

### Q45: How would you evaluate whether a design system adequately addresses cognitive load management and accessibility?
- **Expected:** Check cognitive load: does it enforce minimum target sizes (Fitts's law), consistent spacing (Gestalt proximity), progressive disclosure patterns, and information hierarchy? Check accessibility: does it encode WCAG contrast ratios in design tokens, provide ARIA patterns in components, support keyboard navigation, and maintain semantic HTML? The gap is usually at the API compliance layer — the design system may specify correctly but applications may implement incorrectly.
- **Got:** Conduct comprehensive user testing with cognitive load measurement (task completion time, error rates, mental effort scales), perform accessibility audits against WCAG standards, evaluate information hierarchy and visual clarity through design review, test with assistive technology users, and gather feedback on component consistency and predictability

**Model response:**

```
A robust design system evaluation requires multiple dimensions: quantitative metrics (task performance, error rates, time-on-task) measure cognitive load effectiveness, while structured accessibility testing (WCAG audits, screen reader testing, keyboard navigation) ensures inclusive design. Qualitative methods like cognitive walkthrough analysis, design consistency audits, and user interviews with diverse populations—including people with disabilities—validate whether the system genuinely reduces unnecessary complexity and supports varied user needs. The evaluation should test both individual components in isolation and their integration within realistic workflows, as cognitive load emerges from cumulative interface decisions and component interactions.
```


## By Objective

- **None**: 37/45 (82%)
