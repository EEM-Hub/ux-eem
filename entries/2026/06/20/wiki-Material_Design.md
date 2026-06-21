---
source: sources/wiki-Material_Design.md
source_url: https://en.wikipedia.org/wiki/Material_Design
---

## Google Material Design: Design Language for Cross-Platform UI

Material Design is a comprehensive design language developed by Google, first announced at Google I/O in June 2014 (codenamed "Quantum Paper"). It provides a unified visual framework for building user interfaces across Android, iOS, and web platforms, grounded in the metaphor of physical paper and ink but enhanced with digital capabilities like responsive animation, depth effects (lighting and shadows), and intelligent material that "expands and reforms." Led by head designer Matías Duarte, it has evolved through four major versions: Material Design 1 (2014), Material Design 2 (2018), Material Design 3 / Material You (2021), and Material 3 Expressive (2025).

## Key Concepts

- **Paper-and-ink metaphor**: Digital "material" behaves like physical paper with surfaces, edges, seams, and shadows that communicate affordance — what you can touch and interact with
- **Grid-based layouts**: Systematic use of grids for consistent spatial organization
- **Depth and elevation**: Lighting and shadow effects convey hierarchy and spatial relationships between UI elements
- **Responsive animations and transitions**: Motion design provides continuity and meaning during state changes
- **Cards UI pattern**: Expanded from the cards interface that debuted in Google Now
- **Skeuomorphic roots, digital execution**: Based on real-world interaction concepts but implemented with capabilities that go beyond physical constraints
- **Material Design 2 (2018)**: Emphasized white space, rounded corners, colorful icons, bottom navigation bars, and greater brand customization; introduced Google Sans font
- **Material Design 3 / Material You (2021)**: Introduced dynamic color theming generated from user wallpaper, increased animation, larger buttons, and custom UI theme generation; greater flexibility for designers in geometry, colors, and typography
- **Material 3 Expressive (2025)**: Further improved animations, more colorful and expressive design; announced for Android 16 and Wear OS 6
- **Cross-platform consistency**: Designed to provide a unified experience across Android, iOS, web, and other Google platforms
- **Open source implementations**: Available as component libraries for Android, iOS (discontinued), Web (discontinued), and Flutter

## Commands and Syntax

Material Design is implemented through several official component libraries:

- **Android**: `material-components-android` (latest stable: 1.12.0, May 2024) — Apache-2.0 license
- **Flutter**: `material-components-flutter` — BSD-3-Clause license; primary implementation via Flutter framework and Jetpack Compose
- **Web**: `material-components-web` (v14.0.0, April 2022, discontinued) — MIT license; canonical web implementation is "Material Web"
- **iOS**: `material-components-ios` (v124.2.0, April 2021, discontinued) — Apache-2.0 license

Current active implementation paths: Flutter, Jetpack Compose, and Material Web (web components).

## Relationships

- **Flat design**: Material Design is often compared to flat design but adds depth through shadows and elevation, distinguishing it from purely flat approaches
- **Fluent Design System**: Microsoft's competing design language, serves a similar cross-platform role for Microsoft products
- **Human Interface Guidelines (HIG)**: Apple's equivalent design system; Material Design often contrasted with HIG in platform-specific design discussions
- **Metro (design language)**: Microsoft's earlier design language that influenced the flat design movement
- **Android ecosystem**: Material Design is the native design language for Android; tightly integrated with Android OS releases (Pie, 12, 16)
- **Google product ecosystem**: Rolled out across Gmail, Calendar, Docs, Photos, Contacts, and other Google apps
- **Flutter and Jetpack Compose**: Primary development frameworks for implementing Material Design in modern apps
- **Corporate Memphis and Liquid Glass**: Contemporary design approaches in the broader design language landscape

## Exam-Relevant Points

- Material Design was announced June 25, 2014, at Google I/O; its codename was "Quantum Paper"
- Head designer: Matías Duarte
- Core metaphor: paper and ink with skeuomorphic roots, but digitally enhanced
- Three major versions to know: MD1 (2014), MD2 (2018), MD3/Material You (2021), plus M3 Expressive (2025)
- Material Design 2 key traits: white space emphasis, rounded corners, bottom navigation bars, brand customization, Google Sans font
- Material Design 3 key trait: dynamic color theming derived from user wallpaper; debuted on Android 12
- Material 3 Expressive: announced May 2025 for Android 16 and Wear OS 6; rolled out to Pixel 6+ starting September 2025
- iOS and Web component libraries are **discontinued**; active implementations are Android (native), Flutter, and Jetpack Compose
- Open source with different licenses per platform (Apache-2.0, BSD-3-Clause, MIT)
- Material Design provides APIs for third-party developers, not just Google's own products
- The canonical open-source web implementation is called **Material Web**
