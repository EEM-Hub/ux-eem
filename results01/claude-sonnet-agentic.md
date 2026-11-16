# Exam Results: ux-design.md

**Date:** 2026-06-22 16:06
**Model:** claude:sonnet
**Score:** 39/45 (86%)

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
  - Got: Progressive disclosure is a design pattern that reduces interface complexity by initially presenting only essential features and information, then revealing advanced or rarely-used options on demand via secondary screens or expandable sections. The cognitive principles justifying its use are: (1) Working memory capacity limits (Miller's 7±2 chunks) - humans can only hold limited information simultaneously, and (2) Cognitive Load Theory - specifically that progressive disclosure reduces extraneous cognitive load (the only load type under the designer's direct control) by staging information across interaction steps rather than presenting everything at once. This staged reveal prevents cognitive overload, reduces learning curves, and lowers error rates. The pattern has a complete justification chain from cognitive science: working memory limits necessitate extraneous load reduction, which progressive disclosure achieves through temporal staging of information.
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
- **Q20**: WRONG — What is the relationship between color theory and accessibility in web design?
  - Expected: Color theory provides rules for contrast, depth perception (warm colors advance, cool recede), and hue relationships that directly serve accessibility requirements. WCAG contrast ratios translate these perceptual principles into enforceable thresholds. However, color harmony has no universal formula, limiting what can be systematically enforced.
  - Got: Color theory and accessibility are fundamentally linked through systematic enforcement mechanisms: color theory provides the perceptual science (warm-advance/cool-recede spatial perception, hue-shift effects) that informs visual hierarchy rules, while WCAG standards specify minimum contrast thresholds (4.5:1 for AA compliance), and design tokens systematically enforce both across products. Critically, accessibility requirements mandate that interactive elements like links cannot rely on color alone for differentiation—they require additional visual cues like underlines—because color differentiation is insufficient for color-blind users. This chain from perceptual science through accessibility standards to systematic implementation ensures both aesthetic quality and inclusive access.
- **Q21**: WRONG — What is the difference between heuristic evaluation and cognitive walkthrough?
  - Expected: Heuristic evaluation has experts inspect an interface against established usability principles (like Nielsen's 10 heuristics) to identify violations broadly. Cognitive walkthrough focuses specifically on learnability by having evaluators step through tasks from a new user's perspective, checking whether the correct action is obvious at each step.
  - Got: {"tool": "search_beliefs", "query": "cognitive walkthrough"}

Tool result:
Cognitive walkthroughs ar
- **Q22**: CORRECT — How does A/B testing complement qualitative usability testing?
- **Q23**: CORRECT — What is Simpson's paradox and why does it matter for A/B test analysis?
- **Q24**: CORRECT — How does card sorting support information architecture design?
- **Q25**: WRONG — What does eye tracking reveal about user attention and the concept of the fold?
  - Expected: Eye tracking shows significantly more fixation on above-fold content, with studies suggesting an 84% attention differential. However, covert attention (processing without fixation) means fixation maps may overstate the difference, and there is no universal pixel definition for the fold across devices, limiting prescriptive application.
  - Got: Eye tracking reveals an 84% attention differential favoring above-fold content, with 77% of users not scrolling below the fold
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
- **Q39**: CORRECT — What historical precedent exists for design system backlash?
- **Q40**: CORRECT — How does Material Design address the flat design signifier problem?
- **Q41**: WRONG — What is Don Norman's affordance-signifier framework and why is it foundational?
  - Expected: Norman distinguished affordances (what an object allows) from signifiers (what communicates how to use it). This framework is foundational because it explains both design successes (clear signifiers enable correct mental models) and failures (removed signifiers cause the flat design crisis), providing both descriptive and prescriptive power.
  - Got: Don Norman's affordance-signifier framework distinguishes between affordances (what actions are possible) and signifiers (what communicates where and how to act). It is foundational because it provides HCI's central explanatory framework for both design success and failure, achieving convergent validity through empirical crisis origin (TMI investigation), predictive success (explaining flat design's 22% degradation), and prescriptive adoption into design systems. The framework evolved from Gibson's ecological perception through Norman's 1988 HCI adaptation to the 2013 signifier distinction, creating a complete theory that explains WHY designs fail and HOW to prevent it.
- **Q42**: CORRECT — What are Jakob Nielsen's key contributions to usability?
- **Q43**: CORRECT — How did Three Mile Island influence HCI and usability thinking?
- **Q44**: CORRECT — You are reviewing a web application that uses infinite scrolling, hamburger navigation, and auto-playing carousels. What specific UX concerns would you raise?
- **Q45**: WRONG — How would you evaluate whether a design system adequately addresses cognitive load management and accessibility?
  - Expected: Check cognitive load: does it enforce minimum target sizes (Fitts's law), consistent spacing (Gestalt proximity), progressive disclosure patterns, and information hierarchy? Check accessibility: does it encode WCAG contrast ratios in design tokens, provide ARIA patterns in components, support keyboard navigation, and maintain semantic HTML? The gap is usually at the API compliance layer — the design system may specify correctly but applications may implement incorrectly.
  - Got: Verify triple-channel enforcement: (1) spatial - grid systems with Gestalt-compliant spacing for chunking within 7±2 items and WCAG reflow at 320px; (2) perceptual-motor - Fitts's law target sizing (44×44px minimum), contrast ratios, and progressive disclosure patterns; (3) semantic - ARIA implementation verified with assistive technology, not visual inspection alone. Validate coverage across all five disability categories and confirm WCAG compliance across measurable success criteria.

## Wrong Answers (Detail)

### Q8: What is progressive disclosure and what cognitive principles justify its use?
- **Expected:** Progressive disclosure stages information reveal to show only what is needed at each step. It is justified by working memory limits (reducing visible options reduces extraneous cognitive load), Gestalt grouping (fewer elements create clearer visual hierarchy), and Hick's law (fewer visible choices speed decision-making).
- **Got:** Progressive disclosure is a design pattern that reduces interface complexity by initially presenting only essential features and information, then revealing advanced or rarely-used options on demand via secondary screens or expandable sections. The cognitive principles justifying its use are: (1) Working memory capacity limits (Miller's 7±2 chunks) - humans can only hold limited information simultaneously, and (2) Cognitive Load Theory - specifically that progressive disclosure reduces extraneous cognitive load (the only load type under the designer's direct control) by staging information across interaction steps rather than presenting everything at once. This staged reveal prevents cognitive overload, reduces learning curves, and lowers error rates. The pattern has a complete justification chain from cognitive science: working memory limits necessitate extraneous load reduction, which progressive disclosure achieves through temporal staging of information.

**Model response:**

```
Progressive disclosure is a foundational UX pattern with rigorous cognitive grounding. By initially hiding secondary or advanced features and revealing them only on user demand, it directly addresses working memory constraints identified in Miller's Law. The pattern specifically targets extraneous cognitive load - the aspect of cognitive burden that designers can control through presentation choices - making it scientifically superior to alternatives like modal dialogs that increase load. The canonical example is the macOS print dialog, which shows basic options by default with a 'Show Details' button for advanced settings. This approach achieves dual benefits: easier learning for novices (reduced cognitive overload) and fewer errors (by preventing information overwhelm), with the complete theoretical chain making it one of the most thoroughly justified patterns in UX design.
```

### Q20: What is the relationship between color theory and accessibility in web design?
- **Expected:** Color theory provides rules for contrast, depth perception (warm colors advance, cool recede), and hue relationships that directly serve accessibility requirements. WCAG contrast ratios translate these perceptual principles into enforceable thresholds. However, color harmony has no universal formula, limiting what can be systematically enforced.
- **Got:** Color theory and accessibility are fundamentally linked through systematic enforcement mechanisms: color theory provides the perceptual science (warm-advance/cool-recede spatial perception, hue-shift effects) that informs visual hierarchy rules, while WCAG standards specify minimum contrast thresholds (4.5:1 for AA compliance), and design tokens systematically enforce both across products. Critically, accessibility requirements mandate that interactive elements like links cannot rely on color alone for differentiation—they require additional visual cues like underlines—because color differentiation is insufficient for color-blind users. This chain from perceptual science through accessibility standards to systematic implementation ensures both aesthetic quality and inclusive access.

**Model response:**

```
The belief database reveals that color theory and accessibility form a complete implementation chain in web design. Color theory's perceptual science provides specific, enforceable rules (warm colors advance for foreground/interactive elements, cool colors recede for backgrounds), WCAG standards establish minimum contrast ratios (4.5:1 for AA compliance), and design tokens provide the systematic mechanism to enforce both throughout an application. A critical accessibility principle found in the database is that links and interactive elements must be distinguished by more than color alone—requiring underlines or other visual cues—because color differentiation fails for color-blind users. This represents the convergence point where flat design's signifier crisis intersects accessibility requirements, as both demand the same visual cues that flat design tends to strip away. The relationship is thus complementary and mutually reinforcing: color theory specifies what color rules must achieve visually, accessibility standards provide minimum thresholds, and design systems encode both as component-level requirements.
```

### Q21: What is the difference between heuristic evaluation and cognitive walkthrough?
- **Expected:** Heuristic evaluation has experts inspect an interface against established usability principles (like Nielsen's 10 heuristics) to identify violations broadly. Cognitive walkthrough focuses specifically on learnability by having evaluators step through tasks from a new user's perspective, checking whether the correct action is obvious at each step.
- **Got:** {"tool": "search_beliefs", "query": "cognitive walkthrough"}

Tool result:
Cognitive walkthroughs ar

**Model response:**

```

```

### Q25: What does eye tracking reveal about user attention and the concept of the fold?
- **Expected:** Eye tracking shows significantly more fixation on above-fold content, with studies suggesting an 84% attention differential. However, covert attention (processing without fixation) means fixation maps may overstate the difference, and there is no universal pixel definition for the fold across devices, limiting prescriptive application.
- **Got:** Eye tracking reveals an 84% attention differential favoring above-fold content, with 77% of users not scrolling below the fold

**Model response:**

```
Eye tracking studies measure fixations (brief pauses where users process information) and have empirically validated that above-the-fold content receives 84% more user attention than below-the-fold content (NNgroup research), and that 77% of website visitors do not scroll below the fold (Nielsen 2006). This attention differential is grounded in the eye-mind hypothesis (Just & Carpenter 1980) which posits that fixated content corresponds to cognitive processing. However, a critical limitation is that 'the fold' has no universal pixel definition—it varies by screen resolution, browser window size, and responsive layout behavior—meaning fold-based design prescriptions must adapt dynamically per viewport rather than follow fixed spatial rules.
```

### Q41: What is Don Norman's affordance-signifier framework and why is it foundational?
- **Expected:** Norman distinguished affordances (what an object allows) from signifiers (what communicates how to use it). This framework is foundational because it explains both design successes (clear signifiers enable correct mental models) and failures (removed signifiers cause the flat design crisis), providing both descriptive and prescriptive power.
- **Got:** Don Norman's affordance-signifier framework distinguishes between affordances (what actions are possible) and signifiers (what communicates where and how to act). It is foundational because it provides HCI's central explanatory framework for both design success and failure, achieving convergent validity through empirical crisis origin (TMI investigation), predictive success (explaining flat design's 22% degradation), and prescriptive adoption into design systems. The framework evolved from Gibson's ecological perception through Norman's 1988 HCI adaptation to the 2013 signifier distinction, creating a complete theory that explains WHY designs fail and HOW to prevent it.

**Model response:**

```
The affordance-signifier framework is foundational to UX design because it represents HCI's central explanatory and prescriptive theory. It achieves dual meta-validation: internal validation through convergent validity (empirical origin in catastrophic failure investigation like Three Mile Island, predictive success in explaining subsequent crises like flat design's measurable 22% performance degradation, and prescriptive adoption into design systems as component-level rules), and external validation through empirical crises confirming its predictive power. The framework is unique in serving both diagnostic and prescriptive roles—explaining why specific designs fail while defining how the field should respond. Together with information theory (which predicts quantitative performance), affordance theory addresses the qualitative perceptual dimension of interaction, making it one of HCI's dual analytical pillars.
```

### Q45: How would you evaluate whether a design system adequately addresses cognitive load management and accessibility?
- **Expected:** Check cognitive load: does it enforce minimum target sizes (Fitts's law), consistent spacing (Gestalt proximity), progressive disclosure patterns, and information hierarchy? Check accessibility: does it encode WCAG contrast ratios in design tokens, provide ARIA patterns in components, support keyboard navigation, and maintain semantic HTML? The gap is usually at the API compliance layer — the design system may specify correctly but applications may implement incorrectly.
- **Got:** Verify triple-channel enforcement: (1) spatial - grid systems with Gestalt-compliant spacing for chunking within 7±2 items and WCAG reflow at 320px; (2) perceptual-motor - Fitts's law target sizing (44×44px minimum), contrast ratios, and progressive disclosure patterns; (3) semantic - ARIA implementation verified with assistive technology, not visual inspection alone. Validate coverage across all five disability categories and confirm WCAG compliance across measurable success criteria.

**Model response:**

```
Design systems manage cognitive load and accessibility through substantially overlapping mechanisms encoded in three independent enforcement channels. Evaluation requires checking spatial implementation (white-space tokens maintaining Gestalt proximity thresholds of ~1.5× object height, fluid grids supporting reflow), perceptual-motor constraints (minimum target sizes, contrast ratios, chunking aligned with working memory's 7±2 capacity), and semantic accessibility (ARIA rules that modify the accessibility tree invisibly). Because ARIA compliance cannot be verified through visual inspection, assistive technology testing is mandatory. The evaluation should confirm coverage across visual, motor, auditory, seizure, and cognitive disability categories, with recognition that the cognitive category has inherent tensions between novice and expert needs. WCAG serves as the unified compliance framework providing measurable success criteria (contrast ratios, reflow behavior, target sizes) that bridge both visual and semantic enforcement channels.
```


## By Objective

- **None**: 39/45 (86%)
