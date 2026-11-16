# Exam Results: ux-design.md

**Date:** 2026-06-22 15:17
**Model:** claude:sonnet
**Score:** 36/45 (80%)

## Per-Question Results

- **Q1**: CORRECT — What is Fitts's law and how does it apply to web UI design?
- **Q2**: CORRECT — How does Hick's law relate to information architecture and navigation design?
- **Q3**: CORRECT — Explain the expertise reversal effect and its implications for progressive disclosure in web interfaces.
- **Q4**: CORRECT — How do Gestalt principles of proximity and similarity apply to visual hierarchy in web layouts?
- **Q5**: CORRECT — What is cognitive load theory and how do its three types map to UI design decisions?
- **Q6**: CORRECT — What are the usability problems with carousels in web design?
- **Q7**: WRONG — When is infinite scrolling appropriate versus pagination?
  - Expected: Infinite scrolling suits discovery-oriented tasks (social feeds, image browsing) where users don't need to reach specific content. Pagination is better for goal-directed tasks (search results, product listings) where users need to reference specific positions, compare items, or return to a known location.
  - Got: Pagination is generally preferred; infinite scroll should be avoided or used only with hybrid controls
- **Q8**: WRONG — What is progressive disclosure and what cognitive principles justify its use?
  - Expected: Progressive disclosure stages information reveal to show only what is needed at each step. It is justified by working memory limits (reducing visible options reduces extraneous cognitive load), Gestalt grouping (fewer elements create clearer visual hierarchy), and Hick's law (fewer visible choices speed decision-making).
  - Got: Progressive disclosure is a design technique that reduces complexity by initially presenting only essential features and information, then revealing advanced or rarely-used options on demand via secondary screens or expandable sections.
- **Q9**: WRONG — What are the usability concerns with modal windows?
  - Expected: Modal windows block interaction with the underlying page, disrupting user flow and potentially causing loss of context. They can trap keyboard focus creating accessibility problems, they interrupt task completion, and on mobile they often have dismiss targets that are too small to tap reliably.
  - Got: Modal windows fail across three independent dimensions: cognitive (habituation causes users to dismiss them without reading, and they cover information needed to complete their own tasks), security (focus-stealing can intercept input intended for other programs), and load management (split-attention effect from separating related information across modal and parent windows). Additionally, modals can block clipboard operations users need to complete the modal's input fields, creating a self-defeating cycle where the pattern interferes with its own purpose.
- **Q10**: CORRECT — Why is the hamburger menu controversial in UX design?
- **Q11**: WRONG — What are the four WCAG principles (POUR) and what does each require?
  - Expected: Perceivable (content must be presentable in ways users can perceive), Operable (UI components must be operable by all users), Understandable (content and UI must be understandable), Robust (content must be interpretable by assistive technologies). Together they cover the full spectrum of accessibility requirements.
  - Got: Perceivable, Operable, Understandable, and Robust
- **Q12**: CORRECT — How does WAI-ARIA complement semantic HTML for web accessibility?
- **Q13**: CORRECT — What is the most common cause of screen reader inaccessibility?
- **Q14**: CORRECT — How does progressive enhancement serve as an accessibility strategy?
- **Q15**: CORRECT — What does the WebAIM survey data show about the accessibility training gap?
- **Q16**: CORRECT — What caused the flat design usability crisis and how was it resolved?
- **Q17**: CORRECT — How do grid systems support cognitive load management in web layouts?
- **Q18**: CORRECT — What role does white space play in visual hierarchy according to Gestalt principles?
- **Q19**: CORRECT — How does responsive web design differ from adaptive design?
- **Q20**: WRONG — What is the relationship between color theory and accessibility in web design?
  - Expected: Color theory provides rules for contrast, depth perception (warm colors advance, cool recede), and hue relationships that directly serve accessibility requirements. WCAG contrast ratios translate these perceptual principles into enforceable thresholds. However, color harmony has no universal formula, limiting what can be systematically enforced.
  - Got: Color theory and accessibility are integrated through WCAG contrast requirements and perceptual science
- **Q21**: CORRECT — What is the difference between heuristic evaluation and cognitive walkthrough?
- **Q22**: CORRECT — How does A/B testing complement qualitative usability testing?
- **Q23**: CORRECT — What is Simpson's paradox and why does it matter for A/B test analysis?
- **Q24**: CORRECT — How does card sorting support information architecture design?
- **Q25**: WRONG — What does eye tracking reveal about user attention and the concept of the fold?
  - Expected: Eye tracking shows significantly more fixation on above-fold content, with studies suggesting an 84% attention differential. However, covert attention (processing without fixation) means fixation maps may overstate the difference, and there is no universal pixel definition for the fold across devices, limiting prescriptive application.
  - Got: Eye tracking reveals an 84% attention differential between above-fold and below-fold content, with fixation data showing that content below the fold receives fewer or no fixations. This validates the finding that 77% of visitors do not scroll below the fold.
- **Q26**: CORRECT — What is user-centered design and what are its core principles?
- **Q27**: CORRECT — How do personas help close the mental-model gap between designers and users?
- **Q28**: CORRECT — What role do wireframes play in the UX design process?
- **Q29**: CORRECT — What is a design system and how does it differ from a style guide?
- **Q30**: CORRECT — How does design thinking's abductive reasoning approach apply to wicked problems in UX?
- **Q31**: CORRECT — What UX challenges do single-page applications introduce?
- **Q32**: WRONG — How do progressive web apps balance capabilities with accessibility?
  - Expected: PWAs use web standards (service workers, manifests) to provide native-like capabilities (offline access, push notifications, home screen installation) while maintaining the web's inherent accessibility advantages — URL addressability, progressive enhancement, and standards-based rendering.
  - Got: PWAs create architectural tension with accessibility while simultaneously improving it through size advantages; progressive enhancement can reconcile both.
- **Q33**: WRONG — What is the relationship between web performance and user experience?
  - Expected: Web performance directly affects user perception and engagement. Slow load times increase bounce rates, reduce conversions, and degrade perceived quality. Performance optimization (compression, caching, lazy loading) serves UX by reducing the time between user intent and interface response.
  - Got: Web performance and UX have a complex, tension-filled relationship requiring dual remediation
- **Q34**: CORRECT — How does above the fold apply in responsive web design?
- **Q35**: CORRECT — What is the dual quality mandate in modern web architecture?
- **Q36**: CORRECT — How do design systems encode cognitive constraints like Fitts's law and Gestalt principles?
- **Q37**: CORRECT — What is the role of design tokens in enforcing visual standards?
- **Q38**: CORRECT — How do design systems relate to ISO 9241 usability standards?
- **Q39**: CORRECT — What historical precedent exists for design system backlash?
- **Q40**: CORRECT — How does Material Design address the flat design signifier problem?
- **Q41**: CORRECT — What is Don Norman's affordance-signifier framework and why is it foundational?
- **Q42**: CORRECT — What are Jakob Nielsen's key contributions to usability?
- **Q43**: CORRECT — How did Three Mile Island influence HCI and usability thinking?
- **Q44**: CORRECT — You are reviewing a web application that uses infinite scrolling, hamburger navigation, and auto-playing carousels. What specific UX concerns would you raise?
- **Q45**: WRONG — How would you evaluate whether a design system adequately addresses cognitive load management and accessibility?
  - Expected: Check cognitive load: does it enforce minimum target sizes (Fitts's law), consistent spacing (Gestalt proximity), progressive disclosure patterns, and information hierarchy? Check accessibility: does it encode WCAG contrast ratios in design tokens, provide ARIA patterns in components, support keyboard navigation, and maintain semantic HTML? The gap is usually at the API compliance layer — the design system may specify correctly but applications may implement incorrectly.
  - Got: Evaluate through combined expert inspection and empirical testing across multiple dimensions

## Wrong Answers (Detail)

### Q7: When is infinite scrolling appropriate versus pagination?
- **Expected:** Infinite scrolling suits discovery-oriented tasks (social feeds, image browsing) where users don't need to reach specific content. Pagination is better for goal-directed tasks (search results, product listings) where users need to reference specific positions, compare items, or return to a known location.
- **Got:** Pagination is generally preferred; infinite scroll should be avoided or used only with hybrid controls

**Model response:**

```
```json
{"answer": "Pagination is generally preferred; infinite scroll should be avoided or used only with hybrid controls", "explanation": "Based on the knowledge provided, infinite scrolling creates multiple serious problems: it produces accessibility barriers (users cannot reach page footers, bookmark positions, or navigate effectively with keyboards and screen readers), removes natural stopping cues that contribute to compulsive usage patterns, and loses page addressability and indexability. Pagination supports skip-navigation, permanent deep links, better accessibility (works without JavaScript), and faster initial page loads for large datasets. When infinite scroll patterns must be used, hybrid variations with 'load more' buttons or integrated pagination indicators can restore some user control and orientation. The evidence strongly favors pagination for most use cases, with infinite scroll reserved only for specific contexts where seamless browsing is critical and mitigated by accessibility-preserving hybrid controls."}
```
```

### Q8: What is progressive disclosure and what cognitive principles justify its use?
- **Expected:** Progressive disclosure stages information reveal to show only what is needed at each step. It is justified by working memory limits (reducing visible options reduces extraneous cognitive load), Gestalt grouping (fewer elements create clearer visual hierarchy), and Hick's law (fewer visible choices speed decision-making).
- **Got:** Progressive disclosure is a design technique that reduces complexity by initially presenting only essential features and information, then revealing advanced or rarely-used options on demand via secondary screens or expandable sections.

**Model response:**

```
```json
{"answer": "Progressive disclosure is a design technique that reduces complexity by initially presenting only essential features and information, then revealing advanced or rarely-used options on demand via secondary screens or expandable sections.", "explanation": "Progressive disclosure is justified by several converging cognitive principles: it addresses working memory constraints (Miller's 7±2 chunks) by reducing extraneous cognitive load — the only load type under the designer's direct control. By hiding secondary content, it prevents cognitive overload while also leveraging the Von Restorff isolation effect, which makes the isolated primary content both more noticeable and more memorable. The technique also relates to Hick's law by reducing the number of visible choices, thereby decreasing decision time. This creates a complete mechanism chain from cognitive theory (working memory limits) through load taxonomy (extraneous load reduction) to design technique, resulting in easier learning, fewer errors, and better overall comprehension compared to presenting all options simultaneously."}
```
```

### Q9: What are the usability concerns with modal windows?
- **Expected:** Modal windows block interaction with the underlying page, disrupting user flow and potentially causing loss of context. They can trap keyboard focus creating accessibility problems, they interrupt task completion, and on mobile they often have dismiss targets that are too small to tap reliably.
- **Got:** Modal windows fail across three independent dimensions: cognitive (habituation causes users to dismiss them without reading, and they cover information needed to complete their own tasks), security (focus-stealing can intercept input intended for other programs), and load management (split-attention effect from separating related information across modal and parent windows). Additionally, modals can block clipboard operations users need to complete the modal's input fields, creating a self-defeating cycle where the pattern interferes with its own purpose.

**Model response:**

```
```json
{"answer": "Modal windows fail across three independent dimensions: cognitive (habituation causes users to dismiss them without reading, and they cover information needed to complete their own tasks), security (focus-stealing can intercept input intended for other programs), and load management (split-attention effect from separating related information across modal and parent windows). Additionally, modals can block clipboard operations users need to complete the modal's input fields, creating a self-defeating cycle where the pattern interferes with its own purpose.", "explanation": "According to the beliefs, modal dialogs are among the most thoroughly discredited UI patterns because they create pervasive, structurally independent failure modes. The cognitive dimension includes both habituation (users automatically dismiss warnings without reading them) and information blocking (modals cover content users need to see). The security dimension involves focus-stealing risks where modals intercept input meant for other applications. The load management dimension relates to the split-attention effect, where users must mentally integrate information separated between the modal and parent window. Usability experts recommend undo-based progressive disclosure as the superior alternative, avoiding modal warnings entirely."}
```
```

### Q11: What are the four WCAG principles (POUR) and what does each require?
- **Expected:** Perceivable (content must be presentable in ways users can perceive), Operable (UI components must be operable by all users), Understandable (content and UI must be understandable), Robust (content must be interpretable by assistive technologies). Together they cover the full spectrum of accessibility requirements.
- **Got:** Perceivable, Operable, Understandable, and Robust

**Model response:**

```
```json
{"answer": "Perceivable, Operable, Understandable, and Robust", "explanation": "According to my knowledge, WCAG's four accessibility principles are Perceivable, Operable, Understandable, and Robust (POUR). These principles organize all WCAG success criteria by concern within WCAG's conformance architecture. However, my current knowledge does not include the specific requirements that each principle mandates—only that they exist as the organizing framework for WCAG's success criteria and that they form part of the backwards-compatible, principle-organized, tiered conformance system."}
```
```

### Q20: What is the relationship between color theory and accessibility in web design?
- **Expected:** Color theory provides rules for contrast, depth perception (warm colors advance, cool recede), and hue relationships that directly serve accessibility requirements. WCAG contrast ratios translate these perceptual principles into enforceable thresholds. However, color harmony has no universal formula, limiting what can be systematically enforced.
- **Got:** Color theory and accessibility are integrated through WCAG contrast requirements and perceptual science

**Model response:**

```
```json
{"answer": "Color theory and accessibility are integrated through WCAG contrast requirements and perceptual science", "explanation": "Color theory's perceptual science (warm-advance/cool-recede spatial perception, hue-shift effects under darkening) and WCAG contrast enforcement form a complete chain from perceptual science through accessibility standard to systematic implementation. WCAG specifies minimum contrast ratios (4.5:1 for AA, 7:1 for AAA) as measurable accessibility thresholds, while color theory provides the science-backed rules for what these ratios must achieve visually—such as using complementary-based darkening to avoid hue shifts that distort intended hierarchy. Design tokens operationalize this relationship by systematically encoding both WCAG contrast requirements and color theory principles across entire applications. Additionally, accessibility mandates that color not be the sole differentiator (e.g., links require underlines beyond color alone) to accommodate color-blind users, demonstrating that effective accessible design requires both quantitative contrast compliance and qualitative understanding of color perception limitations."}
```
```

### Q25: What does eye tracking reveal about user attention and the concept of the fold?
- **Expected:** Eye tracking shows significantly more fixation on above-fold content, with studies suggesting an 84% attention differential. However, covert attention (processing without fixation) means fixation maps may overstate the difference, and there is no universal pixel definition for the fold across devices, limiting prescriptive application.
- **Got:** Eye tracking reveals an 84% attention differential between above-fold and below-fold content, with fixation data showing that content below the fold receives fewer or no fixations. This validates the finding that 77% of visitors do not scroll below the fold.

**Model response:**

```
```json
{
  "answer": "Eye tracking reveals an 84% attention differential between above-fold and below-fold content, with fixation data showing that content below the fold receives fewer or no fixations. This validates the finding that 77% of visitors do not scroll below the fold.",
  "explanation": "Eye tracking provides empirical evidence for fold-related behavior through fixation-based information processing. Since most visual information is processed during fixations (brief pauses on specific points), eye tracking can measure where users actually look. Research shows an 84% attention differential between above-fold and below-fold content, and fixation data helps explain why 77% of website visitors do not scroll below the fold—content below the fold simply receives fewer fixations. Eye tracking serves as the field's unified empirical validation instrument at macro-level layout decisions, validating these fold attention patterns. However, it's important to note that fixation maps show where the eye was, not necessarily where attention was directed (due to covert attention), and heat maps show fixation frequency rather than attention or comprehension directly."
}
```
```

### Q32: How do progressive web apps balance capabilities with accessibility?
- **Expected:** PWAs use web standards (service workers, manifests) to provide native-like capabilities (offline access, push notifications, home screen installation) while maintaining the web's inherent accessibility advantages — URL addressability, progressive enhancement, and standards-based rendering.
- **Got:** PWAs create architectural tension with accessibility while simultaneously improving it through size advantages; progressive enhancement can reconcile both.

**Model response:**

```
```json
{
  "answer": "PWAs create architectural tension with accessibility while simultaneously improving it through size advantages; progressive enhancement can reconcile both.",
  "explanation": "PWAs inherit SPA design debt including screen reader accessibility challenges because their JavaScript-dependent compensatory mechanisms (History API, client-side routing) conflict with the semantic HTML stack that screen readers require. However, PWAs also dramatically improve accessibility through their size advantage—consuming only 1-3% of native app size—which directly benefits bandwidth and storage-constrained users, particularly in developing markets where mobile is the first internet experience. This creates a paradox where PWAs are simultaneously more accessible (lightweight, bandwidth-efficient) and less accessible (architectural tension with assistive technologies). Progressive enhancement provides the resolution: by delivering core content via HTML first then layering JavaScript enhancements, PWAs can maintain their advanced capabilities while ensuring the baseline experience aligns with screen reader requirements and WCAG criteria, addressing both dimensions of accessibility."
}
```
```

### Q33: What is the relationship between web performance and user experience?
- **Expected:** Web performance directly affects user perception and engagement. Slow load times increase bounce rates, reduce conversions, and degrade perceived quality. Performance optimization (compression, caching, lazy loading) serves UX by reducing the time between user intent and interface response.
- **Got:** Web performance and UX have a complex, tension-filled relationship requiring dual remediation

**Model response:**

```
```json
{"answer": "Web performance and UX have a complex, tension-filled relationship requiring dual remediation", "explanation": "Based on the beliefs, web performance optimization creates inherent design tensions with user experience. Performance pressure—especially in SPA architectures where 80% of load time is frontend-dominated—incentivizes minimalist visual approaches (like flat design adopted for battery efficiency) that can produce measurable usability degradation (22% slower task completion per NNGroup research). This occurs because aggressive performance optimization through code minification, compression, and lazy loading often encourages removing visual signifiers that affordance theory identifies as critical for usability. The relationship is managed through two-layer remediation: technical performance optimization via the WPO stack (CDN, HTTP/2, minification, compression, lazy loading) addresses measurable load-time metrics captured by Core Web Vitals (TTFB, FCP, FID, CLS, LCP), while UX quality remediation via design systems maintains signifier integrity and cognitive constraints amid performance pressure. The key insight is that performance and UX are not inherently aligned—performance gains can harm usability if designers don't deliberately maintain signifier-rich patterns that are simultaneously performance-efficient."}
```
```

### Q45: How would you evaluate whether a design system adequately addresses cognitive load management and accessibility?
- **Expected:** Check cognitive load: does it enforce minimum target sizes (Fitts's law), consistent spacing (Gestalt proximity), progressive disclosure patterns, and information hierarchy? Check accessibility: does it encode WCAG contrast ratios in design tokens, provide ARIA patterns in components, support keyboard navigation, and maintain semantic HTML? The gap is usually at the API compliance layer — the design system may specify correctly but applications may implement incorrectly.
- **Got:** Evaluate through combined expert inspection and empirical testing across multiple dimensions

**Model response:**

```
```json
{"answer": "Evaluate through combined expert inspection and empirical testing across multiple dimensions", "explanation": "Based on my knowledge, design system evaluation requires verifying both cognitive load management and accessibility through complementary methods. For cognitive load, inspect whether the system encodes dual load management: spatial load via white-space tokens (leveraging Gestalt proximity to stay within Miller's 7±2 chunk capacity) and temporal load via progressive disclosure patterns. For accessibility, verify systematic encoding across disability categories: motor constraints (Fitts's law target sizing meeting WCAG 2.2's 24×24px minimum), visual constraints (design tokens enforcing WCAG AA 4.5:1 contrast ratios, fluid grids supporting 320px reflow), and cognitive constraints (load management overlapping with accessibility needs). Evaluation effectiveness requires combining expert inspection against these encoded rules with empirical user testing, since structural correctness alone doesn't guarantee interaction performance—the same principle that makes expert+empirical complementarity necessary for complete usability evaluation applies to validating design systems' systematic conventions."}
```
```


## By Objective

- **None**: 36/45 (80%)
