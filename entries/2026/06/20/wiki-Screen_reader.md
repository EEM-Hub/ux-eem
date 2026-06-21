---
source: sources/wiki-Screen_reader.md
source_url: https://en.wikipedia.org/wiki/Screen_reader
---

## Screen Readers: Assistive Technology for Non-Visual Display Access

Screen readers are assistive technology software that converts on-screen text and image content into speech or Braille output. They are essential tools for blind users and also serve visually impaired, illiterate, and learning-disabled users. This topic is fundamental to understanding how non-visual users interact with digital interfaces and why accessible design patterns matter.

## Key Concepts

- **Screen reader** — software that conveys visual display content through non-visual means: text-to-speech, earcons (auditory icons), or refreshable Braille displays
- **Off-screen model** — a technique where screen readers intercept OS messages to build an internal representation of the GUI, since graphical interfaces lack a purely textual representation of screen content
- **Accessibility APIs** — standardized interfaces provided by operating systems and platforms that let screen readers query what is currently displayed and receive updates on changes, eliminating the need for off-screen models
- **Verbosity settings** — configurable levels (e.g., low/medium/high) that control how much detail the screen reader announces about page structure, formatting, frames, tables, lists, and regions
- **Scripting** — the ability to customize screen reader behavior for specific applications (e.g., JAWS scripting), allowing shared customizations across user communities
- **Earcons** — non-speech audio cues used alongside or instead of speech to convey interface events

## Key Accessibility APIs

- **Android Accessibility Framework**
- **Apple Accessibility API** (macOS, iOS, tvOS)
- **AT-SPI** (Linux/GNOME)
- **IAccessible2**
- **Microsoft Active Accessibility (MSAA)**
- **Microsoft UI Automation**
- **Java Access Bridge**

## Major Screen Readers by Platform

| Platform | Built-in | Third-party |
|----------|----------|-------------|
| Windows | Microsoft Narrator (since Windows 2000) | JAWS (commercial), NVDA (free/open source), ZoomText |
| macOS/iOS/tvOS | VoiceOver | — |
| Android | TalkBack | — |
| ChromeOS | ChromeVox | — |
| Amazon devices | VoiceView | — |
| Linux | — | Speakup, Orca (free/open source) |

## Commands and Syntax

No specific commands — screen readers are end-user tools. However, relevant design considerations include:

- **Language metadata encoding** — screen readers that support multiple languages rely on proper `lang` attributes in HTML to switch speech synthesis voices
- **ARIA roles and properties** — map to accessibility API constructs that screen readers query
- **Focus management** — screen readers follow focus; interactive elements must be keyboard-focusable and announce their role, state, and name

## Relationships

- **Assistive technology** — screen readers are one category; others include screen magnifiers, switch devices, and voice recognition
- **Accessibility APIs** — the bridge between application UI and screen reader comprehension; applications must implement these APIs correctly for screen readers to work
- **WCAG / accessibility standards** — define the requirements that make content screen-reader compatible
- **Semantic HTML** — proper markup (headings, landmarks, labels, alt text) directly determines screen reader usability
- **Keyboard navigation** — screen reader users rely entirely on keyboard; all interactive patterns must support keyboard access
- **ARIA** — supplements native semantics when HTML alone is insufficient to convey widget roles, states, and properties

## Exam-Relevant Points

- Screen readers use **three primary output modes**: text-to-speech, earcons, and Braille displays
- The **off-screen model** was the original technique for GUI access; modern screen readers prefer **accessibility APIs** but may supplement with OS messages and application object models when APIs are insufficient
- Applications that **fail to comply with accessibility APIs** will not work properly with screen readers — this is the single most common cause of inaccessibility
- **JAWS and NVDA** are the most popular Windows screen readers (JAWS is commercial; NVDA is free/open source)
- **VoiceOver** is built into all Apple platforms; **TalkBack** is built into Android; **Narrator** is built into Windows
- **Verbosity controls** let users adjust how much structural detail is announced — critical for balancing efficiency vs. comprehension
- Screen readers depend on **proper language metadata** to handle multilingual content correctly
- The term "screen reader" originated from IBM's 1984 product **IBM Screen Reader**, developed from the earlier SAID prototype (~1978)
- Screen reader users can interact with web browsers, word processors, email, and other applications — but the experience is **considerably more difficult** than visual GUI use, especially when applications include animations or violate platform accessibility standards
