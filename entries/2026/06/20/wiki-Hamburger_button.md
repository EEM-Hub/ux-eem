---
source: sources/wiki-Hamburger_button.md
source_url: https://en.wikipedia.org/wiki/Hamburger_button
---

## Hamburger Button: Navigation Menu Toggle Pattern

The hamburger button (≡) is a UI control consisting of three parallel horizontal lines, typically placed in a top corner of a graphical user interface. Its function is to toggle a navigation menu or menu panel between a collapsed (hidden) and expanded (visible) state. The icon is designed to resemble lines of text in a small printed menu and is named after its unintentional resemblance to a hamburger sandwich.

## Key Concepts

- **Definition**: A button that toggles a menu or navigation bar between collapsed and displayed states
- **Icon**: Three parallel horizontal bars (≡), known as the "hamburger icon" or "collapsed menu icon"
- **Placement**: Typically in a top corner of the interface
- **Origin**: Designed by Norm Cox for the Xerox Star (1981) with a 16×16 pixel (or possibly 13×13) constraint — intended to be "road sign simple, functionally memorable"
- **Resurgence**: Re-emerged around 2009 driven by limited screen real estate on mobile devices
- **Variants**:
  - **Kebab button**: Three vertically stacked dots (⋮) — reduces screen real-estate consumption further
  - **Meatball / falafel button**: Similar dot-based variants
  - **Waffle button**: Three rows of three squares (⊞-like grid) — used in Microsoft Office 365 and Google apps to pop up an icon array rather than a text menu
- **Not a Unicode character**: The icon itself is not encoded in Unicode; designers approximate it with characters like U+2261 (≡), U+2630 (☰), or U+11054 (𑁔)

## Commands and Syntax

- **CSS implementation**: W3Schools documents how to create a hamburger menu icon with CSS (three horizontal bars)
- **Unicode approximations for prototyping**:
  - Hamburger: `≡` (U+2261), `☰` (U+2630)
  - Kebab: `⋮` (U+22EE), `⁝` (U+205D)
  - Waffle: `▦` (U+25A6) or three kebab characters in a row
- **Caution**: Not all browsers or fonts support these Unicode characters — some users will see a replacement glyph (□ / "tofu")

## Relationships

- **Navigation bar**: The hamburger button's primary function is to toggle navigation visibility
- **Menu bar**: The hamburger menu is often compared unfavorably to persistent menu bars due to increased interaction cost
- **Responsive/mobile design**: The hamburger pattern is a direct response to constrained screen space on mobile devices
- **Interaction cost**: Requires additional clicks compared to visible menu bars — trades discoverability for screen space
- **Related patterns**: Menu key, ellipsis (indicates "more options" for a subset, whereas hamburger signifies all hidden options), tab bar

## Exam-Relevant Points

- **Designer**: Norm Cox; **Year**: 1981; **Platform**: Xerox Star — this is the canonical origin
- **Windows history**: Present in Windows 1.0 (1985), removed in Windows 2.0, returned in Windows 10 Anniversary Update (2016)
- **Mobile resurgence**: ~2009, driven by limited mobile screen area
- **Discoverability problem**: The icon's meaning is not necessarily immediately obvious to first-time or older users — a well-documented usability concern
- **Interaction cost tradeoff**: Hamburger menus save screen space but increase the number of clicks to access content compared to persistent menu bars
- **Overloading risk**: Designers tend to hide too much content behind hamburger menus, reducing discoverability
- **Hamburger vs. kebab vs. waffle**: Know the visual distinction (three lines vs. three dots vs. 3×3 grid) and their typical use contexts
- **The icon is not a standardized Unicode character** — using Unicode approximations risks rendering failures across browsers and fonts
