# Exam Results: ux-design.md

**Date:** 2026-06-22 16:22
**Model:** claude:haiku
**Score:** 37/45 (82%)

## Per-Question Results

- **Q1**: CORRECT — What is Fitts's law and how does it apply to web UI design?
- **Q2**: CORRECT — How does Hick's law relate to information architecture and navigation design?
- **Q3**: CORRECT — Explain the expertise reversal effect and its implications for progressive disclosure in web interfaces.
- **Q4**: CORRECT — How do Gestalt principles of proximity and similarity apply to visual hierarchy in web layouts?
- **Q5**: CORRECT — What is cognitive load theory and how do its three types map to UI design decisions?
- **Q6**: WRONG — What are the usability problems with carousels in web design?
  - Expected: Carousels combine multiple usability anti-patterns: they violate user control by auto-advancing, create banner blindness, hide content behind interaction, distribute attention across panels reducing engagement with each, and introduce timing pressure that conflicts with self-paced reading.
  - Got: Carousels have multiple compounding usability problems: they auto-advance stealing user attention (causing habituation like modals), hide content behind sequential navigation (like infinite scroll), and violate progressive disclosure principles by concealing content without user control over the disclosure pace. They are widely considered harmful to both usability and SEO.
- **Q7**: WRONG — When is infinite scrolling appropriate versus pagination?
  - Expected: Infinite scrolling suits discovery-oriented tasks (social feeds, image browsing) where users don't need to reach specific content. Pagination is better for goal-directed tasks (search results, product listings) where users need to reference specific positions, compare items, or return to a known location.
  - Got: The provided beliefs do not clearly specify when infinite scrolling is appropriate; they emphasize its drawbacks (accessibility barriers, loss of addressability/indexability, removal of stopping cues contributing to compulsive usage) compared to pagination's advantages (skip-navigation, permanent deep links, better accessibility). Hybrid approaches like 'load more' buttons are suggested as compromises.
- **Q8**: WRONG — What is progressive disclosure and what cognitive principles justify its use?
  - Expected: Progressive disclosure stages information reveal to show only what is needed at each step. It is justified by working memory limits (reducing visible options reduces extraneous cognitive load), Gestalt grouping (fewer elements create clearer visual hierarchy), and Hick's law (fewer visible choices speed decision-making).
  - Got: Progressive disclosure reduces complexity by initially presenting only essential information and revealing advanced options on demand. Its cognitive justification rests on: (1) working memory capacity constraints (Miller's 7±2 chunks), (2) extraneous load reduction—the only load type designers control—which improves both learning curves and error rates, and (3) the 84% above-fold attention differential, which determines where disclosure stages should be placed. Progressive disclosure simultaneously achieves load reduction and encoding enhancement through the Von Restorff isolation effect, making it the scientifically superior alternative to modal warnings for managing interface complexity.
- **Q9**: WRONG — What are the usability concerns with modal windows?
  - Expected: Modal windows block interaction with the underlying page, disrupting user flow and potentially causing loss of context. They can trap keyboard focus creating accessibility problems, they interrupt task completion, and on mobile they often have dismiss targets that are too small to tap reliably.
  - Got: Modal windows have three independent categories of usability problems: (1) cognitive—habituation causes users to dismiss without reading, and they cover information needed to complete the modal's own task; (2) security—focus-stealing intercepts input intended for other programs; (3) load management—split-attention from separating related information across modal and parent window.
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
  - Got: Color theory provides the perceptual science foundation for WCAG accessibility standards, enabling systematic enforcement of both accessibility compliance and visual hierarchy through design tokens and design systems.
- **Q21**: CORRECT — What is the difference between heuristic evaluation and cognitive walkthrough?
- **Q22**: CORRECT — How does A/B testing complement qualitative usability testing?
- **Q23**: CORRECT — What is Simpson's paradox and why does it matter for A/B test analysis?
- **Q24**: CORRECT — How does card sorting support information architecture design?
- **Q25**: WRONG — What does eye tracking reveal about user attention and the concept of the fold?
  - Expected: Eye tracking shows significantly more fixation on above-fold content, with studies suggesting an 84% attention differential. However, covert attention (processing without fixation) means fixation maps may overstate the difference, and there is no universal pixel definition for the fold across devices, limiting prescriptive application.
  - Got: Eye tracking reveals that most visual information is processed during fixations (brief pauses on specific points), not saccades. This fixation-based processing, grounded in the eye-mind hypothesis (Just & Carpenter 1980), validates the fold concept: the 84% attention differential between above-fold and below-fold content is explained by content below the fold receiving fewer or no fixations, directly measurable through eye tracking data. However, covert attention (attending to something without looking at it) means fixations show where the eye was, not necessarily where attention was directed.
- **Q26**: CORRECT — What is user-centered design and what are its core principles?
- **Q27**: CORRECT — How do personas help close the mental-model gap between designers and users?
- **Q28**: CORRECT — What role do wireframes play in the UX design process?
- **Q29**: CORRECT — What is a design system and how does it differ from a style guide?
- **Q30**: CORRECT — How does design thinking's abductive reasoning approach apply to wicked problems in UX?
- **Q31**: CORRECT — What UX challenges do single-page applications introduce?
- **Q32**: WRONG — How do progressive web apps balance capabilities with accessibility?
  - Expected: PWAs use web standards (service workers, manifests) to provide native-like capabilities (offline access, push notifications, home screen installation) while maintaining the web's inherent accessibility advantages — URL addressability, progressive enhancement, and standards-based rendering.
  - Got: PWAs balance capabilities with accessibility primarily through resource efficiency, but this balance is complicated by inherited architectural debt.
- **Q33**: WRONG — What is the relationship between web performance and user experience?
  - Expected: Web performance directly affects user perception and engagement. Slow load times increase bounce rates, reduce conversions, and degrade perceived quality. Performance optimization (compression, caching, lazy loading) serves UX by reducing the time between user intent and interface response.
  - Got: Web performance and user experience have a complex, sometimes tension-filled relationship. While frontend performance is important (80% of page load time is frontend-controlled), aggressive performance optimization can paradoxically degrade UX through signifier loss.
- **Q34**: CORRECT — How does above the fold apply in responsive web design?
- **Q35**: CORRECT — What is the dual quality mandate in modern web architecture?
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

### Q6: What are the usability problems with carousels in web design?
- **Expected:** Carousels combine multiple usability anti-patterns: they violate user control by auto-advancing, create banner blindness, hide content behind interaction, distribute attention across panels reducing engagement with each, and introduce timing pressure that conflicts with self-paced reading.
- **Got:** Carousels have multiple compounding usability problems: they auto-advance stealing user attention (causing habituation like modals), hide content behind sequential navigation (like infinite scroll), and violate progressive disclosure principles by concealing content without user control over the disclosure pace. They are widely considered harmful to both usability and SEO.

**Model response:**

```
```json
{
  "answer": "Carousels have multiple compounding usability problems: they auto-advance stealing user attention (causing habituation like modals), hide content behind sequential navigation (like infinite scroll), and violate progressive disclosure principles by concealing content without user control over the disclosure pace. They are widely considered harmful to both usability and SEO.",
  "explanation": "Carousels exemplify a compound failure pattern: they combine the worst properties of both modals (auto-advancing content that steals attention and triggers habituation) and infinite scrolling (hiding content behind sequential navigation). Unlike proper progressive disclosure—where users control when additional information is revealed—carousels force sequential navigation and remove stopping cues, making them doubly discredited as a design pattern."
}
```
```

### Q7: When is infinite scrolling appropriate versus pagination?
- **Expected:** Infinite scrolling suits discovery-oriented tasks (social feeds, image browsing) where users don't need to reach specific content. Pagination is better for goal-directed tasks (search results, product listings) where users need to reference specific positions, compare items, or return to a known location.
- **Got:** The provided beliefs do not clearly specify when infinite scrolling is appropriate; they emphasize its drawbacks (accessibility barriers, loss of addressability/indexability, removal of stopping cues contributing to compulsive usage) compared to pagination's advantages (skip-navigation, permanent deep links, better accessibility). Hybrid approaches like 'load more' buttons are suggested as compromises.

**Model response:**

```
```json
{
  "answer": "The provided beliefs do not clearly specify when infinite scrolling is appropriate; they emphasize its drawbacks (accessibility barriers, loss of addressability/indexability, removal of stopping cues contributing to compulsive usage) compared to pagination's advantages (skip-navigation, permanent deep links, better accessibility). Hybrid approaches like 'load more' buttons are suggested as compromises.",
  "explanation": "According to the beliefs, pagination is preferred for large datasets (server-side), supports addressability and indexability critical for SEO and deep-linking, works without JavaScript for better accessibility, and enables user control. Infinite scrolling creates accessibility barriers, prevents footer access and bookmarking, loses page addressability, and removes natural stopping cues that contribute to compulsive usage patterns. The beliefs identify hybrid variations ('load more' buttons, pagination indicators) as mitigating infinite scroll's drawbacks, and AJAX hybrid pagination as combining server-side efficiency with client-side feel, but do not explicitly recommend scenarios where pure infinite scrolling is the appropriate choice—the evidence presented argues against it as a default pattern."
}
```
```

### Q8: What is progressive disclosure and what cognitive principles justify its use?
- **Expected:** Progressive disclosure stages information reveal to show only what is needed at each step. It is justified by working memory limits (reducing visible options reduces extraneous cognitive load), Gestalt grouping (fewer elements create clearer visual hierarchy), and Hick's law (fewer visible choices speed decision-making).
- **Got:** Progressive disclosure reduces complexity by initially presenting only essential information and revealing advanced options on demand. Its cognitive justification rests on: (1) working memory capacity constraints (Miller's 7±2 chunks), (2) extraneous load reduction—the only load type designers control—which improves both learning curves and error rates, and (3) the 84% above-fold attention differential, which determines where disclosure stages should be placed. Progressive disclosure simultaneously achieves load reduction and encoding enhancement through the Von Restorff isolation effect, making it the scientifically superior alternative to modal warnings for managing interface complexity.

**Model response:**

```
```json
{
  "answer": "Progressive disclosure reduces complexity by initially presenting only essential information and revealing advanced options on demand. Its cognitive justification rests on: (1) working memory capacity constraints (Miller's 7±2 chunks), (2) extraneous load reduction—the only load type designers control—which improves both learning curves and error rates, and (3) the 84% above-fold attention differential, which determines where disclosure stages should be placed. Progressive disclosure simultaneously achieves load reduction and encoding enhancement through the Von Restorff isolation effect, making it the scientifically superior alternative to modal warnings for managing interface complexity.",
  "explanation": "Progressive disclosure is justified by a complete cognitive-to-visual chain: working memory limits necessitate extraneous load reduction (cognitive mechanism), while the above-fold attention differential determines where disclosure stages should be placed (visual mechanism). By hiding secondary content, it reduces visible complexity within working memory capacity limits and triggers the Von Restorff isolation effect, making disclosed information more noticeable and memorable. Unlike modal warnings, which are self-defeating through habituation and information-blocking, progressive disclosure has a complete justification chain with evaluable checkpoints, making it a resolved scientific solution rather than a design preference."
}
```
```

### Q9: What are the usability concerns with modal windows?
- **Expected:** Modal windows block interaction with the underlying page, disrupting user flow and potentially causing loss of context. They can trap keyboard focus creating accessibility problems, they interrupt task completion, and on mobile they often have dismiss targets that are too small to tap reliably.
- **Got:** Modal windows have three independent categories of usability problems: (1) cognitive—habituation causes users to dismiss without reading, and they cover information needed to complete the modal's own task; (2) security—focus-stealing intercepts input intended for other programs; (3) load management—split-attention from separating related information across modal and parent window.

**Model response:**

```
```json
{"answer": "Modal windows have three independent categories of usability problems: (1) cognitive—habituation causes users to dismiss without reading, and they cover information needed to complete the modal's own task; (2) security—focus-stealing intercepts input intended for other programs; (3) load management—split-attention from separating related information across modal and parent window.", "explanation": "Modal dialogs are discredited at both pattern and theory levels. At the pattern level, they fail across cognitive (habituation undermines warnings, information blocking is self-defeating), security (focus-stealing creates privacy/data integrity risks), and load-management dimensions (split-attention cognitive effects). At the theory level, they violate the principle that related information must be spatially co-located for effective processing, and progressive disclosure offers a scientifically superior alternative by staging information without displacing context. Modal warning dialogs are particularly problematic: they are self-defeating because habituation causes dismissal without reading, they block clipboard operations, and expert guidance recommends providing undo instead."}
```
```

### Q20: What is the relationship between color theory and accessibility in web design?
- **Expected:** Color theory provides rules for contrast, depth perception (warm colors advance, cool recede), and hue relationships that directly serve accessibility requirements. WCAG contrast ratios translate these perceptual principles into enforceable thresholds. However, color harmony has no universal formula, limiting what can be systematically enforced.
- **Got:** Color theory provides the perceptual science foundation for WCAG accessibility standards, enabling systematic enforcement of both accessibility compliance and visual hierarchy through design tokens and design systems.

**Model response:**

```
```json
{
  "answer": "Color theory provides the perceptual science foundation for WCAG accessibility standards, enabling systematic enforcement of both accessibility compliance and visual hierarchy through design tokens and design systems.",
  "explanation": "Color theory's perceptual science—particularly warm-advance/cool-recede spatial perception and hue-shift effects from darkening—specifies what color rules must achieve visually, while WCAG specifies measurable contrast thresholds (4.5:1 for AA level). Design tokens systematically enforce these WCAG contrast requirements across products, making accessibility compliance a design-system property rather than per-component decisions. Additionally, color theory provides specific implementation rules for visual hierarchy: warm colors should mark interactive/foreground elements (signaling interactivity through perceptual advance), cool colors should define backgrounds (signaling passivity through recession), and complementary-based darkening should be preferred over black-mixing to avoid unintended hue shifts. Together, color theory grounds accessibility standards in perceptual science while design tokens provide the mechanism to enforce both accessibility and visual hierarchy systematically."
}
```
```

### Q25: What does eye tracking reveal about user attention and the concept of the fold?
- **Expected:** Eye tracking shows significantly more fixation on above-fold content, with studies suggesting an 84% attention differential. However, covert attention (processing without fixation) means fixation maps may overstate the difference, and there is no universal pixel definition for the fold across devices, limiting prescriptive application.
- **Got:** Eye tracking reveals that most visual information is processed during fixations (brief pauses on specific points), not saccades. This fixation-based processing, grounded in the eye-mind hypothesis (Just & Carpenter 1980), validates the fold concept: the 84% attention differential between above-fold and below-fold content is explained by content below the fold receiving fewer or no fixations, directly measurable through eye tracking data. However, covert attention (attending to something without looking at it) means fixations show where the eye was, not necessarily where attention was directed.

**Model response:**

```
```json
{
  "answer": "Eye tracking reveals that most visual information is processed during fixations (brief pauses on specific points), not saccades. This fixation-based processing, grounded in the eye-mind hypothesis (Just & Carpenter 1980), validates the fold concept: the 84% attention differential between above-fold and below-fold content is explained by content below the fold receiving fewer or no fixations, directly measurable through eye tracking data. However, covert attention (attending to something without looking at it) means fixations show where the eye was, not necessarily where attention was directed.",
  "explanation": "Eye tracking operationalizes the eye-mind hypothesis by providing empirical data on fixation patterns, which shows that users concentrate their cognitive processing above the fold. Research documents an 84% attention differential (NNgroup) and 77% no-scroll behavior (Nielsen 2006), and eye tracking's fixation-based model explains this mechanistically: content below the fold receives fewer fixations because users do not scroll there. Eye tracking thus serves as the field's validation instrument at macro scale (fold attention differential) and micro scale (hierarchy scanpath convergence), providing empirical grounding for the fold concept. The limitation is that fixations measure gaze location, not attention itself—covert attention allows cognition to occur without corresponding fixations—so eye tracking reveals attention correlates rather than attention certainties."
}
```
```

### Q32: How do progressive web apps balance capabilities with accessibility?
- **Expected:** PWAs use web standards (service workers, manifests) to provide native-like capabilities (offline access, push notifications, home screen installation) while maintaining the web's inherent accessibility advantages — URL addressability, progressive enhancement, and standards-based rendering.
- **Got:** PWAs balance capabilities with accessibility primarily through resource efficiency, but this balance is complicated by inherited architectural debt.

**Model response:**

```
```json
{
  "answer": "PWAs balance capabilities with accessibility primarily through resource efficiency, but this balance is complicated by inherited architectural debt.",
  "explanation": "Progressive Web Apps provide dramatic accessibility benefits for bandwidth-constrained populations in developing markets—their 1–3% native app size creates a digital-access equity mechanism for users with limited data and storage. However, PWAs inherit SPA design debt through the App Shell Model, creating architectural accessibility challenges across signifier degradation, broken platform defaults (navigation, analytics, SEO), and content addressability barriers. This creates a multi-dimensional balance: PWAs gain accessibility through resource efficiency, but face accessibility challenges from their JavaScript-heavy SPA architecture, requiring systematic compensatory mechanisms to achieve complete accessibility alongside their capability advantages."
}
```
```

### Q33: What is the relationship between web performance and user experience?
- **Expected:** Web performance directly affects user perception and engagement. Slow load times increase bounce rates, reduce conversions, and degrade perceived quality. Performance optimization (compression, caching, lazy loading) serves UX by reducing the time between user intent and interface response.
- **Got:** Web performance and user experience have a complex, sometimes tension-filled relationship. While frontend performance is important (80% of page load time is frontend-controlled), aggressive performance optimization can paradoxically degrade UX through signifier loss.

**Model response:**

```
```json
{
  "answer": "Web performance and user experience have a complex, sometimes tension-filled relationship. While frontend performance is important (80% of page load time is frontend-controlled), aggressive performance optimization can paradoxically degrade UX through signifier loss.",
  "explanation": "Performance optimization pressure, especially in SPA architectures, incentivizes minimalist visual approaches (flat design) to reduce graphics intensity and file sizes. However, Norman's affordance-signifier theory predicts that removing visual cues degrades usability, and NNGroup empirically confirmed this with a 22% performance degradation in flat design interfaces. This creates an inherent design tension in modern web applications: optimizing for load time metrics (Core Web Vitals: TTFB, FCP, FID, CLS, LCP) can conflict with maintaining the visual signifiers that users depend on for understanding affordances and completing tasks. The field's resolution has been through design systems, which encode signifier requirements alongside performance-efficient patterns, allowing designers to achieve both fast load times and usable interfaces—demonstrating that performance and usability need not be zero-sum when approached through systematic design enforcement rather than ad-hoc optimization."
}
```
```


## By Objective

- **None**: 37/45 (82%)
