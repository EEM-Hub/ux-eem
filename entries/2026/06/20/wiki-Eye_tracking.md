---
source: sources/wiki-Eye_tracking.md
source_url: https://en.wikipedia.org/wiki/Eye_tracking
---

## Eye Tracking: Principles, Technologies, and UX Applications

Eye tracking measures where a person looks (point of gaze) or how their eyes move relative to their head. It is a foundational research method in UX design, usability testing, and human-computer interaction, providing objective data about visual attention patterns that reveal how users process interfaces, read content, and navigate designs.

## Key Concepts

- **Fixations**: Brief pauses where the eye rests on a specific point; most visual information is processed during fixations, not during movement
- **Saccades**: Rapid eye movements between fixation points; vision is largely suppressed during saccades
- **Scanpath**: The complete sequence of fixations and saccades a user produces while viewing a stimulus — used to analyze cognitive intent, interest, and salience
- **Smooth pursuit**: Eye movement that follows a moving object (distinct from saccade-fixation patterns)
- **Microsaccades**: Small involuntary saccades during attempted fixation — require 240+ Hz sampling to capture
- **Strong eye-mind hypothesis** (Just & Carpenter, 1980): What is fixated is what is being cognitively processed, for exactly as long as the fixation lasts — widely assumed in UX research but contested by covert attention findings
- **Covert attention**: People can attend to something they are not directly looking at, which means fixation maps may show where the eye was, not necessarily where attention was
- **Areas of Interest (AOIs)**: Defined regions of a stimulus used to quantify where and how long users looked; can be manually coded or AI-identified
- **Yarbus's finding**: The task given to a viewer fundamentally changes their eye movement pattern on the same image — critical for UX test design (task framing shapes what you measure)
- Reading is not smooth — it consists of fixations and saccades, with some words skipped and occasional regressions to earlier words

## Commands and Syntax

No CLI commands — but key procedural knowledge for conducting eye tracking studies:

- **Calibration**: Required before every session. Subject looks at known points while the tracker records corresponding gaze values. Poor calibration produces invalid data.
- **Sampling rate selection**: 30 Hz minimum; 50/60 Hz common; 240–1250 Hz needed for fixational eye movements or saccade dynamics research
- **Bright-pupil vs. dark-pupil technique**: Determined by illumination source position relative to optics. Bright-pupil (coaxial light) provides better iris/pupil contrast across all eye colors and lighting conditions.
- **Head-mounted vs. remote (table-mounted)**: Head-mounted measures eye-in-head angles (requires head tracking to get gaze direction). Remote measures gaze angles directly but typically requires head stabilization.

## Data Visualization Methods

| Method | Use Case | Strengths |
|--------|----------|-----------|
| **Heat maps** | Aggregate gaze density across multiple users | Most widely recognized; shows "hot zones" of frequent fixation |
| **Saliency maps** | Highlight attention-grabbing elements | Bright areas on black canvas; good for identifying salient features |
| **Gaze plots / scanpaths** | Individual user analysis | Shows fixation sequence and saccade paths; reveals reading/scanning strategy |
| **Focus maps / blind zone maps** | Identifying unseen content | Highlights areas users did NOT look at — reveals missed content |
| **Animated gaze replay** | Moment-by-moment individual analysis | Shows temporal sequence of attention allocation |

## Tracker Types

| Type | Mechanism | Pros | Cons |
|------|-----------|------|------|
| **Eye-attached (contact lens/coil)** | Physical attachment to eye with mirror or magnetic sensor | Most sensitive; measures horizontal, vertical, and torsion | Intrusive; requires expertise |
| **Optical / video-based** | IR light reflects off eye, captured by camera | Non-invasive, inexpensive, widely used | Requires calibration; affected by glasses/lighting |
| **Electrooculogram (EOG)** | Electrodes measure electric potentials around eyes | Works with eyes closed; low power; wearable; works in any lighting | Poor gaze-direction accuracy; signal drift |

## Relationships

- **Usability testing**: Eye tracking reveals whether users see key UI elements, how they scan pages, and where they get stuck — complements task completion metrics and think-aloud protocols
- **Information architecture**: Scanpath analysis shows navigation patterns and whether content hierarchy matches user attention flow
- **Visual design**: Heat maps validate or challenge assumptions about visual hierarchy, ad placement, and content prominence
- **Accessibility**: Eye tracking is used for assistive technology (wheelchair control, prosthetics) and studying age-related vision changes that affect interface use
- **Cognitive psychology**: Fixation duration and patterns serve as proxies for cognitive processing effort — connects to cognitive load theory in UX
- **AI/Deep learning**: CNNs increasingly used for eye-tracking analysis, saliency prediction, and AOI identification — reduces manual coding effort
- **Protocol analysis**: Eye tracking is often paired with verbal protocols (think-aloud) because fixations alone cannot distinguish recognition from confusion — a fixation on a face may indicate liking, dislike, or puzzlement

## Exam-Relevant Points

- Eye tracking measures gaze position or eye motion; it does **not** directly reveal cognitive processes — a fixation indicates where the eye was, not necessarily what was understood
- The **eye-mind hypothesis** assumes fixation equals processing, but **covert attention** undermines this — users can attend to unfixated areas
- **Yarbus (1967)** demonstrated that the same image produces different scanpaths depending on the task — UX implication: test tasks must match real user goals
- **Bright-pupil** technique uses coaxial illumination and works across all iris colors and lighting conditions; **dark-pupil** uses offset illumination
- **EOG** is the only method that works with eyes closed (used in sleep research) and requires minimal computation, but has poor spatial accuracy
- Heat maps show fixation **frequency**, not attention — they are the most recognized but not the most analytically powerful visualization
- Calibration quality directly determines data validity — a poorly calibrated system produces "wildly erroneous data"
- Experienced vs. novice users show fundamentally different scanpaths (driving study: experts look ahead to danger zones; novices fixate on immediate obstacles)
- Elderly users depend more on foveal (central) vision while walking; younger users leverage peripheral vision — age-related design implications
- Minimum 30 Hz sampling rate; 240+ Hz needed for microsaccade and saccade dynamics research
- Visual attention leads the eye by 100–250 ms — attention shifts before gaze follows
