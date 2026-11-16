# Exam Results: ux-design.md

**Date:** 2026-06-23 09:26
**Model:** claude:sonnet
**Score:** 37/45 (82%)

## Per-Question Results

- **Q1**: CORRECT — What is Fitts's law and how does it apply to web UI design?
- **Q2**: CORRECT — How does Hick's law relate to information architecture and navigation design?
- **Q3**: CORRECT — Explain the expertise reversal effect and its implications for progressive disclosure in web interfaces.
- **Q4**: CORRECT — How do Gestalt principles of proximity and similarity apply to visual hierarchy in web layouts?
- **Q5**: WRONG — What is cognitive load theory and how do its three types map to UI design decisions?
  - Expected: Cognitive load theory distinguishes intrinsic load (inherent task complexity), extraneous load (unnecessary processing from poor design), and germane load (processing that builds understanding). UI design should minimize extraneous load through clear layout and progressive disclosure while supporting germane load through meaningful interactions.
  - Got: Cognitive load theory identifies three types: intrinsic (material difficulty), extraneous (presentation design), and germane (productive schema-building). For UI design, only extraneous load is directly designer-controlled, while intrinsic load is determined by the task itself. Crucially, germane load is not an independent design lever but the residual working memory capacity after extraneous load is subtracted. This means all UI design interventions that improve comprehension work exclusively through extraneous load reduction—techniques like progressive disclosure, clear visual hierarchy, and minimizing split-attention effects reduce extraneous load imposed by poor presentation, thereby freeing working memory capacity for productive germane processing. Designers cannot directly amplify germane load; they can only remove extraneous obstacles that prevent users from applying their full cognitive capacity to the inherent task demands.
- **Q6**: CORRECT — What are the usability problems with carousels in web design?
- **Q7**: CORRECT — When is infinite scrolling appropriate versus pagination?
- **Q8**: CORRECT — What is progressive disclosure and what cognitive principles justify its use?
- **Q9**: WRONG — What are the usability concerns with modal windows?
  - Expected: Modal windows block interaction with the underlying page, disrupting user flow and potentially causing loss of context. They can trap keyboard focus creating accessibility problems, they interrupt task completion, and on mobile they often have dismiss targets that are too small to tap reliably.
  - Got: Modal windows have multiple usability concerns across cognitive, security, and load management dimensions.
- **Q10**: CORRECT — Why is the hamburger menu controversial in UX design?
- **Q11**: WRONG — What are the four WCAG principles (POUR) and what does each require?
  - Expected: Perceivable (content must be presentable in ways users can perceive), Operable (UI components must be operable by all users), Understandable (content and UI must be understandable), Robust (content must be interpretable by assistive technologies). Together they cover the full spectrum of accessibility requirements.
  - Got: Perceivable, Operable, Understandable, and Robust
- **Q12**: CORRECT — How does WAI-ARIA complement semantic HTML for web accessibility?
- **Q13**: CORRECT — What is the most common cause of screen reader inaccessibility?
- **Q14**: CORRECT — How does progressive enhancement serve as an accessibility strategy?
- **Q15**: WRONG — What does the WebAIM survey data show about the accessibility training gap?
  - Expected: A 2018 WebAIM survey found that close to 93% of web accessibility practitioners received no formal schooling on accessibility. This creates a systematic gap between available tools and standards (WCAG, ARIA, design systems) and practitioners' ability to apply them correctly.
  - Got: a
- **Q16**: CORRECT — What caused the flat design usability crisis and how was it resolved?
- **Q17**: CORRECT — How do grid systems support cognitive load management in web layouts?
- **Q18**: CORRECT — What role does white space play in visual hierarchy according to Gestalt principles?
- **Q19**: CORRECT — How does responsive web design differ from adaptive design?
- **Q20**: CORRECT — What is the relationship between color theory and accessibility in web design?
- **Q21**: CORRECT — What is the difference between heuristic evaluation and cognitive walkthrough?
- **Q22**: CORRECT — How does A/B testing complement qualitative usability testing?
- **Q23**: CORRECT — What is Simpson's paradox and why does it matter for A/B test analysis?
- **Q24**: CORRECT — How does card sorting support information architecture design?
- **Q25**: WRONG — What does eye tracking reveal about user attention and the concept of the fold?
  - Expected: Eye tracking shows significantly more fixation on above-fold content, with studies suggesting an 84% attention differential. However, covert attention (processing without fixation) means fixation maps may overstate the difference, and there is no universal pixel definition for the fold across devices, limiting prescriptive application.
  - Got: Eye tracking reveals an 84% attention differential between above-the-fold and below-the-fold content, validated through fixation data showing that users process information during brief fixation pauses rather than during saccadic eye movements. This empirical evidence supports Nielsen's finding that 77% of users do not scroll below the fold, as content below the fold receives fewer or no fixations. However, eye tracking has limitations: heat maps show fixation frequency rather than attention or comprehension directly, and covert attention means users can attend to content they are not directly fixating on. The eye-mind hypothesis (Just & Carpenter, 1980) assumes fixated content is being cognitively processed, but this relationship is contested. Overall, eye tracking provides the empirical mechanism explaining why above-the-fold placement matters—users process information where they fixate, and fixations concentrate above the fold—though it measures gaze location rather than attention or understanding per se.
- **Q26**: CORRECT — What is user-centered design and what are its core principles?
- **Q27**: CORRECT — How do personas help close the mental-model gap between designers and users?
- **Q28**: CORRECT — What role do wireframes play in the UX design process?
- **Q29**: CORRECT — What is a design system and how does it differ from a style guide?
- **Q30**: CORRECT — How does design thinking's abductive reasoning approach apply to wicked problems in UX?
- **Q31**: CORRECT — What UX challenges do single-page applications introduce?
- **Q32**: CORRECT — How do progressive web apps balance capabilities with accessibility?
- **Q33**: WRONG — What is the relationship between web performance and user experience?
  - Expected: Web performance directly affects user perception and engagement. Slow load times increase bounce rates, reduce conversions, and degrade perceived quality. Performance optimization (compression, caching, lazy loading) serves UX by reducing the time between user intent and interface response.
  - Got: Web performance is a critical component of user experience, but optimization creates inherent design tensions
- **Q34**: CORRECT — How does above the fold apply in responsive web design?
- **Q35**: WRONG — What is the dual quality mandate in modern web architecture?
  - Expected: Modern web architecture has two complementary quality channels: remedial (design systems treating existing design debt, especially in SPAs) and preventive (progressive enhancement eliminating accessibility gaps by starting from an accessible baseline). Together they provide both corrective and preventive quality assurance.
  - Got: Semantic accessibility and visual usability
- **Q36**: CORRECT — How do design systems encode cognitive constraints like Fitts's law and Gestalt principles?
- **Q37**: CORRECT — What is the role of design tokens in enforcing visual standards?
- **Q38**: WRONG — How do design systems relate to ISO 9241 usability standards?
  - Expected: Design systems can implement ISO 9241's three quality dimensions at the component level: dialogue principles map to component behavior patterns, presentation attributes map to visual design rules, and usability factors map to measurable performance targets — making standards compliance systematic rather than ad hoc.
  - Got: Design systems operationalize ISO 9241 standards through systematic implementation
- **Q39**: CORRECT — What historical precedent exists for design system backlash?
- **Q40**: CORRECT — How does Material Design address the flat design signifier problem?
- **Q41**: CORRECT — What is Don Norman's affordance-signifier framework and why is it foundational?
- **Q42**: CORRECT — What are Jakob Nielsen's key contributions to usability?
- **Q43**: CORRECT — How did Three Mile Island influence HCI and usability thinking?
- **Q44**: CORRECT — You are reviewing a web application that uses infinite scrolling, hamburger navigation, and auto-playing carousels. What specific UX concerns would you raise?
- **Q45**: CORRECT — How would you evaluate whether a design system adequately addresses cognitive load management and accessibility?

## Wrong Answers (Detail)

### Q5: What is cognitive load theory and how do its three types map to UI design decisions?
- **Expected:** Cognitive load theory distinguishes intrinsic load (inherent task complexity), extraneous load (unnecessary processing from poor design), and germane load (processing that builds understanding). UI design should minimize extraneous load through clear layout and progressive disclosure while supporting germane load through meaningful interactions.
- **Got:** Cognitive load theory identifies three types: intrinsic (material difficulty), extraneous (presentation design), and germane (productive schema-building). For UI design, only extraneous load is directly designer-controlled, while intrinsic load is determined by the task itself. Crucially, germane load is not an independent design lever but the residual working memory capacity after extraneous load is subtracted. This means all UI design interventions that improve comprehension work exclusively through extraneous load reduction—techniques like progressive disclosure, clear visual hierarchy, and minimizing split-attention effects reduce extraneous load imposed by poor presentation, thereby freeing working memory capacity for productive germane processing. Designers cannot directly amplify germane load; they can only remove extraneous obstacles that prevent users from applying their full cognitive capacity to the inherent task demands.

**Model response:**

```
```json
{"answer": "Cognitive load theory identifies three types: intrinsic (material difficulty), extraneous (presentation design), and germane (productive schema-building). For UI design, only extraneous load is directly designer-controlled, while intrinsic load is determined by the task itself. Crucially, germane load is not an independent design lever but the residual working memory capacity after extraneous load is subtracted. This means all UI design interventions that improve comprehension work exclusively through extraneous load reduction—techniques like progressive disclosure, clear visual hierarchy, and minimizing split-attention effects reduce extraneous load imposed by poor presentation, thereby freeing working memory capacity for productive germane processing. Designers cannot directly amplify germane load; they can only remove extraneous obstacles that prevent users from applying their full cognitive capacity to the inherent task demands.", "explanation": "The mapping is fundamentally asymmetric: UI designers control presentation (extraneous load) but not task complexity (intrinsic load) or productive capacity (germane load, which emerges from what remains). Every usability improvement operates through the same mechanism—reducing unnecessary cognitive burden imposed by interface design choices—rather than through independent manipulation of all three load types. This explains why progressive disclosure, simplified navigation, and clear signifiers all work: they minimize extraneous load, leaving more working memory available for understanding and completing the user's actual goal."}
```
```

### Q9: What are the usability concerns with modal windows?
- **Expected:** Modal windows block interaction with the underlying page, disrupting user flow and potentially causing loss of context. They can trap keyboard focus creating accessibility problems, they interrupt task completion, and on mobile they often have dismiss targets that are too small to tap reliably.
- **Got:** Modal windows have multiple usability concerns across cognitive, security, and load management dimensions.

**Model response:**

```
```json
{
  "answer": "Modal windows have multiple usability concerns across cognitive, security, and load management dimensions.",
  "explanation": "Modal dialogs fail in three independent ways: (1) Cognitive failures—users develop habituation and dismiss modals without reading them, undermining warnings; modals also cover information users need to complete the modal's own input fields, creating self-defeating information blocking. (2) Security risks—modals can steal focus by intercepting keyboard/mouse input intended for other programs. (3) Load management—modals violate spatial integration principles by separating related information between the modal and the blocked parent window (split-attention effect), and they can block clipboard operations users need. Usability experts recommend alternatives like undo functionality instead of modal warnings, and progressive disclosure instead of modal confirmations, as these avoid the modal interaction pattern's structural problems entirely."
}
```
```

### Q11: What are the four WCAG principles (POUR) and what does each require?
- **Expected:** Perceivable (content must be presentable in ways users can perceive), Operable (UI components must be operable by all users), Understandable (content and UI must be understandable), Robust (content must be interpretable by assistive technologies). Together they cover the full spectrum of accessibility requirements.
- **Got:** Perceivable, Operable, Understandable, and Robust

**Model response:**

```
```json
{"answer": "Perceivable, Operable, Understandable, and Robust", "explanation": "Based on my knowledge, WCAG's four accessibility principles are Perceivable, Operable, Understandable, and Robust (POUR). These principles organize all WCAG success criteria by concern within a backwards-compatible, tiered conformance architecture. However, I don't have explicit detailed definitions in my current knowledge base of what each principle specifically requires, only that they serve as the organizational framework for WCAG's success criteria across conformance levels A, AA, and AAA."}
```
```

### Q15: What does the WebAIM survey data show about the accessibility training gap?
- **Expected:** A 2018 WebAIM survey found that close to 93% of web accessibility practitioners received no formal schooling on accessibility. This creates a systematic gap between available tools and standards (WCAG, ARIA, design systems) and practitioners' ability to apply them correctly.
- **Got:** a

**Model response:**

```
```json
{"answer": "A 2018 WebAIM survey found that close to 93% of web accessibility practitioners received no formal schooling on accessibility.", "explanation": "The WebAIM survey data reveals a severe accessibility training gap in the field. Despite working as web accessibility practitioners, nearly 93% of respondents reported having received no formal education or schooling specifically on accessibility topics. This finding demonstrates that the vast majority of people working in web accessibility are self-taught or learned through on-the-job experience rather than through structured educational programs, highlighting a significant gap between professional practice and formal training infrastructure in the accessibility domain."}
```
```

### Q25: What does eye tracking reveal about user attention and the concept of the fold?
- **Expected:** Eye tracking shows significantly more fixation on above-fold content, with studies suggesting an 84% attention differential. However, covert attention (processing without fixation) means fixation maps may overstate the difference, and there is no universal pixel definition for the fold across devices, limiting prescriptive application.
- **Got:** Eye tracking reveals an 84% attention differential between above-the-fold and below-the-fold content, validated through fixation data showing that users process information during brief fixation pauses rather than during saccadic eye movements. This empirical evidence supports Nielsen's finding that 77% of users do not scroll below the fold, as content below the fold receives fewer or no fixations. However, eye tracking has limitations: heat maps show fixation frequency rather than attention or comprehension directly, and covert attention means users can attend to content they are not directly fixating on. The eye-mind hypothesis (Just & Carpenter, 1980) assumes fixated content is being cognitively processed, but this relationship is contested. Overall, eye tracking provides the empirical mechanism explaining why above-the-fold placement matters—users process information where they fixate, and fixations concentrate above the fold—though it measures gaze location rather than attention or understanding per se.

**Model response:**

```
```json
{"answer": "Eye tracking reveals an 84% attention differential between above-the-fold and below-the-fold content, validated through fixation data showing that users process information during brief fixation pauses rather than during saccadic eye movements. This empirical evidence supports Nielsen's finding that 77% of users do not scroll below the fold, as content below the fold receives fewer or no fixations. However, eye tracking has limitations: heat maps show fixation frequency rather than attention or comprehension directly, and covert attention means users can attend to content they are not directly fixating on. The eye-mind hypothesis (Just & Carpenter, 1980) assumes fixated content is being cognitively processed, but this relationship is contested. Overall, eye tracking provides the empirical mechanism explaining why above-the-fold placement matters—users process information where they fixate, and fixations concentrate above the fold—though it measures gaze location rather than attention or understanding per se.", "explanation": "Eye tracking validates the fold concept through fixation-based evidence: the 84% attention differential between above-fold and below-fold content is explained by users processing information during fixations, and below-fold content receives fewer fixations because 77% of users don't scroll. The eye-mind hypothesis suggests fixations indicate cognitive processing, providing the mechanism linking gaze patterns to the observed fold effect. However, limitations exist: heat maps show where users looked (fixation frequency) but not necessarily what they attended to or comprehended, and covert attention allows processing of non-fixated content. Eye tracking thus offers strong but imperfect evidence that the fold matters because users concentrate their information-processing fixations in the initially visible area."}
```
```

### Q33: What is the relationship between web performance and user experience?
- **Expected:** Web performance directly affects user perception and engagement. Slow load times increase bounce rates, reduce conversions, and degrade perceived quality. Performance optimization (compression, caching, lazy loading) serves UX by reducing the time between user intent and interface response.
- **Got:** Web performance is a critical component of user experience, but optimization creates inherent design tensions

**Model response:**

```
```json
{"answer": "Web performance is a critical component of user experience, but optimization creates inherent design tensions", "explanation": "Web performance directly impacts user experience through page load times and interaction responsiveness, with Core Web Vitals metrics (TTFB, FCP, FID, CLS, LCP) providing measurable benchmarks for user-perceptible performance. Since at least 80% of page load time is frontend-controlled, performance optimization focuses on frontend techniques like minification, compression, and lazy loading. However, performance optimization creates a design tension: aggressive optimization often encourages minimalist visual approaches that can harm usability through signifier loss, as demonstrated by flat design's measured 22% performance degradation. This tension is particularly acute in SPA architectures, which both intensify the frontend performance challenge and require JavaScript-heavy compensatory mechanisms. Therefore, performance is not merely 'faster is better' but requires balancing load time optimization against the preservation of visual signifiers and other UX quality factors."}
```
```

### Q35: What is the dual quality mandate in modern web architecture?
- **Expected:** Modern web architecture has two complementary quality channels: remedial (design systems treating existing design debt, especially in SPAs) and preventive (progressive enhancement eliminating accessibility gaps by starting from an accessible baseline). Together they provide both corrective and preventive quality assurance.
- **Got:** Semantic accessibility and visual usability

**Model response:**

```
```json
{"answer": "Semantic accessibility and visual usability", "explanation": "Modern web architecture faces a dual quality mandate operating across complementary layers: legal enforcement (lawsuit precedent since 2000, ISO codification, WCAG standards) mandates the machine-readable semantic layer through proper HTML markup and ARIA attributes for assistive technologies, while design systems must protect the human-perceivable visual layer by preventing signifier loss and maintaining visual hierarchy. This dual enforcement mechanism ensures accessibility operates at both the assistive-technology level (screen readers, keyboard navigation) and the visual-cognition level (perceivable affordances, clear hierarchy), making modern web development accountable to both machine interpretation and human perception simultaneously."}
```
```

### Q38: How do design systems relate to ISO 9241 usability standards?
- **Expected:** Design systems can implement ISO 9241's three quality dimensions at the component level: dialogue principles map to component behavior patterns, presentation attributes map to visual design rules, and usability factors map to measurable performance targets — making standards compliance systematic rather than ad hoc.
- **Got:** Design systems operationalize ISO 9241 standards through systematic implementation

**Model response:**

```
```json
{"answer": "Design systems operationalize ISO 9241 standards through systematic implementation", "explanation": "ISO 9241 defines formal international standards for interface quality across dialogue principles (including consistency), presentation attributes (clarity, discriminability, legibility, etc.), and usability factors. Design systems provide the practical implementation framework for these standards: they are comprehensive frameworks of standards, reusable components, and documentation that serve as a single source of truth for consistent product development. Design tokens (named variables for color, typography, spacing) systematically encode and enforce ISO 9241's presentation attributes across an entire application, making compliance a design-system property rather than per-component decisions. Essentially, ISO 9241 provides the formal specification of what usable interfaces should achieve, while design systems provide the systematic tooling to reliably implement and maintain those standards at organizational scale."}
```
```


## By Objective

- **None**: 37/45 (82%)
