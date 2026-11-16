# Exam Results: ux-design.md

**Date:** 2026-06-23 10:25
**Model:** claude:sonnet
**Score:** 36/45 (80%)

## Per-Question Results

- **Q1**: WRONG — What is Fitts's law and how does it apply to web UI design?
  - Expected: Fitts's law states that the time to reach a target is a function of the distance to and size of the target. In web UI, it means interactive elements should be large enough and positioned to minimize movement distance — edge and corner positions are advantageous because the screen edge acts as an infinitely large target.
  - Got: {"tool": "search_beliefs", "query": "Fitts's law"}
{"tool": "search_beliefs", "query": "Fitts law UI
- **Q2**: CORRECT — How does Hick's law relate to information architecture and navigation design?
- **Q3**: CORRECT — Explain the expertise reversal effect and its implications for progressive disclosure in web interfaces.
- **Q4**: CORRECT — How do Gestalt principles of proximity and similarity apply to visual hierarchy in web layouts?
- **Q5**: CORRECT — What is cognitive load theory and how do its three types map to UI design decisions?
- **Q6**: CORRECT — What are the usability problems with carousels in web design?
- **Q7**: CORRECT — When is infinite scrolling appropriate versus pagination?
- **Q8**: WRONG — What is progressive disclosure and what cognitive principles justify its use?
  - Expected: Progressive disclosure stages information reveal to show only what is needed at each step. It is justified by working memory limits (reducing visible options reduces extraneous cognitive load), Gestalt grouping (fewer elements create clearer visual hierarchy), and Hick's law (fewer visible choices speed decision-making).
  - Got: a
- **Q9**: WRONG — What are the usability concerns with modal windows?
  - Expected: Modal windows block interaction with the underlying page, disrupting user flow and potentially causing loss of context. They can trap keyboard focus creating accessibility problems, they interrupt task completion, and on mobile they often have dismiss targets that are too small to tap reliably.
  - Got: Modal dialogs fail across three independent dimensions: cognitive (habituation causes dismissal without reading, covering needed content creates self-defeating information blocking), security (focus-stealing intercepts input intended for other programs), and load management (split-attention effect from separating related information across modal and parent).
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
  - Got: Color theory and accessibility in web design are interconnected through a science-to-implementation chain: color theory's perceptual science (warm-advance/cool-recede spatial perception, hue-shift effects) provides the foundational understanding of how users perceive color visually, WCAG standards translate this into enforceable minimum contrast requirements (4.5:1 for AA compliance), and design tokens systematically implement both across entire applications. This relationship ensures that color choices serve both aesthetic hierarchy (warm colors for interactive elements, cool for backgrounds) and functional accessibility (sufficient contrast for signifier visibility), making color decisions simultaneously a design system enforcement mechanism and an accessibility compliance requirement. The convergence means that proper color implementation addresses visual cognition constraints while meeting legal accessibility mandates.
- **Q21**: CORRECT — What is the difference between heuristic evaluation and cognitive walkthrough?
- **Q22**: CORRECT — How does A/B testing complement qualitative usability testing?
- **Q23**: CORRECT — What is Simpson's paradox and why does it matter for A/B test analysis?
- **Q24**: CORRECT — How does card sorting support information architecture design?
- **Q25**: WRONG — What does eye tracking reveal about user attention and the concept of the fold?
  - Expected: Eye tracking shows significantly more fixation on above-fold content, with studies suggesting an 84% attention differential. However, covert attention (processing without fixation) means fixation maps may overstate the difference, and there is no universal pixel definition for the fold across devices, limiting prescriptive application.
  - Got: Eye tracking reveals that user attention is heavily concentrated above the fold, with an 84% attention differential between above-fold and below-fold content, and validates that 77% of users do not scroll below the fold. This is because most visual information processing occurs during fixations (brief pauses on specific points), and above-fold content receives significantly more fixations than below-fold content. These findings empirically validate that the fold concept—originally from print newspaper layout—remains highly relevant in web design, as it marks a critical boundary where user attention and information processing drop dramatically.
- **Q26**: CORRECT — What is user-centered design and what are its core principles?
- **Q27**: CORRECT — How do personas help close the mental-model gap between designers and users?
- **Q28**: CORRECT — What role do wireframes play in the UX design process?
- **Q29**: CORRECT — What is a design system and how does it differ from a style guide?
- **Q30**: CORRECT — How does design thinking's abductive reasoning approach apply to wicked problems in UX?
- **Q31**: CORRECT — What UX challenges do single-page applications introduce?
- **Q32**: WRONG — How do progressive web apps balance capabilities with accessibility?
  - Expected: PWAs use web standards (service workers, manifests) to provide native-like capabilities (offline access, push notifications, home screen installation) while maintaining the web's inherent accessibility advantages — URL addressability, progressive enhancement, and standards-based rendering.
  - Got: PWAs gain native-like capabilities (offline support, push notifications, hardware access) but inherit SPA design debt through the App Shell Model, creating accessibility challenges including broken platform defaults, signifier degradation, and performance-driven minimalism. The balance is problematic - advanced capabilities come at the cost of compounded accessibility barriers, especially when combined with patterns like infinite scrolling.
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
  - Got: {"tool": "search_beliefs", "query": "what users perceive communication"}

Tool result:
Don Norman de
- **Q42**: WRONG — What are Jakob Nielsen's key contributions to usability?
  - Expected: Nielsen established usability as a systematic discipline through his 10 usability heuristics, the discount usability engineering methodology (including the finding that 5 users reveal ~85% of usability problems), founding the Nielsen Norman Group with Don Norman, and decades of evidence-based usability research and advocacy.
  - Got: Nielsen's 10 usability heuristics and heuristic evaluation methodology
- **Q43**: CORRECT — How did Three Mile Island influence HCI and usability thinking?
- **Q44**: CORRECT — You are reviewing a web application that uses infinite scrolling, hamburger navigation, and auto-playing carousels. What specific UX concerns would you raise?
- **Q45**: WRONG — How would you evaluate whether a design system adequately addresses cognitive load management and accessibility?
  - Expected: Check cognitive load: does it enforce minimum target sizes (Fitts's law), consistent spacing (Gestalt proximity), progressive disclosure patterns, and information hierarchy? Check accessibility: does it encode WCAG contrast ratios in design tokens, provide ARIA patterns in components, support keyboard navigation, and maintain semantic HTML? The gap is usually at the API compliance layer — the design system may specify correctly but applications may implement incorrectly.
  - Got: Multi-granularity evaluation combining expert inspection (heuristic evaluation, cognitive walkthroughs), empirical user testing, and WCAG compliance verification across both visual and semantic (ARIA) layers

## Wrong Answers (Detail)

### Q1: What is Fitts's law and how does it apply to web UI design?
- **Expected:** Fitts's law states that the time to reach a target is a function of the distance to and size of the target. In web UI, it means interactive elements should be large enough and positioned to minimize movement distance — edge and corner positions are advantageous because the screen edge acts as an infinitely large target.
- **Got:** {"tool": "search_beliefs", "query": "Fitts's law"}
{"tool": "search_beliefs", "query": "Fitts law UI

**Model response:**

```

```

### Q8: What is progressive disclosure and what cognitive principles justify its use?
- **Expected:** Progressive disclosure stages information reveal to show only what is needed at each step. It is justified by working memory limits (reducing visible options reduces extraneous cognitive load), Gestalt grouping (fewer elements create clearer visual hierarchy), and Hick's law (fewer visible choices speed decision-making).
- **Got:** a

**Model response:**

```
Progressive disclosure is justified by working memory limits (Miller's 7±2 chunks) and cognitive load theory. By staging information revelation, it reduces extraneous cognitive load—the only load type under designer control—which leads to easier learning (reduced learning curve) and fewer errors (lower error rates by preventing cognitive overload). The technique addresses the fundamental constraint that users can only process limited information simultaneously, so hiding secondary content until needed reduces cognitive burden while maintaining access to advanced functionality when required. This creates a complete justification chain from cognitive science (working memory constraints) through load taxonomy (extraneous load reduction) to design technique (staged reveal).
```

### Q9: What are the usability concerns with modal windows?
- **Expected:** Modal windows block interaction with the underlying page, disrupting user flow and potentially causing loss of context. They can trap keyboard focus creating accessibility problems, they interrupt task completion, and on mobile they often have dismiss targets that are too small to tap reliably.
- **Got:** Modal dialogs fail across three independent dimensions: cognitive (habituation causes dismissal without reading, covering needed content creates self-defeating information blocking), security (focus-stealing intercepts input intended for other programs), and load management (split-attention effect from separating related information across modal and parent).

**Model response:**

```
The belief database identifies modal windows as having pervasive, structurally independent failure modes. Cognitively, users become habituated to modals and dismiss them reflexively without reading, and modals can cover information needed to complete their own input fields or block clipboard operations. From a security perspective, modals can steal focus and intercept keyboard/mouse input intended for other programs, creating privacy and security risks. From a cognitive load perspective, modals violate spatial integration principles by separating related information between the modal and parent window, increasing extraneous cognitive load through the split-attention effect. These three failure dimensions are independent and reinforce each other, making modals one of the most thoroughly evidence-rejected common UI patterns. The database notes that usability experts recommend undo-based progressive disclosure as the theoretically grounded alternative to modal confirmation dialogs.
```

### Q20: What is the relationship between color theory and accessibility in web design?
- **Expected:** Color theory provides rules for contrast, depth perception (warm colors advance, cool recede), and hue relationships that directly serve accessibility requirements. WCAG contrast ratios translate these perceptual principles into enforceable thresholds. However, color harmony has no universal formula, limiting what can be systematically enforced.
- **Got:** Color theory and accessibility in web design are interconnected through a science-to-implementation chain: color theory's perceptual science (warm-advance/cool-recede spatial perception, hue-shift effects) provides the foundational understanding of how users perceive color visually, WCAG standards translate this into enforceable minimum contrast requirements (4.5:1 for AA compliance), and design tokens systematically implement both across entire applications. This relationship ensures that color choices serve both aesthetic hierarchy (warm colors for interactive elements, cool for backgrounds) and functional accessibility (sufficient contrast for signifier visibility), making color decisions simultaneously a design system enforcement mechanism and an accessibility compliance requirement. The convergence means that proper color implementation addresses visual cognition constraints while meeting legal accessibility mandates.

**Model response:**

```
The beliefs reveal that color theory completes the visual cognition chain in design systems by providing specific, enforceable rules: warm-advance/cool-recede for spatial hierarchy, hue-shift awareness for accessible darkening, and contrast ratios for signifier visibility. These color principles are systematically enforced through design tokens that encode WCAG AA 4.5:1 contrast requirements, creating a chain from perceptual science through accessibility standards to implementation. This makes color theory not just an aesthetic concern but a core component of the accessibility enforcement architecture, where design systems use color rules to ensure interfaces are both visually hierarchical and accessible across disability categories, particularly for visual impairments.
```

### Q25: What does eye tracking reveal about user attention and the concept of the fold?
- **Expected:** Eye tracking shows significantly more fixation on above-fold content, with studies suggesting an 84% attention differential. However, covert attention (processing without fixation) means fixation maps may overstate the difference, and there is no universal pixel definition for the fold across devices, limiting prescriptive application.
- **Got:** Eye tracking reveals that user attention is heavily concentrated above the fold, with an 84% attention differential between above-fold and below-fold content, and validates that 77% of users do not scroll below the fold. This is because most visual information processing occurs during fixations (brief pauses on specific points), and above-fold content receives significantly more fixations than below-fold content. These findings empirically validate that the fold concept—originally from print newspaper layout—remains highly relevant in web design, as it marks a critical boundary where user attention and information processing drop dramatically.

**Model response:**

```
Eye tracking technology measures where users fixate their gaze and for how long, revealing that the vast majority of visual processing happens during these fixation pauses rather than during eye movements (saccades). The empirical data consistently shows that above-the-fold content receives approximately 84% more attention than below-the-fold content, and that 77% of visitors never scroll past the fold. This validates the fold as a crucial design consideration inherited from print newspapers, where the upper half of the front page was visible on newsstands. Eye tracking serves as the primary empirical instrument for validating both macro-level layout decisions (like fold placement) and micro-level visual organization, making it the foundational tool for understanding how the fold concept affects user attention distribution on web pages.
```

### Q32: How do progressive web apps balance capabilities with accessibility?
- **Expected:** PWAs use web standards (service workers, manifests) to provide native-like capabilities (offline access, push notifications, home screen installation) while maintaining the web's inherent accessibility advantages — URL addressability, progressive enhancement, and standards-based rendering.
- **Got:** PWAs gain native-like capabilities (offline support, push notifications, hardware access) but inherit SPA design debt through the App Shell Model, creating accessibility challenges including broken platform defaults, signifier degradation, and performance-driven minimalism. The balance is problematic - advanced capabilities come at the cost of compounded accessibility barriers, especially when combined with patterns like infinite scrolling.

**Model response:**

```
According to the belief database, PWAs emerged post-2017 as a convergence of mobile web and native app capabilities, delivering offline support, push notifications, and hardware access. However, PWA architecture inherits SPA design debt through the App Shell Model - the very pattern that enables offline functionality also introduces accessibility barriers through broken navigation defaults, signifier degradation, and performance-driven visual minimalism. This creates a tension where gaining native-like capabilities comes at the cost of accumulating design debt across multiple dimensions. The belief database specifically notes that PWAs using certain patterns like infinite scrolling face 'doubly-compounded design debt' - the highest-debt configuration in modern web architecture. This suggests the balance is not well-achieved: PWAs gain capabilities but struggle with accessibility, requiring explicit compensatory mechanisms to address the inherited architectural problems.
```

### Q41: What is Don Norman's affordance-signifier framework and why is it foundational?
- **Expected:** Norman distinguished affordances (what an object allows) from signifiers (what communicates how to use it). This framework is foundational because it explains both design successes (clear signifiers enable correct mental models) and failures (removed signifiers cause the flat design crisis), providing both descriptive and prescriptive power.
- **Got:** {"tool": "search_beliefs", "query": "what users perceive communication"}

Tool result:
Don Norman de

**Model response:**

```

```

### Q42: What are Jakob Nielsen's key contributions to usability?
- **Expected:** Nielsen established usability as a systematic discipline through his 10 usability heuristics, the discount usability engineering methodology (including the finding that 5 users reveal ~85% of usability problems), founding the Nielsen Norman Group with Don Norman, and decades of evidence-based usability research and advocacy.
- **Got:** Nielsen's 10 usability heuristics and heuristic evaluation methodology

**Model response:**

```
Jakob Nielsen's most significant contribution to usability is his set of 10 usability heuristics proposed in 1994, which include principles like visibility of system status, match between system and real world, user control and freedom, consistency and standards, error prevention, recognition rather than recall, flexibility and efficiency of use, aesthetic and minimalist design, error recovery support, and help documentation. These heuristics form the foundation of heuristic evaluation, a quick and cost-effective usability inspection method where evaluators examine interfaces against these established principles. Nielsen has also been an influential voice in usability discourse, providing critical analysis of design trends such as his 2013 critique of flat design as a threat to tablet usability.
```

### Q45: How would you evaluate whether a design system adequately addresses cognitive load management and accessibility?
- **Expected:** Check cognitive load: does it enforce minimum target sizes (Fitts's law), consistent spacing (Gestalt proximity), progressive disclosure patterns, and information hierarchy? Check accessibility: does it encode WCAG contrast ratios in design tokens, provide ARIA patterns in components, support keyboard navigation, and maintain semantic HTML? The gap is usually at the API compliance layer — the design system may specify correctly but applications may implement incorrectly.
- **Got:** Multi-granularity evaluation combining expert inspection (heuristic evaluation, cognitive walkthroughs), empirical user testing, and WCAG compliance verification across both visual and semantic (ARIA) layers

**Model response:**

```
The belief database reveals that complete evaluation requires multiple complementary methods because they find non-overlapping problems. Expert inspection assesses cognitive load management patterns (spatial white space, temporal progressive disclosure, perceptual hierarchy) against established principles, while behavioral observation captures actual user performance and struggle. Critically, accessibility evaluation cannot rely on visual inspection alone because ARIA modifies the accessibility tree without changing visual appearance—the semantic layer requires explicit verification. Design systems encode accessibility across three channels (spatial, perceptual-motor, semantic) and must be tested across all five disability categories, requiring a multi-method approach spanning expert review through empirical validation to adequately assess both cognitive load management and accessibility compliance.
```


## By Objective

- **None**: 36/45 (80%)
