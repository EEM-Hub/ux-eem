# Exam Results: ux-design.md

**Date:** 2026-06-22 16:34
**Model:** claude:haiku
**Score:** 40/45 (88%)

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
  - Got: Missing or improper semantic HTML structure and missing alternative text for images
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
  - Got: Eye tracking reveals that the fold is not a hard barrier to user attention; users actively scroll to find relevant content, and attention follows content hierarchy and visual cues rather than stopping at the traditional fold point.
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
  - Got: The dual quality mandate refers to the simultaneous requirement to deliver both user experience quality (accessibility, usability, visual design) and technical quality (performance, maintainability, security) in web architecture.
- **Q36**: CORRECT — How do design systems encode cognitive constraints like Fitts's law and Gestalt principles?
- **Q37**: CORRECT — What is the role of design tokens in enforcing visual standards?
- **Q38**: CORRECT — How do design systems relate to ISO 9241 usability standards?
- **Q39**: WRONG — What historical precedent exists for design system backlash?
  - Expected: The 1980s grid system backlash, driven by perceived dogmatism and corporate association, shows that design enforcement mechanisms can provoke rejection when they convert quality floors into innovation ceilings. Design systems risk the same cycle if they ossify into rigid corporate standards rather than evolving frameworks.
  - Got: Twitter Bootstrap (2011–2015) backlash; also skeuomorphic design systems (2006–2013) and Apple's Aqua interface (2001–2006)
- **Q40**: CORRECT — How does Material Design address the flat design signifier problem?
- **Q41**: CORRECT — What is Don Norman's affordance-signifier framework and why is it foundational?
- **Q42**: CORRECT — What are Jakob Nielsen's key contributions to usability?
- **Q43**: CORRECT — How did Three Mile Island influence HCI and usability thinking?
- **Q44**: CORRECT — You are reviewing a web application that uses infinite scrolling, hamburger navigation, and auto-playing carousels. What specific UX concerns would you raise?
- **Q45**: WRONG — How would you evaluate whether a design system adequately addresses cognitive load management and accessibility?
  - Expected: Check cognitive load: does it enforce minimum target sizes (Fitts's law), consistent spacing (Gestalt proximity), progressive disclosure patterns, and information hierarchy? Check accessibility: does it encode WCAG contrast ratios in design tokens, provide ARIA patterns in components, support keyboard navigation, and maintain semantic HTML? The gap is usually at the API compliance layer — the design system may specify correctly but applications may implement incorrectly.
  - Got: Through systematic evaluation combining compliance audits, user testing with diverse participants, cognitive load measurement, and ongoing metrics monitoring

## Wrong Answers (Detail)

### Q13: What is the most common cause of screen reader inaccessibility?
- **Expected:** Applications failing to comply with accessibility APIs is the single most common cause of screen reader inaccessibility. This breaks the semantic chain between the interface and assistive technology regardless of how well the design system encodes accessibility constraints.
- **Got:** Missing or improper semantic HTML structure and missing alternative text for images

**Model response:**

```
```json
{
  "answer": "Missing or improper semantic HTML structure and missing alternative text for images",
  "explanation": "The most common causes of screen reader inaccessibility are twofold: (1) Failure to use semantic HTML elements (nav, main, article, header, footer, etc.) instead of generic divs and spans, which deprives screen readers of structural context, and (2) Missing alt text on images, which is among the most frequently cited WCAG violations in accessibility audits. When developers use improper semantic markup or omit alt text for images and icon buttons, screen readers cannot convey essential information to users. While many other issues contribute to poor accessibility (missing form labels, poor heading hierarchy, improper ARIA usage, keyboard navigation failures), the lack of semantic HTML and missing alt text represent the foundational, most frequently encountered violations that directly impact screen reader functionality across web applications."
}
```
```

### Q25: What does eye tracking reveal about user attention and the concept of the fold?
- **Expected:** Eye tracking shows significantly more fixation on above-fold content, with studies suggesting an 84% attention differential. However, covert attention (processing without fixation) means fixation maps may overstate the difference, and there is no universal pixel definition for the fold across devices, limiting prescriptive application.
- **Got:** Eye tracking reveals that the fold is not a hard barrier to user attention; users actively scroll to find relevant content, and attention follows content hierarchy and visual cues rather than stopping at the traditional fold point.

**Model response:**

```
```json
{"answer": "Eye tracking reveals that the fold is not a hard barrier to user attention; users actively scroll to find relevant content, and attention follows content hierarchy and visual cues rather than stopping at the traditional fold point.", "explanation": "Eye tracking studies have fundamentally challenged the notion that content 'above the fold' is the primary area of user focus. Research shows users regularly scroll when looking for information, contradicting the assumption that the fold represents a critical attention threshold. Instead, eye tracking reveals that user attention is driven by perceived relevance, visual hierarchy, interactive elements, and calls-to-action rather than arbitrary page boundaries. The fold exists as a natural break point but not as an attentional cliff—users' gaze patterns show they will follow content and search targets regardless of position, making content organization, visual priority, and scannability more important than strict above-the-fold placement."}
```
```

### Q35: What is the dual quality mandate in modern web architecture?
- **Expected:** Modern web architecture has two complementary quality channels: remedial (design systems treating existing design debt, especially in SPAs) and preventive (progressive enhancement eliminating accessibility gaps by starting from an accessible baseline). Together they provide both corrective and preventive quality assurance.
- **Got:** The dual quality mandate refers to the simultaneous requirement to deliver both user experience quality (accessibility, usability, visual design) and technical quality (performance, maintainability, security) in web architecture.

**Model response:**

```
```json
{
  "answer": "The dual quality mandate refers to the simultaneous requirement to deliver both user experience quality (accessibility, usability, visual design) and technical quality (performance, maintainability, security) in web architecture.",
  "explanation": "Modern web architecture cannot treat user-facing and technical quality as separate concerns. The dual mandate acknowledges that excellent UX depends on sound technical foundations—fast performance, robust security, and maintainable code—while conversely, technical excellence without user-centered design results in products that serve no one well. This requires balancing feature richness with performance, embracing accessibility not as an afterthought but as a core architectural principle, and making architectural decisions that support both developer experience and end-user experience. The mandate is 'dual' because optimizing for only one dimension creates systems that fail: performant but unusable, or feature-rich but slow and inaccessible."
}
```
```

### Q39: What historical precedent exists for design system backlash?
- **Expected:** The 1980s grid system backlash, driven by perceived dogmatism and corporate association, shows that design enforcement mechanisms can provoke rejection when they convert quality floors into innovation ceilings. Design systems risk the same cycle if they ossify into rigid corporate standards rather than evolving frameworks.
- **Got:** Twitter Bootstrap (2011–2015) backlash; also skeuomorphic design systems (2006–2013) and Apple's Aqua interface (2001–2006)

**Model response:**

```
```json
{
  "answer": "Twitter Bootstrap (2011–2015) backlash; also skeuomorphic design systems (2006–2013) and Apple's Aqua interface (2001–2006)",
  "explanation": "Bootstrap's widespread adoption created a homogenization problem—thousands of websites looked identical because they used the default framework, sparking criticism that design systems could constrain creativity rather than enable it. Similarly, the skeuomorphic design trend (realistic textures, gradients, shadows) pioneered by early Apple design systems faced significant backlash as designers and users rejected the faux-realism in favor of cleaner, flatter aesthetics. These precedents established a recurring pattern: when a design system becomes too prescriptive or ubiquitous, it generates cultural resistance from designers seeking differentiation and from users fatigued by visual consistency. This tension between system coherence and creative freedom remains central to modern design system governance."
}
```
```

### Q45: How would you evaluate whether a design system adequately addresses cognitive load management and accessibility?
- **Expected:** Check cognitive load: does it enforce minimum target sizes (Fitts's law), consistent spacing (Gestalt proximity), progressive disclosure patterns, and information hierarchy? Check accessibility: does it encode WCAG contrast ratios in design tokens, provide ARIA patterns in components, support keyboard navigation, and maintain semantic HTML? The gap is usually at the API compliance layer — the design system may specify correctly but applications may implement incorrectly.
- **Got:** Through systematic evaluation combining compliance audits, user testing with diverse participants, cognitive load measurement, and ongoing metrics monitoring

**Model response:**

```
```json
{
  "answer": "Through systematic evaluation combining compliance audits, user testing with diverse participants, cognitive load measurement, and ongoing metrics monitoring",
  "explanation": "Evaluate a design system's cognitive load and accessibility by conducting multi-method assessments: (1) Automated and manual WCAG compliance audits for accessibility standards; (2) Cognitive load user testing using NASA-TLX scales, task completion rates, and error analysis to measure decision-making burden; (3) Structured user testing with participants including people with disabilities (visual, motor, cognitive, hearing impairments) to identify real-world friction; (4) Component consistency analysis to ensure pattern predictability reduces learning curve; (5) Documentation clarity evaluation to assess how easily designers can apply the system; (6) Ongoing metrics tracking task completion time, accessibility issue volume, and designer confidence scores. Success indicators include: accessibility scores ≥95% WCAG AA compliance, cognitive load decreasing as designers gain familiarity, zero critical accessibility failures in user testing, and positive feedback on system learnability. The system should simplify rather than multiply designer choices—fewer high-quality options reduce decision fatigue while better serving users with varied abilities and cognitive preferences."
}
```
```


## By Objective

- **None**: 40/45 (88%)
