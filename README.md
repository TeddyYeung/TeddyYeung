# Hi, I'm Teddy 👋

## ✅ Merged Contributions

### [`flutter/packages`](https://github.com/flutter/packages) (`image_picker_ios`) — [PR #12267](https://github.com/flutter/packages/pull/12267) · shipped in **0.8.13+10**
`Official Flutter team repository` · `image_picker ~5M downloads/mo` · `7.7K+ likes`
- Fixed a long-standing iOS bug ([flutter/flutter#132154](https://github.com/flutter/flutter/issues/132154), open since 2023) where selecting an image that `UIImage` cannot decode (e.g. AVIF) via PHPicker left the picker hanging or was treated as a successful save.
- The operation now completes with the existing `invalid_image` error; added a regression test verifying that no path is returned and the `NSOperation` finishes.
- Carried it through the full flutter/packages process: Google CLA, several upstream merge-conflict resolutions, and porting the test to the new Swift Testing suite after the Objective-C tests were migrated.

### [`flutter_foreground_task`](https://github.com/Dev-hwang/flutter_foreground_task) — [PR #387](https://github.com/Dev-hwang/flutter_foreground_task/pull/387) · shipped in **v11.0.0**
`~219K downloads/mo` · `580+ likes` · `+1,276 LOC / 24 files`
- Added iOS **Swift Package Manager** support to one of the most-used background-execution plugins in Flutter.
- Solved SPM's no-mixed-language-target constraint by isolating a pure-Swift SPM target while keeping the ObjC + Swift CocoaPods path fully intact — **zero breaking changes** for existing users.
- Made implicit umbrella-header imports explicit (`Flutter`, `UserNotifications`) so the module compiles standalone under SPM.

### [`image_gallery_saver_plus`](https://github.com/ArmanKT/image_gallery_saver_plus) — [PR #3](https://github.com/ArmanKT/image_gallery_saver_plus/pull/3)
`~136K downloads/mo` · `120+ likes`
- Diagnosed and fixed a broken `Package.swift` that declared a non-existent `FlutterFramework` dependency, which made **SPM resolution fail for every consumer**.
- Aligned the iOS deployment target with the podspec and brought the manifest in line with Flutter's official plugin SPM template.

### [`is_lock_screen2`](https://github.com/Wing-Li/flutter_is_lock_screen2) — [PR #10](https://github.com/Wing-Li/flutter_is_lock_screen2/pull/10) · shipped in **v2.1.0**
`+409 / −148 LOC · 23 files`
- Added iOS SPM support with dual-path compatibility; verified builds with SPM enabled and with CocoaPods retained.

## 📦 Maintained Packages

### [`flutter_mute_plus`](https://pub.dev/packages/flutter_mute_plus) — [GitHub](https://github.com/TeddyYeung/flutter_mute_plus) · **v1.1.0**
`160/160 pub points` · `Android + iOS`
- Maintained fork of the unmaintained [`flutter_mute`](https://pub.dev/packages/flutter_mute): check or toggle the device ringer mode (normal, silent, vibrate) and listen for changes.
- Brought it up to date with **AGP 8/9**, **Xcode 16+** and **Swift Package Manager** support, and shipped pending community fixes the original repository could not accept.
- Submitted to [Flutter Gems](https://fluttergems.dev/) ([PR #1013](https://github.com/fluttergems/fluttergems/pull/1013)).
