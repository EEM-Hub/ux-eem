# Exam Results: ux-design.md

**Date:** 2026-06-22 15:36
**Model:** claude:sonnet
**Score:** 38/45 (84%)

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
  - Got: Progressive disclosure is a design pattern that reveals information and interface elements gradually, showing essential features first and more advanced options as needed.
- **Q9**: CORRECT — What are the usability concerns with modal windows?
- **Q10**: CORRECT — Why is the hamburger menu controversial in UX design?
- **Q11**: CORRECT — What are the four WCAG principles (POUR) and what does each require?
- **Q12**: CORRECT — How does WAI-ARIA complement semantic HTML for web accessibility?
- **Q13**: WRONG — What is the most common cause of screen reader inaccessibility?
  - Expected: Applications failing to comply with accessibility APIs is the single most common cause of screen reader inaccessibility. This breaks the semantic chain between the interface and assistive technology regardless of how well the design system encodes accessibility constraints.
  - Got: Missing or inadequate alternative text for images
- **Q14**: CORRECT — How does progressive enhancement serve as an accessibility strategy?
- **Q15**: WRONG — What does the WebAIM survey data show about the accessibility training gap?
  - Expected: A 2018 WebAIM survey found that close to 93% of web accessibility practitioners received no formal schooling on accessibility. This creates a systematic gap between available tools and standards (WCAG, ARIA, design systems) and practitioners' ability to apply them correctly.
  - Got: Approximately 70-80% of web professionals report having little to no formal accessibility training
- **Q16**: CORRECT — What caused the flat design usability crisis and how was it resolved?
- **Q17**: CORRECT — How do grid systems support cognitive load management in web layouts?
- **Q18**: CORRECT — What role does white space play in visual hierarchy according to Gestalt principles?
- **Q19**: CORRECT — How does responsive web design differ from adaptive design?
- **Q20**: WRONG — What is the relationship between color theory and accessibility in web design?
  - Expected: Color theory provides rules for contrast, depth perception (warm colors advance, cool recede), and hue relationships that directly serve accessibility requirements. WCAG contrast ratios translate these perceptual principles into enforceable thresholds. However, color harmony has no universal formula, limiting what can be systematically enforced.
  - Got: Color theory provides the foundational principles for creating accessible color schemes in web design
- **Q21**: CORRECT — What is the difference between heuristic evaluation and cognitive walkthrough?
- **Q22**: CORRECT — How does A/B testing complement qualitative usability testing?
- **Q23**: CORRECT — What is Simpson's paradox and why does it matter for A/B test analysis?
- **Q24**: CORRECT — How does card sorting support information architecture design?
- **Q25**: WRONG — What does eye tracking reveal about user attention and the concept of the fold?
  - Expected: Eye tracking shows significantly more fixation on above-fold content, with studies suggesting an 84% attention differential. However, covert attention (processing without fixation) means fixation maps may overstate the difference, and there is no universal pixel definition for the fold across devices, limiting prescriptive application.
  - Got: Eye tracking reveals that while users do scroll and view content below the fold, the majority of attention is concentrated above the fold, particularly in the upper-left area following F-pattern or Z-pattern scanning behaviors.
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
  - Got: Functional quality and experiential quality
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
  - Got: Use a combination of automated testing, heuristic evaluation, and user testing across both dimensions

## Wrong Answers (Detail)

### Q8: What is progressive disclosure and what cognitive principles justify its use?
- **Expected:** Progressive disclosure stages information reveal to show only what is needed at each step. It is justified by working memory limits (reducing visible options reduces extraneous cognitive load), Gestalt grouping (fewer elements create clearer visual hierarchy), and Hick's law (fewer visible choices speed decision-making).
- **Got:** Progressive disclosure is a design pattern that reveals information and interface elements gradually, showing essential features first and more advanced options as needed.

**Model response:**

```
```json
{"answer": "Progressive disclosure is a design pattern that reveals information and interface elements gradually, showing essential features first and more advanced options as needed.", "explanation": "Progressive disclosure is justified by several cognitive principles: it reduces cognitive load by limiting the amount of information users must process simultaneously, respects working memory limitations (Miller's Law of 7±2 items), supports recognition over recall by contextually revealing options when relevant, and implements chunking to make complex interfaces more manageable. This approach prevents decision paralysis and interface overwhelm by matching information presentation to user expertise levels and task progression, allowing novices to accomplish basic tasks without confronting advanced complexity while still providing access to deeper functionality for expert users who need it."}
```
```

### Q13: What is the most common cause of screen reader inaccessibility?
- **Expected:** Applications failing to comply with accessibility APIs is the single most common cause of screen reader inaccessibility. This breaks the semantic chain between the interface and assistive technology regardless of how well the design system encodes accessibility constraints.
- **Got:** Missing or inadequate alternative text for images

**Model response:**

```
```json
{"answer": "Missing or inadequate alternative text for images", "explanation": "The most common cause of screen reader inaccessibility is missing or inadequate alternative text (alt attributes) for images. This issue appears on the majority of websites and prevents screen reader users from understanding non-text content. When images lack alt text, screen readers either skip them entirely or read out unhelpful file names like 'IMG_2847.jpg'. While other issues like missing form labels, poor heading structure, and improper ARIA usage are also prevalent, image accessibility violations consistently rank as the #1 issue in automated accessibility audits and affect virtually every type of web content from informational graphics to decorative elements to functional icons."}
```
```

### Q15: What does the WebAIM survey data show about the accessibility training gap?
- **Expected:** A 2018 WebAIM survey found that close to 93% of web accessibility practitioners received no formal schooling on accessibility. This creates a systematic gap between available tools and standards (WCAG, ARIA, design systems) and practitioners' ability to apply them correctly.
- **Got:** Approximately 70-80% of web professionals report having little to no formal accessibility training

**Model response:**

```
```json
{"answer": "Approximately 70-80% of web professionals report having little to no formal accessibility training", "explanation": "WebAIM's practitioner surveys consistently reveal a significant accessibility training gap in the web development and design industry. The data shows that the vast majority of professionals working on web projects have not received formal education or structured training in web accessibility, instead relying on self-directed learning or on-the-job experience. This training gap contributes to the persistent accessibility barriers found on websites, as practitioners may not have the foundational knowledge needed to implement WCAG guidelines effectively or understand the diverse needs of users with disabilities."}
```
```

### Q20: What is the relationship between color theory and accessibility in web design?
- **Expected:** Color theory provides rules for contrast, depth perception (warm colors advance, cool recede), and hue relationships that directly serve accessibility requirements. WCAG contrast ratios translate these perceptual principles into enforceable thresholds. However, color harmony has no universal formula, limiting what can be systematically enforced.
- **Got:** Color theory provides the foundational principles for creating accessible color schemes in web design

**Model response:**

```
```json
{"answer": "Color theory provides the foundational principles for creating accessible color schemes in web design", "explanation": "Color theory and accessibility are intrinsically linked in web design. Color theory principles—such as contrast ratios, hue relationships, and luminance—directly inform accessibility standards like WCAG requirements for text readability and visual hierarchy. Understanding color theory enables designers to create palettes that accommodate color vision deficiencies (affecting approximately 8% of males and 0.5% of females), ensure sufficient contrast for low vision users, and avoid relying solely on color to convey information. Effective accessible design requires both theoretical knowledge of how colors interact perceptually and practical application of those principles to meet minimum contrast ratios (4.5:1 for normal text, 3:1 for large text) and support diverse visual capabilities across the user population."}
```
```

### Q25: What does eye tracking reveal about user attention and the concept of the fold?
- **Expected:** Eye tracking shows significantly more fixation on above-fold content, with studies suggesting an 84% attention differential. However, covert attention (processing without fixation) means fixation maps may overstate the difference, and there is no universal pixel definition for the fold across devices, limiting prescriptive application.
- **Got:** Eye tracking reveals that while users do scroll and view content below the fold, the majority of attention is concentrated above the fold, particularly in the upper-left area following F-pattern or Z-pattern scanning behaviors.

**Model response:**

```
```json
{"answer": "Eye tracking reveals that while users do scroll and view content below the fold, the majority of attention is concentrated above the fold, particularly in the upper-left area following F-pattern or Z-pattern scanning behaviors.", "explanation": "Eye tracking studies have debunked the myth that users never scroll below the fold, demonstrating that users will engage with lower content when it appears valuable. However, these studies also reveal that content above the fold receives disproportionately more viewing time and attention, and critically, users make rapid judgments about page credibility and relevance based on what they see immediately without scrolling. The fold acts not as an absolute barrier but as a priority zone—users scan above-the-fold content first to determine whether the page merits further exploration. This means designers should place key value propositions, compelling content, and clear navigation above the fold to encourage continued engagement, while recognizing that users will scroll for content they find worthwhile."}
```
```

### Q35: What is the dual quality mandate in modern web architecture?
- **Expected:** Modern web architecture has two complementary quality channels: remedial (design systems treating existing design debt, especially in SPAs) and preventive (progressive enhancement eliminating accessibility gaps by starting from an accessible baseline). Together they provide both corrective and preventive quality assurance.
- **Got:** Functional quality and experiential quality

**Model response:**

```
```json
{"answer": "Functional quality and experiential quality", "explanation": "The dual quality mandate in modern web architecture refers to the requirement to simultaneously deliver both functional quality (performance, reliability, security, and technical correctness) and experiential quality (usability, accessibility, aesthetic appeal, and user delight). This represents the fundamental tension in web development where teams must balance technical excellence with user-centered design, ensuring systems are not only robust and performant but also intuitive and engaging. Success requires architectural decisions that support both dimensions, such as progressive enhancement, responsive design, and performance budgets that preserve interaction quality."}
```
```

### Q45: How would you evaluate whether a design system adequately addresses cognitive load management and accessibility?
- **Expected:** Check cognitive load: does it enforce minimum target sizes (Fitts's law), consistent spacing (Gestalt proximity), progressive disclosure patterns, and information hierarchy? Check accessibility: does it encode WCAG contrast ratios in design tokens, provide ARIA patterns in components, support keyboard navigation, and maintain semantic HTML? The gap is usually at the API compliance layer — the design system may specify correctly but applications may implement incorrectly.
- **Got:** Use a combination of automated testing, heuristic evaluation, and user testing across both dimensions

**Model response:**

```
```json
{"answer": "Use a combination of automated testing, heuristic evaluation, and user testing across both dimensions", "explanation": "To evaluate cognitive load management, assess consistency across components, measure task completion efficiency, audit documentation clarity, and test the learning curve with new users. For accessibility, run automated WCAG compliance tools (axe, Lighthouse), conduct manual keyboard and screen reader testing, verify color contrast ratios, and perform user testing with people who have disabilities. Key metrics include: component reuse patterns, decision points per task, WCAG conformance level, keyboard navigability score, and real user feedback from diverse ability groups. A well-designed system should show high consistency scores, minimal steps for common tasks, AA or AAA WCAG compliance, and positive feedback from both neurotypical users and those using assistive technologies."}
```
```


## By Objective

- **None**: 38/45 (84%)
