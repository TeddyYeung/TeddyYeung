# Teddy Yeung

Mobile engineer (5 years) building and operating production iOS & Android apps with Flutter.

**Focus areas**
- **Architecture**: modular, testable codebases that scale with the product and the team
- **Delivery**: CI/CD and build automation that keep releases fast and predictable
- **AI-assisted engineering**: integrating coding agents into review, testing, and release workflows
- **Platform**: native-layer work in Swift and Kotlin, contributed upstream to Flutter and its plugins

[Website](https://teddyyeung.is-a.dev) · [LinkedIn](https://www.linkedin.com/in/teddyyeung/) · [Medium](https://medium.com/@TeddyYeung)

## Open Source Contributions

| Project | Contribution | Reach |
|---|---|---|
| [flutter/flutter](https://github.com/flutter/flutter) web engine · [#195958](https://github.com/flutter/flutter/pull/195958) | Fixed still AVIF images failing to decode on Chrome ([flutter#160600](https://github.com/flutter/flutter/issues/160600)) in both the CanvasKit and Skwasm renderers; added four decoder tests for still and animated AVIF. | Flutter SDK (web) |
| [flutter/packages](https://github.com/flutter/packages) `image_picker_ios` · [#12267](https://github.com/flutter/packages/pull/12267) | Fixed a long-standing iOS bug ([flutter#132154](https://github.com/flutter/flutter/issues/132154), open since 2023) where undecodable images such as AVIF left the picker hanging; added a regression test. Shipped in 0.8.13+10. | ~5.9M downloads/mo |
| [flutter_foreground_task](https://github.com/Dev-hwang/flutter_foreground_task) · [#387](https://github.com/Dev-hwang/flutter_foreground_task/pull/387) | Added iOS Swift Package Manager support by isolating a pure-Swift target, with zero breaking changes for CocoaPods users. Shipped in v11.0.0. | ~270K downloads/mo |
| [image_gallery_saver_plus](https://github.com/ArmanKT/image_gallery_saver_plus) · [#3](https://github.com/ArmanKT/image_gallery_saver_plus/pull/3) | Fixed a broken `Package.swift` that made SPM resolution fail for every consumer. | ~151K downloads/mo |
| [flutter_jailbreak_detection_plus](https://github.com/yazanalkamsheh/flutter_jailbreak_detection_plus) · [#9](https://github.com/yazanalkamsheh/flutter_jailbreak_detection_plus/pull/9) | Added iOS Swift Package Manager support alongside CocoaPods, with no Dart API changes. Shipped in v1.10.8. | ~63K downloads/mo |
| [is_lock_screen2](https://github.com/Wing-Li/flutter_is_lock_screen2) · [#10](https://github.com/Wing-Li/flutter_is_lock_screen2/pull/10) | Added iOS SPM support alongside CocoaPods. Shipped in v2.1.0. | |

Detailed write-ups: [open-source-contributions](https://github.com/TeddyYeung/open-source-contributions)

**In review**
- [flutter/flutter #196029](https://github.com/flutter/flutter/pull/196029): [web] decode images once in `instantiateImageCodecWithSize` instead of twice
- [appsflyer_sdk #456](https://github.com/AppsFlyerSDK/appsflyer-flutter-plugin/pull/456): fix iOS callback ownership when the plugin is registered on more than one FlutterEngine
- [datetime_setting #10](https://github.com/fuadarradhi/datetime_setting/pull/10): iOS Swift Package Manager support

## Packages

- **[flutter_jailbreak_guard](https://pub.dev/packages/flutter_jailbreak_guard)** ([GitHub](https://github.com/TeddyYeung/flutter_jailbreak_guard)): jailbreak and root detection with SPM and CocoaPods support. A drop-in replacement for [`flutter_jailbreak_detection_plus`](https://pub.dev/packages/flutter_jailbreak_detection_plus), with an option to pin the BSD-2 licensed `IOSSecuritySuite` 1.9.x.
- **[flutter_mute_plus](https://pub.dev/packages/flutter_mute_plus)** ([GitHub](https://github.com/TeddyYeung/flutter_mute_plus)): maintained fork of the unmaintained [`flutter_mute`](https://pub.dev/packages/flutter_mute), updated for AGP 8/9, Xcode 16+ and SPM. 160/160 pub points.
