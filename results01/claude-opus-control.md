# Exam Results: ux-design.md

**Date:** 2026-06-22 14:29
**Model:** claude:opus
**Score:** 43/45 (95%)

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
  - Got: Missing or improper alternative text for non-text content
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
- **Q35**: CORRECT — What is the dual quality mandate in modern web architecture?
- **Q36**: CORRECT — How do design systems encode cognitive constraints like Fitts's law and Gestalt principles?
- **Q37**: CORRECT — What is the role of design tokens in enforcing visual standards?
- **Q38**: CORRECT — How do design systems relate to ISO 9241 usability standards?
- **Q39**: WRONG — What historical precedent exists for design system backlash?
  - Expected: The 1980s grid system backlash, driven by perceived dogmatism and corporate association, shows that design enforcement mechanisms can provoke rejection when they convert quality floors into innovation ceilings. Design systems risk the same cycle if they ossify into rigid corporate standards rather than evolving frameworks.
  - Got: Multiple historical precedents exist, most notably the backlash against Microsoft's Metro/Modern UI (2012), Apple's iOS 7 flat design shift (2013), Google's early Material Design rigidity (2014), and broader 'design system fatigue' discussions (2018-present).
- **Q40**: CORRECT — How does Material Design address the flat design signifier problem?
- **Q41**: CORRECT — What is Don Norman's affordance-signifier framework and why is it foundational?
- **Q42**: CORRECT — What are Jakob Nielsen's key contributions to usability?
- **Q43**: CORRECT — How did Three Mile Island influence HCI and usability thinking?
- **Q44**: CORRECT — You are reviewing a web application that uses infinite scrolling, hamburger navigation, and auto-playing carousels. What specific UX concerns would you raise?
- **Q45**: CORRECT — How would you evaluate whether a design system adequately addresses cognitive load management and accessibility?

## Wrong Answers (Detail)

### Q13: What is the most common cause of screen reader inaccessibility?
- **Expected:** Applications failing to comply with accessibility APIs is the single most common cause of screen reader inaccessibility. This breaks the semantic chain between the interface and assistive technology regardless of how well the design system encodes accessibility constraints.
- **Got:** Missing or improper alternative text for non-text content

**Model response:**

```
{"answer": "Missing or improper alternative text for non-text content", "explanation": "The most common cause of screen reader inaccessibility is missing or improper alternative text (alt text) for non-text content such as images, icons, buttons, and other visual elements. When images lack alt attributes or have meaningless alt text (like 'image1.jpg' or empty strings on informative images), screen readers either skip the content entirely or announce unhelpful information, leaving users unable to understand the page. This is consistently identified as the most prevalent accessibility issue in studies like the WebAIM Million annual analysis, which surveys the top million homepages and repeatedly finds missing alternative text among the most detected WCAG failures. While other issues like missing form labels, poor heading structure, and insufficient color contrast are also widespread, missing alt text remains the single most pervasive barrier because it affects the most fundamental aspect of web content comprehension for screen reader users — understanding what visual content conveys."}
```

### Q39: What historical precedent exists for design system backlash?
- **Expected:** The 1980s grid system backlash, driven by perceived dogmatism and corporate association, shows that design enforcement mechanisms can provoke rejection when they convert quality floors into innovation ceilings. Design systems risk the same cycle if they ossify into rigid corporate standards rather than evolving frameworks.
- **Got:** Multiple historical precedents exist, most notably the backlash against Microsoft's Metro/Modern UI (2012), Apple's iOS 7 flat design shift (2013), Google's early Material Design rigidity (2014), and broader 'design system fatigue' discussions (2018-present).

**Model response:**

```
```json
{"answer": "Multiple historical precedents exist, most notably the backlash against Microsoft's Metro/Modern UI (2012), Apple's iOS 7 flat design shift (2013), Google's early Material Design rigidity (2014), and broader 'design system fatigue' discussions (2018-present).", "explanation": "The most well-documented backlash occurred when Microsoft introduced Metro UI with Windows 8 in 2012, which removed familiar desktop metaphors and imposed a touch-first tile interface on desktop users, leading to significant user revolt and contributing to Windows 8's poor reception. Apple's iOS 7 (2013) drew intense criticism when Jony Ive replaced the skeuomorphic design language users had grown attached to with a stark flat aesthetic, prompting accessibility complaints and disorientation among longtime users. Google's Material Design, while broadly praised, faced criticism for making Android apps feel homogeneous and 'same-y,' leading Google to later introduce Material You with more customization options. More broadly, the design systems movement itself has faced recurring backlash: designers have pushed back against overly rigid component libraries that constrain creativity, criticized the 'boring design' that emerges when every product uses the same system, and questioned whether design systems prioritize engineering efficiency over user experience and brand differentiation. The Bootstrap era (2012-2016) is another precedent, where the web was criticized for every site looking identical. These precedents suggest that design system backlash follows a predictable cycle: adoption for efficiency, over-standardization, creative frustration, and eventual loosening or rebellion toward more expressive approaches."}
```
```


## By Objective

- **None**: 43/45 (95%)
