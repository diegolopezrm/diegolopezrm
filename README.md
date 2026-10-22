<div align="center">

<img src="https://github.com/diegolopezrm.png" width="120" alt="Diego López" />

# Diego López

**Senior Mobile & Full-Stack Engineer** · Flutter · Dart · React · Cloud

Bucaramanga, Colombia · Remote, US time zones

[![LinkedIn](https://img.shields.io/badge/LinkedIn-diegolopezcamacho-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/diegolopezcamacho)
[![Email](https://img.shields.io/badge/Email-diegolopezcamacho%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:diegolopezcamacho@gmail.com)
[![DL Soft](https://img.shields.io/badge/DL_Soft-dlsoft.dev-111111?style=for-the-badge&logo=googlechrome&logoColor=white)](https://dlsoft.dev)
[![pub.dev](https://img.shields.io/badge/pub.dev-genui__gen-0175C2?style=for-the-badge&logo=dart&logoColor=white)](https://pub.dev/packages/genui_gen)

</div>

<br/>

I build mobile and web products end to end, from architecture to store release, and I ship fixes into the frameworks I use every day.

- **8+ years** shipping cross-platform apps: 8+ titles in the App Store and Play Store, 20,000+ active users.
- **Regulated software.** Led the Flutter app and GCP architecture behind FDA-regulated PCR diagnostic devices at Visby Medical.
- **AI in production.** Directed 100+ AI chatbots at TK Elevator and embedded agentic workflows (Claude Code) across development, QA and release.
- **Leadership.** Led and mentored teams of up to 10 engineers across the US, Spain, Chile and Colombia.
- **Open source.** Merged code in `flutter/flutter`, `flutter/genui`, Google's `a2ui` protocol, `jaspr`, HeyGen's `hyperframes`, `opencv_dart` and the Flutter plugin for Meta's AI glasses. Author of two Dart packages on pub.dev.
- **Founder** of [DL Soft](https://dlsoft.dev), building software for healthcare, legal, government and education since 2019.

> ![Open to work](https://img.shields.io/badge/Open_to_work-2EA043?style=flat-square) **Open to senior mobile / full-stack roles**, remote in US time zones. Fastest way to reach me is [email](mailto:diegolopezcamacho@gmail.com).

<br/>

## <img src="https://api.iconify.design/octicon:telescope-16.svg?color=%237d8590&height=20" height="20" align="absmiddle" alt="" /> Now

- Contributing to Flutter's foldable-device support ahead of the iPhone Duo.
- Fixing accessibility in Flutter's A2UI renderers, [`a2ui_flutter`](https://github.com/a2ui-project/a2ui/tree/main/dart/a2ui_flutter) and [`flutter/genui`](https://github.com/flutter/genui): what a generated component says to a screen reader, measured rather than assumed.
- Maintaining [`genui_gen`](https://pub.dev/packages/genui_gen), code generation for Google's GenUI framework.
- Running a cross-language conformance suite against the four `a2ui` client implementations.
- Checking that HeyGen's [HyperFrames](https://github.com/heygen-com/hyperframes) renders the same colors on any machine, measured against known swatches.

<br/>

## <img src="https://api.iconify.design/octicon:tools-16.svg?color=%237d8590&height=20" height="20" align="absmiddle" alt="" /> Open source

| Project | Contribution | Status |
|---|---|---|
| [**flutter/flutter**](https://github.com/flutter/flutter) | [#191647](https://github.com/flutter/flutter/pull/191647) Report web `env(safe-area-inset-*)` as `FlutterView.viewPadding`. Closes [#84833](https://github.com/flutter/flutter/issues/84833), open since 2021. Picked up in [Flutter Notable Commits](https://github.com/flutter/flutter/issues/181433). | ![Merged Sep 2026](https://img.shields.io/badge/Merged-Sep_2026-8250DF?style=flat-square&labelColor=8250DF&color=30363D) |
| [**flutter/genui**](https://github.com/flutter/genui) · Google's generative UI SDK | [#1035](https://github.com/flutter/genui/pull/1035) Apply the accessibility label and description an agent sends · [#1042](https://github.com/flutter/genui/pull/1042) Give the catalog's controls a name · [#1043](https://github.com/flutter/genui/pull/1043) Announce an image's description · [#1038](https://github.com/flutter/genui/pull/1038) Show a literal CheckBox value. Found by measuring the semantics tree each component produces; the maintainers asked me to own the accessibility fix. | ![4 PRs merged](https://img.shields.io/badge/Merged-4_PRs-8250DF?style=flat-square&labelColor=8250DF&color=30363D) |
| [**a2ui-project/a2ui**](https://github.com/a2ui-project/a2ui) · Google's agent-to-UI protocol | Eight PRs across the Dart, TypeScript and Swift clients, including a [cross-language conformance suite](https://github.com/a2ui-project/a2ui/pull/2497) for the expression parser. Twenty-one issues filed, most from measured divergences between the implementations. Accessibility fixes for `a2ui_flutter`, the renderer replacing `flutter/genui`, in review ([#3411](https://github.com/a2ui-project/a2ui/pull/3411), [#3412](https://github.com/a2ui-project/a2ui/pull/3412)). | ![8 PRs merged](https://img.shields.io/badge/Merged-8_PRs-8250DF?style=flat-square&labelColor=8250DF&color=30363D) |
| [**schultek/jaspr**](https://github.com/schultek/jaspr) · the Dart web framework behind flutter.dev | [#893](https://github.com/schultek/jaspr/pull/893) Parse raw HTML against the element it lands in · [#897](https://github.com/schultek/jaspr/pull/897) Ignore a malformed `If-Modified-Since` · [#896](https://github.com/schultek/jaspr/pull/896) Render `css()` as native nested CSS. [#895](https://github.com/schultek/jaspr/pull/895), `--enable-experiment` for build and serve, in review. | ![3 PRs merged](https://img.shields.io/badge/Merged-3_PRs-8250DF?style=flat-square&labelColor=8250DF&color=30363D) |
| [**heygen-com/hyperframes**](https://github.com/heygen-com/hyperframes) · HeyGen's HTML-to-video renderer | [#5382](https://github.com/heygen-com/hyperframes/pull/5382) Encode and tag ProRes MOV output as BT.709, so its colors match the MP4 · [#5394](https://github.com/heygen-com/hyperframes/pull/5394) Say when the Docker image build times out instead of blaming Docker. Both found measuring renders against known color swatches. | ![2 PRs merged](https://img.shields.io/badge/Merged-2_PRs-8250DF?style=flat-square&labelColor=8250DF&color=30363D) |
| [**rainyl/opencv_dart**](https://github.com/rainyl/opencv_dart) | [#451](https://github.com/rainyl/opencv_dart/pull/451) Fail early when OpenCV is older than dartcv requires · [#452](https://github.com/rainyl/opencv_dart/pull/452) Let projects choose which OpenCV to build against. | ![Merged](https://img.shields.io/badge/Merged-8250DF?style=flat-square) |
| [**rodcone/flutter_meta_wearables_dat**](https://github.com/rodcone/flutter_meta_wearables_dat) · Flutter plugin for Meta's AI glasses | [#50](https://github.com/rodcone/flutter_meta_wearables_dat/pull/50) Carry the glasses' microphone on the camera stream (iOS). Shipped in 1.0.1. | ![Merged Oct 2026](https://img.shields.io/badge/Merged-Oct_2026-8250DF?style=flat-square&labelColor=8250DF&color=30363D) |
| [**flutter/flutter**](https://github.com/flutter/flutter) | [#192721](https://github.com/flutter/flutter/pull/192721) Animate the child between sub-screens when the fold changes · [#193362](https://github.com/flutter/flutter/pull/193362) Let the browser handle Control+wheel zoom. | ![In review](https://img.shields.io/badge/In_review-1F6FEB?style=flat-square) |

<br/>

## <img src="https://api.iconify.design/octicon:package-16.svg?color=%237d8590&height=20" height="20" align="absmiddle" alt="" /> Packages

**[genui_gen](https://pub.dev/packages/genui_gen)** · **[genui_gen_builder](https://pub.dev/packages/genui_gen_builder)** · [source](https://github.com/diegolopezrm/genui_gen) · [docs](https://diegolopezrm.github.io/genui_gen)

[![pub version](https://img.shields.io/pub/v/genui_gen?style=flat-square&logo=dart&logoColor=white&label=genui_gen)](https://pub.dev/packages/genui_gen)
[![pub version](https://img.shields.io/pub/v/genui_gen_builder?style=flat-square&logo=dart&logoColor=white&label=genui_gen_builder)](https://pub.dev/packages/genui_gen_builder)
[![pub points](https://img.shields.io/pub/points/genui_gen_builder?style=flat-square&label=pub%20points)](https://pub.dev/packages/genui_gen_builder/score)

Annotate a Flutter widget, run `build_runner`, and get a [GenUI](https://pub.dev/packages/genui) `CatalogItem` whose JSON schema, widget builder and few-shot examples are derived from the constructor. The catalog cannot drift from the widget because nothing is written by hand. Annotate a plain Dart function and it becomes a catalog function the agent can call. The builder scores 160/160 on pub.dev's quality report.

It also ships the tools an agent-composed interface needs and an ordinary app does not: record a real session and replay it with no model or network, keep what every component says to a screen reader and fail the build when it changes, and diff a catalog against the one you published to see what a rename costs the agent.

**[Quincena](https://diegolopezrm.github.io/quincena/)** · [source](https://github.com/diegolopezrm/quincena) puts all of it in one app: personal finance where an agent composes every answer from a catalog of twenty generated components, in Spanish and English. It runs in the browser with no account or key, and replays five sessions Gemini answered for real.

<br/>

## <img src="https://api.iconify.design/octicon:briefcase-16.svg?color=%237d8590&height=20" height="20" align="absmiddle" alt="" /> Experience

| When | Where | What |
|---|---|---|
| 2025 – 2026 | **Visby Medical** · US, remote | Senior Mobile Engineer. Owned the Flutter app and GCP architecture for FDA-regulated diagnostic devices, supervising 3 engineers. |
| 2024 – 2025 | **TK Elevator** via Stefanini · Chile | Technical Lead, AI. 100+ chatbots on Azure OpenAI and Cognitive Search, leading a 3-person team. |
| 2023 – 2024 | **Spect Inc.** · US, remote | Senior Full-Stack Engineer. Real-time medical video calls (AWS Chime) between iOS and web, Go backend services. |
| 2023 | **Shokworks** · US, remote | Senior Full-Stack Developer. Led the mobile team on fintech and investment platforms. |
| 2022 – 2023 | **Kubesoft** · Colombia / US | Senior Flutter Developer. 3D maps with real-time tracking for 1,000+ vehicles. |
| 2022 | **ActionTracker** · Spain, remote | Senior Flutter Developer. Led 7 engineers on a vessel and vehicle monitoring app with 5,000+ users. |
| 2020 – 2022 | **UIS** · **Samsoft** · Colombia | Migrated 1B+ records from Informix to Oracle. Shipped 20+ notarial PWAs in React. |
| 2019 – now | **DL Soft** · Colombia | Founder & Technical Director. 10+ projects for healthcare, legal, government and education. |

<br/>

## <img src="https://api.iconify.design/octicon:rocket-16.svg?color=%237d8590&height=20" height="20" align="absmiddle" alt="" /> Selected work

- **Sinfony** · Colombia's leading notarial platform, running in 40+ notary offices, with DIAN e-invoicing and AI-assisted document generation. `React` `Node.js` `Oracle`
- **Iglesia La Victoria** · Booking web app serving 50,000+ weekly users, plus a fintech mobile app for community payments. `React` `Flutter` `Firebase`
- **SkyWatch Security** · Enterprise workforce and site-security platform with QR time tracking and multi-role access. `Flutter`
- **Fluxway** · Collaborative EV charging marketplace for Colombia, with trip planner and QR-based identification. `React Native` `Firebase`
- **Montañas Azules** · Patient meal ordering for Hospital Internacional de Colombia. `Flutter` `Firebase`

More at [dlsoft.dev](https://dlsoft.dev).

<br/>

## <img src="https://api.iconify.design/octicon:stack-16.svg?color=%237d8590&height=20" height="20" align="absmiddle" alt="" /> Stack

<div align="center">

**Mobile**

<img src="https://skillicons.dev/icons?i=flutter,dart,swift,kotlin,apple,androidstudio" alt="Flutter, Dart, Swift, Kotlin, Apple, Android Studio" />

**Web & backend**

<img src="https://skillicons.dev/icons?i=react,ts,nextjs,nodejs,go,python,java,graphql" alt="React, TypeScript, Next.js, Node.js, Go, Python, Java, GraphQL" />

**Cloud & data**

<img src="https://skillicons.dev/icons?i=gcp,aws,azure,firebase,docker,kubernetes,terraform,mongodb" alt="GCP, AWS, Azure, Firebase, Docker, Kubernetes, Terraform, MongoDB" />

</div>

Plus Azure OpenAI, Claude and agentic workflows in production, and CI/CD for every store release.

<br/>

## <img src="https://api.iconify.design/octicon:graph-16.svg?color=%237d8590&height=20" height="20" align="absmiddle" alt="" /> GitHub

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=diegolopezrm&theme=github-dark-blue&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" />
  <img alt="GitHub contribution streak" src="https://streak-stats.demolab.com?user=diegolopezrm&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" />
</picture>

</div>

<br/>

## <img src="https://api.iconify.design/octicon:book-16.svg?color=%237d8590&height=20" height="20" align="absmiddle" alt="" /> Also

- Co-author of a Flutter engineering book with [Majid Hajian](https://github.com/mhadaily).
- B.Sc. Computer Engineering, Industrial University of Santander (2024).
- Spanish native · English professional (C1).

<br/>

<div align="center">

[LinkedIn](https://www.linkedin.com/in/diegolopezcamacho) · [Email](mailto:diegolopezcamacho@gmail.com) · [dlsoft.dev](https://dlsoft.dev) · [pub.dev](https://pub.dev/packages/genui_gen)

</div>
