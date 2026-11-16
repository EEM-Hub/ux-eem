# Exam Results: ux-design.md

**Date:** 2026-06-23 08:16
**Model:** claude:opus
**Score:** 44/45 (97%)

## Per-Question Results

- **Q1**: CORRECT — What is Fitts's law and how does it apply to web UI design?
- **Q2**: CORRECT — How does Hick's law relate to information architecture and navigation design?
- **Q3**: CORRECT — Explain the expertise reversal effect and its implications for progressive disclosure in web interfaces.
- **Q4**: CORRECT — How do Gestalt principles of proximity and similarity apply to visual hierarchy in web layouts?
- **Q5**: CORRECT — What is cognitive load theory and how do its three types map to UI design decisions?
- **Q6**: CORRECT — What are the usability problems with carousels in web design?
- **Q7**: CORRECT — When is infinite scrolling appropriate versus pagination?
- **Q8**: CORRECT — What is progressive disclosure and what cognitive principles justify its use?
- **Q9**: CORRECT — What are the usability concerns with modal windows?
- **Q10**: CORRECT — Why is the hamburger menu controversial in UX design?
- **Q11**: CORRECT — What are the four WCAG principles (POUR) and what does each require?
- **Q12**: CORRECT — How does WAI-ARIA complement semantic HTML for web accessibility?
- **Q13**: CORRECT — What is the most common cause of screen reader inaccessibility?
- **Q14**: CORRECT — How does progressive enhancement serve as an accessibility strategy?
- **Q15**: CORRECT — What does the WebAIM survey data show about the accessibility training gap?
- **Q16**: CORRECT — What caused the flat design usability crisis and how was it resolved?
- **Q17**: CORRECT — How do grid systems support cognitive load management in web layouts?
- **Q18**: CORRECT — What role does white space play in visual hierarchy according to Gestalt principles?
- **Q19**: CORRECT — How does responsive web design differ from adaptive design?
- **Q20**: CORRECT — What is the relationship between color theory and accessibility in web design?
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
- **Q33**: CORRECT — What is the relationship between web performance and user experience?
- **Q34**: CORRECT — How does above the fold apply in responsive web design?
- **Q35**: WRONG — What is the dual quality mandate in modern web architecture?
  - Expected: Modern web architecture has two complementary quality channels: remedial (design systems treating existing design debt, especially in SPAs) and preventive (progressive enhancement eliminating accessibility gaps by starting from an accessible baseline). Together they provide both corrective and preventive quality assurance.
  - Got: Legal enforcement of semantic HTML accessibility and design systems' prevention of signifier loss — law mandates the machine-readable semantic layer while design systems protect the human-perceivable visual layer.
- **Q36**: CORRECT — How do design systems encode cognitive constraints like Fitts's law and Gestalt principles?
- **Q37**: CORRECT — What is the role of design tokens in enforcing visual standards?
- **Q38**: CORRECT — How do design systems relate to ISO 9241 usability standards?
- **Q39**: CORRECT — What historical precedent exists for design system backlash?
- **Q40**: CORRECT — How does Material Design address the flat design signifier problem?
- **Q41**: CORRECT — What is Don Norman's affordance-signifier framework and why is it foundational?
- **Q42**: CORRECT — What are Jakob Nielsen's key contributions to usability?
- **Q43**: CORRECT — How did Three Mile Island influence HCI and usability thinking?
- **Q44**: CORRECT — You are reviewing a web application that uses infinite scrolling, hamburger navigation, and auto-playing carousels. What specific UX concerns would you raise?
- **Q45**: CORRECT — How would you evaluate whether a design system adequately addresses cognitive load management and accessibility?

## Wrong Answers (Detail)

### Q35: What is the dual quality mandate in modern web architecture?
- **Expected:** Modern web architecture has two complementary quality channels: remedial (design systems treating existing design debt, especially in SPAs) and preventive (progressive enhancement eliminating accessibility gaps by starting from an accessible baseline). Together they provide both corrective and preventive quality assurance.
- **Got:** Legal enforcement of semantic HTML accessibility and design systems' prevention of signifier loss — law mandates the machine-readable semantic layer while design systems protect the human-perceivable visual layer.

**Model response:**

```
{"answer": "Legal enforcement of semantic HTML accessibility and design systems' prevention of signifier loss — law mandates the machine-readable semantic layer while design systems protect the human-perceivable visual layer.", "explanation": "Modern web architecture operates under a dual quality mandate spanning two complementary accessibility layers. Legal enforcement (rooted in lawsuit precedent since 2000, ISO codification in 2012, and converging on WCAG 2.1 AA worldwide) mandates the semantic layer — the machine-readable structure that assistive technologies like screen readers depend on, fulfilled through native HTML semantics, ARIA augmentation, and accessibility API exposure. Simultaneously, design systems (evolved from pattern languages through formalized tokens) protect the visual-perceptual layer by encoding signifier requirements — such as WCAG AA 4.5:1 contrast ratios and minimum target sizes — as reusable, enforceable design decisions, preventing the kind of signifier loss that flat design's 22% performance degradation demonstrated. Together these create a dual enforcement mechanism ensuring accessibility operates at both the assistive-technology level (semantic) and the visual-cognition level (perceptual), with neither layer alone being sufficient for truly accessible web architecture."}
```


## By Objective

- **None**: 44/45 (97%)
