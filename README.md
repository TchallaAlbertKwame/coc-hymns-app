# COC Hymns App Release Packages (V3.0.1)

Welcome to the official release packages and distribution assets for **COC Hymns (Version 3.0.1+30)**.

---

## 📂 Store Submissions & Release Artifacts

All pre-built production files are organized cleanly in their respective directories below:

### 1. 🤖 Android (`android/`)
| File | Size | Destination / Purpose |
| :--- | :--- | :--- |
| **[`COC-HYMNS-V3.0.1.aab`](android/COC-HYMNS-V3.0.1.aab)** | **67 MB** | **Google Play Console** (Required format for publishing to Google Play Store). Automatically splits and delivers tiny 16MB packages to user devices. |
| **[`COC-HYMNS-V3.0.1-arm64-v8a.apk`](android/COC-HYMNS-V3.0.1-arm64-v8a.apk)** | **16.8 MB** | Direct download for 95%+ of modern smartphones (super-fast, optimized). |
| **[`COC-HYMNS-V3.0.1-armeabi-v7a.apk`](android/COC-HYMNS-V3.0.1-armeabi-v7a.apk)** | **16.5 MB** | Direct download for older 32-bit Android phones. |
| **[`COC-HYMNS-V3.0.1-universal.apk`](android/COC-HYMNS-V3.0.1-universal.apk)** | **34 MB** | Universal direct download APK (contains all ABIs, compatible with all devices). |

### 2. 🍏 Apple iOS (`ios/`)
| File | Size | Destination / Purpose |
| :--- | :--- | :--- |
| **[`COC-HYMNS-V3.0.1-Runner.app.zip`](ios/COC-HYMNS-V3.0.1-Runner.app.zip)** | **21 MB** | **Apple App Store & TestFlight**. Standalone production release app archive. To submit directly via Xcode or Transporter, codesign with your Apple Developer Team ID or run `flutter build ipa`. |

### 3. 🛡️ Obfuscation Debug Symbols (`symbols/`)
| File | Destination / Purpose |
| :--- | :--- |
| **[`android-symbols-v3.0.1.zip`](symbols/android-symbols-v3.0.1.zip)** | Upload to **Google Play Console** -> *App Bundle Explorer* -> *Downloads* -> *Upload Native Debug Symbols / Deobfuscation File* (allows Play Console to show demangled crash stack traces). |
| **[`ios-symbols-v3.0.1.zip`](symbols/ios-symbols-v3.0.1.zip)** | Upload to **App Store Connect** / Crashlytics for iOS crash reporting and stack trace deobfuscation. |

---

## 🆕 What's New in V3.0.1
- 📚 **Modular Hymn Books Library**: Organize your hymns like a personal bookshelf. Manage **Sacred Selections (SS)**, **Songs of the Church (SOC)**, **Twi**, **Ewe**, **Ga**, **Dangme (274 hymns, praises & choruses)**, **Twi Choruses**, and **Songs of Praises**.
- 🛡️ **Guarded Gesture Controls**: Smooth swiping across iOS and Android without trackpad or multi-touch gesture crashes.
- 📺 **YouTube Fallback System**: Instant fallback search and direct link to official Church of Christ YouTube channel whenever direct audio is unavailable.
- 🎨 **Unified Details AppBar**: Standardized modern presentation across all local language and standard hymnals.
- ⚡ **Optimized APKs**: Shrunk per-device download size to just ~16MB with modern code obfuscation.
