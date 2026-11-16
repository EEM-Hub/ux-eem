# Exam Results: ux-design.md

**Date:** 2026-06-23 08:32
**Model:** claude:opus
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
  - Got: Missing or improper alternative text for images and missing semantic HTML markup
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
  - Got: Eye tracking reveals that users do look below the fold, but attention is disproportionately concentrated above it.
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
  - Got: The dual quality mandate in modern web architecture refers to the requirement that web applications must simultaneously satisfy two distinct quality dimensions: developer experience (DX) and user experience (UX). On the developer side, the architecture must support maintainability, testability, modularity, and efficient workflows — enabling teams to build, iterate, and ship reliably. On the user side, the same architecture must deliver fast load times, accessibility, responsive interactions, and intuitive interfaces. These two mandates often create tension: abstractions that improve DX (heavy frameworks, deep component hierarchies, build-time tooling) can degrade UX (larger bundles, slower rendering, accessibility gaps), and vice versa. Modern web architecture patterns — such as server components, progressive enhancement, islands architecture, and edge rendering — attempt to resolve this tension by shifting complexity to the build or server layer so that developer ergonomics and end-user performance are both preserved. The dual mandate means that architectural decisions cannot optimize for only one audience; every choice must be evaluated against both the team that maintains the system and the people who use it.
- **Q36**: CORRECT — How do design systems encode cognitive constraints like Fitts's law and Gestalt principles?
- **Q37**: CORRECT — What is the role of design tokens in enforcing visual standards?
- **Q38**: CORRECT — How do design systems relate to ISO 9241 usability standards?
- **Q39**: WRONG — What historical precedent exists for design system backlash?
  - Expected: The 1980s grid system backlash, driven by perceived dogmatism and corporate association, shows that design enforcement mechanisms can provoke rejection when they convert quality floors into innovation ceilings. Design systems risk the same cycle if they ossify into rigid corporate standards rather than evolving frameworks.
  - Got: Multiple historical precedents exist, most notably the backlash against Google's Material Design (2014-onwards) and Apple's iOS 7 flat design transition (2013).
- **Q40**: CORRECT — How does Material Design address the flat design signifier problem?
- **Q41**: CORRECT — What is Don Norman's affordance-signifier framework and why is it foundational?
- **Q42**: CORRECT — What are Jakob Nielsen's key contributions to usability?
- **Q43**: CORRECT — How did Three Mile Island influence HCI and usability thinking?
- **Q44**: CORRECT — You are reviewing a web application that uses infinite scrolling, hamburger navigation, and auto-playing carousels. What specific UX concerns would you raise?
- **Q45**: CORRECT — How would you evaluate whether a design system adequately addresses cognitive load management and accessibility?

## Wrong Answers (Detail)

### Q13: What is the most common cause of screen reader inaccessibility?
- **Expected:** Applications failing to comply with accessibility APIs is the single most common cause of screen reader inaccessibility. This breaks the semantic chain between the interface and assistive technology regardless of how well the design system encodes accessibility constraints.
- **Got:** Missing or improper alternative text for images and missing semantic HTML markup

**Model response:**

```
{"answer": "Missing or improper alternative text for images and missing semantic HTML markup", "explanation": "The most common cause of screen reader inaccessibility is the absence of proper semantic markup and alternative text. This encompasses several related issues: images without alt attributes (or with meaningless alt text like 'image1.jpg'), interactive elements built from non-semantic elements like <div> and <span> instead of native HTML controls (<button>, <a>, <input>), missing form labels, and lack of proper heading hierarchy. Among these, missing alternative text on images is consistently cited as the single most prevalent accessibility failure in web content audits such as the WebAIM Million report. When screen readers encounter an image without alt text, users either hear nothing or hear the raw filename, losing critical information. Combined with the widespread use of <div onclick> instead of <button>, missing ARIA labels, and poor document structure, these semantic markup failures account for the majority of screen reader accessibility barriers on the web."}
```

### Q25: What does eye tracking reveal about user attention and the concept of the fold?
- **Expected:** Eye tracking shows significantly more fixation on above-fold content, with studies suggesting an 84% attention differential. However, covert attention (processing without fixation) means fixation maps may overstate the difference, and there is no universal pixel definition for the fold across devices, limiting prescriptive application.
- **Got:** Eye tracking reveals that users do look below the fold, but attention is disproportionately concentrated above it.

**Model response:**

```
```json
{"answer": "Eye tracking reveals that users do look below the fold, but attention is disproportionately concentrated above it.", "explanation": "Eye tracking studies, notably those by the Nielsen Norman Group, consistently show that users spend roughly 57–80% of their viewing time on content above the fold, with attention declining sharply as they scroll down. However, the data also debunks the myth that users never scroll — they do, especially when visual cues (like partially visible content) signal that more information exists below. Eye tracking heatmaps reveal an F-shaped or layer-cake scanning pattern where the top of the page receives the densest fixations, but engaged users will scroll if the above-fold content establishes relevance and motivation. The key design implication is not to cram everything above the fold, but rather to place the most critical content and strongest value propositions there to hook attention, while designing clear visual continuity that encourages scrolling. Eye tracking also shows that arbitrary fold-line cutoffs matter less on modern devices with varied viewport sizes — what matters more is the information scent and visual hierarchy that guides the user's gaze progressively down the page."}
```
```

### Q35: What is the dual quality mandate in modern web architecture?
- **Expected:** Modern web architecture has two complementary quality channels: remedial (design systems treating existing design debt, especially in SPAs) and preventive (progressive enhancement eliminating accessibility gaps by starting from an accessible baseline). Together they provide both corrective and preventive quality assurance.
- **Got:** The dual quality mandate in modern web architecture refers to the requirement that web applications must simultaneously satisfy two distinct quality dimensions: developer experience (DX) and user experience (UX). On the developer side, the architecture must support maintainability, testability, modularity, and efficient workflows — enabling teams to build, iterate, and ship reliably. On the user side, the same architecture must deliver fast load times, accessibility, responsive interactions, and intuitive interfaces. These two mandates often create tension: abstractions that improve DX (heavy frameworks, deep component hierarchies, build-time tooling) can degrade UX (larger bundles, slower rendering, accessibility gaps), and vice versa. Modern web architecture patterns — such as server components, progressive enhancement, islands architecture, and edge rendering — attempt to resolve this tension by shifting complexity to the build or server layer so that developer ergonomics and end-user performance are both preserved. The dual mandate means that architectural decisions cannot optimize for only one audience; every choice must be evaluated against both the team that maintains the system and the people who use it.

**Model response:**

```
{"answer": "The dual quality mandate in modern web architecture refers to the requirement that web applications must simultaneously satisfy two distinct quality dimensions: developer experience (DX) and user experience (UX). On the developer side, the architecture must support maintainability, testability, modularity, and efficient workflows — enabling teams to build, iterate, and ship reliably. On the user side, the same architecture must deliver fast load times, accessibility, responsive interactions, and intuitive interfaces. These two mandates often create tension: abstractions that improve DX (heavy frameworks, deep component hierarchies, build-time tooling) can degrade UX (larger bundles, slower rendering, accessibility gaps), and vice versa. Modern web architecture patterns — such as server components, progressive enhancement, islands architecture, and edge rendering — attempt to resolve this tension by shifting complexity to the build or server layer so that developer ergonomics and end-user performance are both preserved. The dual mandate means that architectural decisions cannot optimize for only one audience; every choice must be evaluated against both the team that maintains the system and the people who use it."}
```

### Q39: What historical precedent exists for design system backlash?
- **Expected:** The 1980s grid system backlash, driven by perceived dogmatism and corporate association, shows that design enforcement mechanisms can provoke rejection when they convert quality floors into innovation ceilings. Design systems risk the same cycle if they ossify into rigid corporate standards rather than evolving frameworks.
- **Got:** Multiple historical precedents exist, most notably the backlash against Google's Material Design (2014-onwards) and Apple's iOS 7 flat design transition (2013).

**Model response:**

```
```json
{"answer": "Multiple historical precedents exist, most notably the backlash against Google's Material Design (2014-onwards) and Apple's iOS 7 flat design transition (2013).", "explanation": "The most prominent historical precedent for design system backlash is the widespread criticism of Google's Material Design, which after its 2014 introduction led to complaints that apps across the Android ecosystem looked indistinguishable, stifling brand identity and creative expression — critics dubbed it 'Material Monotony.' Similarly, Apple's abrupt shift from skeuomorphic to flat design in iOS 7 (2013) generated significant backlash from designers and users who felt the new aesthetic sacrificed usability cues (affordances like buttons that looked tappable) for visual minimalism. IBM's Carbon Design System and Salesforce's Lightning Design System have also faced internal resistance from product teams who felt constrained by rigid component libraries that couldn't accommodate edge cases. More broadly, the Bootstrap era (2011-2016) created a well-documented phenomenon where countless websites looked nearly identical, prompting a counter-movement toward custom design and the coining of terms like 'Bootstrap sites' as a pejorative. These backlashes typically follow a pattern: a design system gains adoption for its consistency and efficiency benefits, reaches a tipping point where uniformity becomes perceived as homogeneity, and then faces pushback demanding more flexibility, theming capabilities, or escape hatches for brand differentiation. The tension between consistency (which design systems optimize for) and distinctiveness (which brands and designers value) is a recurring cycle in the history of design standardization."}
```
```


## By Objective

- **None**: 41/45 (91%)
