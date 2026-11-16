# Exam Results: ux-design.md

**Date:** 2026-06-23 09:49
**Model:** claude:sonnet
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
  - Got: Progressive disclosure is a UX pattern that reveals information and interface elements gradually, showing only what's immediately necessary and hiding advanced options until needed.
- **Q9**: CORRECT — What are the usability concerns with modal windows?
- **Q10**: CORRECT — Why is the hamburger menu controversial in UX design?
- **Q11**: CORRECT — What are the four WCAG principles (POUR) and what does each require?
- **Q12**: CORRECT — How does WAI-ARIA complement semantic HTML for web accessibility?
- **Q13**: WRONG — What is the most common cause of screen reader inaccessibility?
  - Expected: Applications failing to comply with accessibility APIs is the single most common cause of screen reader inaccessibility. This breaks the semantic chain between the interface and assistive technology regardless of how well the design system encodes accessibility constraints.
  - Got: Missing alternative text and form labels
- **Q14**: CORRECT — How does progressive enhancement serve as an accessibility strategy?
- **Q15**: CORRECT — What does the WebAIM survey data show about the accessibility training gap?
- **Q16**: CORRECT — What caused the flat design usability crisis and how was it resolved?
- **Q17**: CORRECT — How do grid systems support cognitive load management in web layouts?
- **Q18**: CORRECT — What role does white space play in visual hierarchy according to Gestalt principles?
- **Q19**: CORRECT — How does responsive web design differ from adaptive design?
- **Q20**: WRONG — What is the relationship between color theory and accessibility in web design?
  - Expected: Color theory provides rules for contrast, depth perception (warm colors advance, cool recede), and hue relationships that directly serve accessibility requirements. WCAG contrast ratios translate these perceptual principles into enforceable thresholds. However, color harmony has no universal formula, limiting what can be systematically enforced.
  - Got: Color theory provides the foundational framework for understanding color relationships and contrast, which directly informs accessibility compliance in web design
- **Q21**: CORRECT — What is the difference between heuristic evaluation and cognitive walkthrough?
- **Q22**: CORRECT — How does A/B testing complement qualitative usability testing?
- **Q23**: CORRECT — What is Simpson's paradox and why does it matter for A/B test analysis?
- **Q24**: CORRECT — How does card sorting support information architecture design?
- **Q25**: WRONG — What does eye tracking reveal about user attention and the concept of the fold?
  - Expected: Eye tracking shows significantly more fixation on above-fold content, with studies suggesting an 84% attention differential. However, covert attention (processing without fixation) means fixation maps may overstate the difference, and there is no universal pixel definition for the fold across devices, limiting prescriptive application.
  - Got: Eye tracking reveals that users do scroll and attend to content below the fold when it's relevant and well-presented, largely debunking the myth that all important content must be above the fold.
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
  - Got: Performance and user experience must both be first-class concerns
- **Q36**: CORRECT — How do design systems encode cognitive constraints like Fitts's law and Gestalt principles?
- **Q37**: CORRECT — What is the role of design tokens in enforcing visual standards?
- **Q38**: WRONG — How do design systems relate to ISO 9241 usability standards?
  - Expected: Design systems can implement ISO 9241's three quality dimensions at the component level: dialogue principles map to component behavior patterns, presentation attributes map to visual design rules, and usability factors map to measurable performance targets — making standards compliance systematic rather than ad hoc.
  - Got: Design systems operationalize ISO 9241 usability principles
- **Q39**: WRONG — What historical precedent exists for design system backlash?
  - Expected: The 1980s grid system backlash, driven by perceived dogmatism and corporate association, shows that design enforcement mechanisms can provoke rejection when they convert quality floors into innovation ceilings. Design systems risk the same cycle if they ossify into rigid corporate standards rather than evolving frameworks.
  - Got: Material Design, Flat Design, and Bootstrap homogenization
- **Q40**: CORRECT — How does Material Design address the flat design signifier problem?
- **Q41**: CORRECT — What is Don Norman's affordance-signifier framework and why is it foundational?
- **Q42**: CORRECT — What are Jakob Nielsen's key contributions to usability?
- **Q43**: CORRECT — How did Three Mile Island influence HCI and usability thinking?
- **Q44**: CORRECT — You are reviewing a web application that uses infinite scrolling, hamburger navigation, and auto-playing carousels. What specific UX concerns would you raise?
- **Q45**: WRONG — How would you evaluate whether a design system adequately addresses cognitive load management and accessibility?
  - Expected: Check cognitive load: does it enforce minimum target sizes (Fitts's law), consistent spacing (Gestalt proximity), progressive disclosure patterns, and information hierarchy? Check accessibility: does it encode WCAG contrast ratios in design tokens, provide ARIA patterns in components, support keyboard navigation, and maintain semantic HTML? The gap is usually at the API compliance layer — the design system may specify correctly but applications may implement incorrectly.
  - Got: Conduct multi-method evaluation combining heuristic review, user testing, and automated tools

## Wrong Answers (Detail)

### Q8: What is progressive disclosure and what cognitive principles justify its use?
- **Expected:** Progressive disclosure stages information reveal to show only what is needed at each step. It is justified by working memory limits (reducing visible options reduces extraneous cognitive load), Gestalt grouping (fewer elements create clearer visual hierarchy), and Hick's law (fewer visible choices speed decision-making).
- **Got:** Progressive disclosure is a UX pattern that reveals information and interface elements gradually, showing only what's immediately necessary and hiding advanced options until needed.

**Model response:**

```
```json
{"answer": "Progressive disclosure is a UX pattern that reveals information and interface elements gradually, showing only what's immediately necessary and hiding advanced options until needed.", "explanation": "Progressive disclosure is justified by several cognitive principles, primarily cognitive load theory, which recognizes that working memory has limited capacity (typically 7±2 chunks). By revealing complexity incrementally, progressive disclosure reduces the initial cognitive burden, allowing users to focus on primary tasks without being overwhelmed by all possible options. This aligns with selective attention principles—users can only process limited information simultaneously. The pattern also leverages recognition over recall by presenting options contextually when relevant, making them easier to identify than requiring users to remember what might be available. Additionally, it supports better information processing by chunking complex interfaces into manageable segments, and applies Gestalt principles of figure-ground relationship by making essential elements more prominent through the reduction of visual noise."}
```
```

### Q13: What is the most common cause of screen reader inaccessibility?
- **Expected:** Applications failing to comply with accessibility APIs is the single most common cause of screen reader inaccessibility. This breaks the semantic chain between the interface and assistive technology regardless of how well the design system encodes accessibility constraints.
- **Got:** Missing alternative text and form labels

**Model response:**

```
```json
{"answer": "Missing alternative text and form labels", "explanation": "The most common cause of screen reader inaccessibility is the absence of proper text alternatives for non-text content, particularly missing alt attributes on images and missing or inadequate labels on form inputs. Large-scale accessibility audits consistently show these violations at the top of WCAG failure lists. When images lack alt text, screen reader users miss critical visual information. When form inputs lack proper labels (via <label> elements or aria-label), users cannot determine what information to enter, making forms completely unusable. These issues are pervasive because developers often focus on visual design without considering how assistive technologies interpret content, and automated testing tools can detect but not fix these semantic gaps."}
```
```

### Q20: What is the relationship between color theory and accessibility in web design?
- **Expected:** Color theory provides rules for contrast, depth perception (warm colors advance, cool recede), and hue relationships that directly serve accessibility requirements. WCAG contrast ratios translate these perceptual principles into enforceable thresholds. However, color harmony has no universal formula, limiting what can be systematically enforced.
- **Got:** Color theory provides the foundational framework for understanding color relationships and contrast, which directly informs accessibility compliance in web design

**Model response:**

```
```json
{"answer": "Color theory provides the foundational framework for understanding color relationships and contrast, which directly informs accessibility compliance in web design", "explanation": "Color theory and accessibility are intrinsically linked in web design. Color theory principles—particularly regarding contrast, luminance, and color relationships—form the scientific basis for meeting accessibility standards like WCAG contrast ratios (4.5:1 for normal text, 3:1 for large text). Understanding color theory helps designers create palettes that not only achieve sufficient contrast for users with low vision but also account for color vision deficiencies affecting approximately 8% of men and 0.5% of women. Effective accessible design requires applying color theory to ensure information isn't conveyed by color alone, using complementary colors strategically for emphasis while maintaining readability, and balancing aesthetic harmony with functional contrast requirements that serve all users regardless of visual ability."}
```
```

### Q25: What does eye tracking reveal about user attention and the concept of the fold?
- **Expected:** Eye tracking shows significantly more fixation on above-fold content, with studies suggesting an 84% attention differential. However, covert attention (processing without fixation) means fixation maps may overstate the difference, and there is no universal pixel definition for the fold across devices, limiting prescriptive application.
- **Got:** Eye tracking reveals that users do scroll and attend to content below the fold when it's relevant and well-presented, largely debunking the myth that all important content must be above the fold.

**Model response:**

```
```json
{"answer": "Eye tracking reveals that users do scroll and attend to content below the fold when it's relevant and well-presented, largely debunking the myth that all important content must be above the fold.", "explanation": "Eye tracking studies have demonstrated that the traditional notion of 'the fold' as a hard barrier for user attention is outdated. Research shows that users routinely scroll past the initial viewport when content is engaging, well-structured, and clearly indicates more information below. While the top portion of a page does receive disproportionate attention initially, eye tracking data reveals that users follow visual cues, content hierarchy, and their information needs rather than stopping at an arbitrary fold line. This has shifted design strategy from cramming everything above the fold to creating clear visual flow and content scent that encourages exploration throughout the page."}
```
```

### Q35: What is the dual quality mandate in modern web architecture?
- **Expected:** Modern web architecture has two complementary quality channels: remedial (design systems treating existing design debt, especially in SPAs) and preventive (progressive enhancement eliminating accessibility gaps by starting from an accessible baseline). Together they provide both corrective and preventive quality assurance.
- **Got:** Performance and user experience must both be first-class concerns

**Model response:**

```
```json
{"answer": "Performance and user experience must both be first-class concerns", "explanation": "The dual quality mandate in modern web architecture refers to the requirement that applications must simultaneously deliver both exceptional user experience (rich interactivity, smooth animations, responsive feedback) and exceptional performance (fast load times, minimal time-to-interactive, efficient resource usage). This mandate arose because traditional approaches often sacrificed one for the other—heavy client-side JavaScript frameworks provided great UX but poor initial load performance, while server-rendered pages were fast but less interactive. Modern architectures like SSR/SSG hybrid frameworks, edge computing, and progressive enhancement patterns attempt to satisfy both mandates simultaneously rather than treating them as a tradeoff."}
```
```

### Q38: How do design systems relate to ISO 9241 usability standards?
- **Expected:** Design systems can implement ISO 9241's three quality dimensions at the component level: dialogue principles map to component behavior patterns, presentation attributes map to visual design rules, and usability factors map to measurable performance targets — making standards compliance systematic rather than ad hoc.
- **Got:** Design systems operationalize ISO 9241 usability principles

**Model response:**

```
```json
{"answer": "Design systems operationalize ISO 9241 usability principles", "explanation": "Design systems serve as practical implementations of ISO 9241 usability standards by encoding proven interaction patterns, dialogue principles, and accessibility guidelines into reusable components. ISO 9241 defines usability in terms of effectiveness, efficiency, and satisfaction, while design systems achieve these goals through consistent, well-tested UI elements that embody principles like suitability for task (9241-110), conformity with user expectations, and error tolerance. By standardizing components and documenting usage patterns, design systems help teams consistently apply ISO 9241's human-centered design approach across products, reducing cognitive load and ensuring predictable interactions that meet the standard's ergonomic requirements."}
```
```

### Q39: What historical precedent exists for design system backlash?
- **Expected:** The 1980s grid system backlash, driven by perceived dogmatism and corporate association, shows that design enforcement mechanisms can provoke rejection when they convert quality floors into innovation ceilings. Design systems risk the same cycle if they ossify into rigid corporate standards rather than evolving frameworks.
- **Got:** Material Design, Flat Design, and Bootstrap homogenization

**Model response:**

```
```json
{"answer": "Material Design, Flat Design, and Bootstrap homogenization", "explanation": "The most notable historical precedents include the Material Design backlash (mid-2010s) where critics argued Google's opinionated system caused apps to lose brand identity and look identical; the Flat Design backlash (2013-2015) following iOS 7 and Windows 8, where designers criticized reduced usability and loss of visual affordances; and Bootstrap fatigue (early 2010s) when widespread framework adoption led to cookie-cutter websites. Each case followed a similar pattern: initial enthusiasm for consistency and efficiency, followed by criticism of homogenization, reduced creativity, and loss of brand differentiation. These precedents established a recurring tension in design systems between standardization benefits and the cost of visual monotony."}
```
```

### Q45: How would you evaluate whether a design system adequately addresses cognitive load management and accessibility?
- **Expected:** Check cognitive load: does it enforce minimum target sizes (Fitts's law), consistent spacing (Gestalt proximity), progressive disclosure patterns, and information hierarchy? Check accessibility: does it encode WCAG contrast ratios in design tokens, provide ARIA patterns in components, support keyboard navigation, and maintain semantic HTML? The gap is usually at the API compliance layer — the design system may specify correctly but applications may implement incorrectly.
- **Got:** Conduct multi-method evaluation combining heuristic review, user testing, and automated tools

**Model response:**

```
```json
{"answer": "Conduct multi-method evaluation combining heuristic review, user testing, and automated tools", "explanation": "Evaluate cognitive load by assessing consistency across components, measuring task completion times and error rates, reviewing information hierarchy and progressive disclosure patterns, and testing with users to identify confusion points. For accessibility, combine automated tools (WAVE, axe) to check WCAG compliance, manual testing with screen readers and keyboard navigation, review of ARIA implementation and focus management, contrast ratio verification, and crucially, usability testing with people who use assistive technologies. The design system should provide clear documentation on both aspects, include accessibility annotations in component specs, and demonstrate consistent patterns that reduce cognitive burden while maintaining full accessibility across all interaction modes."}
```
```


## By Objective

- **None**: 37/45 (82%)
