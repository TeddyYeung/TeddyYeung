# Hi, I'm Teddy 👋

**Mobile Software Engineer · Flutter & iOS platform internals**

I ship production Flutter apps and fix the native layer underneath them — build systems, plugin registration, and platform channels.
My upstream work focuses on migrating the Flutter plugin ecosystem to **Swift Package Manager** ahead of the CocoaPods trunk read-only cutoff (Dec 2026).

> *"My goal is to simplify complexity."* — Jack Dorsey

---

## 📈 Open Source Impact

| | |
|---|---|
| **Merged upstream PRs** | 3 plugins, all shipped in official pub.dev releases |
| **Reach of merged code** | **~357K downloads / month** across affected packages |
| **Community signal** | 700+ pub.dev likes on packages I contributed to |

<sub>Download figures from pub.dev, 30-day window, as of Sep 2026.</sub>

---

## ✅ Merged Contributions

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
