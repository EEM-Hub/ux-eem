# Exam Results: ux-design.md

**Date:** 2026-06-23 10:58
**Model:** claude:haiku
**Score:** 41/45 (91%)

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
- **Q13**: WRONG — What is the most common cause of screen reader inaccessibility?
  - Expected: Applications failing to comply with accessibility APIs is the single most common cause of screen reader inaccessibility. This breaks the semantic chain between the interface and assistive technology regardless of how well the design system encodes accessibility constraints.
  - Got: Missing or inadequate alt text on images
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
- **Q25**: WRONG — What does eye tracking reveal about user attention and the concept of the fold?
  - Expected: Eye tracking shows significantly more fixation on above-fold content, with studies suggesting an 84% attention differential. However, covert attention (processing without fixation) means fixation maps may overstate the difference, and there is no universal pixel definition for the fold across devices, limiting prescriptive application.
  - Got: Eye tracking reveals that the fold is less significant than traditionally thought; users follow content relevance and design hierarchy rather than stopping at the fold boundary.
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
  - Got: Balancing performance optimization with user experience quality
- **Q36**: CORRECT — How do design systems encode cognitive constraints like Fitts's law and Gestalt principles?
- **Q37**: CORRECT — What is the role of design tokens in enforcing visual standards?
- **Q38**: WRONG — How do design systems relate to ISO 9241 usability standards?
  - Expected: Design systems can implement ISO 9241's three quality dimensions at the component level: dialogue principles map to component behavior patterns, presentation attributes map to visual design rules, and usability factors map to measurable performance targets — making standards compliance systematic rather than ad hoc.
  - Got: Design systems implement ISO 9241 usability principles at scale
- **Q39**: CORRECT — What historical precedent exists for design system backlash?
- **Q40**: CORRECT — How does Material Design address the flat design signifier problem?
- **Q41**: CORRECT — What is Don Norman's affordance-signifier framework and why is it foundational?
- **Q42**: CORRECT — What are Jakob Nielsen's key contributions to usability?
- **Q43**: CORRECT — How did Three Mile Island influence HCI and usability thinking?
- **Q44**: CORRECT — You are reviewing a web application that uses infinite scrolling, hamburger navigation, and auto-playing carousels. What specific UX concerns would you raise?
- **Q45**: CORRECT — How would you evaluate whether a design system adequately addresses cognitive load management and accessibility?

## Wrong Answers (Detail)

### Q13: What is the most common cause of screen reader inaccessibility?
- **Expected:** Applications failing to comply with accessibility APIs is the single most common cause of screen reader inaccessibility. This breaks the semantic chain between the interface and assistive technology regardless of how well the design system encodes accessibility constraints.
- **Got:** Missing or inadequate alt text on images

**Model response:**

```
```json
{
  "answer": "Missing or inadequate alt text on images",
  "explanation": "Missing or poorly written alt text on images is the most frequently documented cause of screen reader inaccessibility across accessibility audits and WCAG violation studies. Images without alt text are completely inaccessible to screen reader users and convey no information, making this a critical barrier. While other issues like improper semantic HTML (missing form labels, incorrect heading hierarchy) and inadequate ARIA implementation are also very common, missing alt text consistently appears as the single most prevalent violation because images are ubiquitous on web pages and developers frequently omit alt attributes or use placeholder text rather than descriptive alternatives."
}
```
```

### Q25: What does eye tracking reveal about user attention and the concept of the fold?
- **Expected:** Eye tracking shows significantly more fixation on above-fold content, with studies suggesting an 84% attention differential. However, covert attention (processing without fixation) means fixation maps may overstate the difference, and there is no universal pixel definition for the fold across devices, limiting prescriptive application.
- **Got:** Eye tracking reveals that the fold is less significant than traditionally thought; users follow content relevance and design hierarchy rather than stopping at the fold boundary.

**Model response:**

```
```json
{
  "answer": "Eye tracking reveals that the fold is less significant than traditionally thought; users follow content relevance and design hierarchy rather than stopping at the fold boundary.",
  "explanation": "Eye tracking studies demonstrate that the traditional 'fold' concept—borrowed from print design—does not function as a hard boundary for user attention in web interfaces. Contrary to early web design assumptions that 'everything important should be above the fold,' eye tracking data shows users actively scroll to find relevant content, and their attention patterns are driven by information hierarchy, visual design cues, and perceived content value rather than scroll position. The fold is not a fixed line of attention; users engage with below-the-fold content readily when it's contextually relevant or when design signaling indicates more content exists. Furthermore, with responsive design and varied device sizes, the fold position itself is variable, making it an unreliable design constraint. Eye tracking has thus revealed that successful web design requires optimizing for scannability and content relevance across the entire page, not concentrating all important information above an arbitrary screen boundary."
}
```
```

### Q35: What is the dual quality mandate in modern web architecture?
- **Expected:** Modern web architecture has two complementary quality channels: remedial (design systems treating existing design debt, especially in SPAs) and preventive (progressive enhancement eliminating accessibility gaps by starting from an accessible baseline). Together they provide both corrective and preventive quality assurance.
- **Got:** Balancing performance optimization with user experience quality

**Model response:**

```
```json
{"answer": "Balancing performance optimization with user experience quality", "explanation": "Modern web architecture requires simultaneously achieving two quality objectives: delivering fast-loading, highly responsive applications while maintaining rich, accessible, and delightful user experiences. This dual mandate stems from the expectation that web applications must meet strict performance budgets (Core Web Vitals, time-to-interactive) while avoiding the stripped-down interfaces that pure performance optimization can produce. The mandate forces architects to make intentional tradeoffs between efficiency and polish, requiring thoughtful feature prioritization, progressive enhancement strategies, and deliberate optimization of both the technical stack and user-facing interactions to serve both speed and experience goals simultaneously."}
```
```

### Q38: How do design systems relate to ISO 9241 usability standards?
- **Expected:** Design systems can implement ISO 9241's three quality dimensions at the component level: dialogue principles map to component behavior patterns, presentation attributes map to visual design rules, and usability factors map to measurable performance targets — making standards compliance systematic rather than ad hoc.
- **Got:** Design systems implement ISO 9241 usability principles at scale

**Model response:**

```
```json
{
  "answer": "Design systems implement ISO 9241 usability principles at scale",
  "explanation": "Design systems serve as practical operationalizations of ISO 9241 standards by codifying usability principles (consistency, predictability, learnability, error prevention) into reusable components and patterns. ISO 9241, particularly parts 10-11 on dialogue principles and usability guidance, provides the normative framework for what makes interfaces usable; design systems translate these abstract principles into concrete, scalable implementations that ensure products conform to the standard across teams and time. A well-designed system enforces ISO 9241 compliance by making it the default rather than requiring each feature to independently discover and apply the standard."
}
```
```


## By Objective

- **None**: 41/45 (91%)
