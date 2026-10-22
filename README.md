# Teddy Yeung

Mobile engineer (5 years) building and operating production iOS & Android apps with Flutter.

**Focus areas**
- **Architecture**: modular, testable codebases that scale with the product and the team
- **Delivery**: CI/CD and build automation that keep releases fast and predictable
- **AI-assisted engineering**: integrating coding agents into review, testing, and release workflows
- **Platform**: native-layer work in Swift and Kotlin, contributed upstream to Flutter packages

[Website](https://teddyyeung.is-a.dev) · [LinkedIn](https://www.linkedin.com/in/teddyyeung/) · [Medium](https://medium.com/@TeddyYeung)

## Open Source Contributions

| Project | Contribution | Reach |
|---|---|---|
| [flutter/packages](https://github.com/flutter/packages) `image_picker_ios` · [#12267](https://github.com/flutter/packages/pull/12267) | Fixed a long-standing iOS bug ([flutter#132154](https://github.com/flutter/flutter/issues/132154), open since 2023) where undecodable images such as AVIF left the picker hanging; added a regression test. Shipped in 0.8.13+10. | ~5M downloads/mo |
| [flutter_foreground_task](https://github.com/Dev-hwang/flutter_foreground_task) · [#387](https://github.com/Dev-hwang/flutter_foreground_task/pull/387) | Added iOS Swift Package Manager support by isolating a pure-Swift target, with zero breaking changes for CocoaPods users. Shipped in v11.0.0. | ~219K downloads/mo |
| [image_gallery_saver_plus](https://github.com/ArmanKT/image_gallery_saver_plus) · [#3](https://github.com/ArmanKT/image_gallery_saver_plus/pull/3) | Fixed a broken `Package.swift` that made SPM resolution fail for every consumer. | ~136K downloads/mo |
| [is_lock_screen2](https://github.com/Wing-Li/flutter_is_lock_screen2) · [#10](https://github.com/Wing-Li/flutter_is_lock_screen2/pull/10) | Added iOS SPM support alongside CocoaPods. Shipped in v2.1.0. | |

Detailed write-ups: [open-source-contributions](https://github.com/TeddyYeung/open-source-contributions)

## Packages

- **[flutter_jailbreak_guard](https://pub.dev/packages/flutter_jailbreak_guard)** ([GitHub](https://github.com/TeddyYeung/flutter_jailbreak_guard)): jailbreak and root detection with SPM and CocoaPods support. A drop-in replacement for the CocoaPods-only [flutter_jailbreak_detection_plus](https://pub.dev/packages/flutter_jailbreak_detection_plus), with an option to pin the BSD-2 licensed IOSSecuritySuite 1.9.x.
- **[flutter_mute_plus](https://pub.dev/packages/flutter_mute_plus)** ([GitHub](https://github.com/TeddyYeung/flutter_mute_plus)): maintained fork of the unmaintained [flutter_mute](https://pub.dev/packages/flutter_mute), updated for AGP 8/9, Xcode 16+ and SPM. 160/160 pub points.
