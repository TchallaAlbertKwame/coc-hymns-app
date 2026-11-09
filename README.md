# COC Hymns App Release Packages (V3.0.1)

Welcome to the official release packages and distribution assets for **COC Hymns (Version 3.0.1+30)**.

---

## 📂 Store Submissions & Release Artifacts

All pre-built production files are organized cleanly in their respective directories below:

### 1. 🤖 Android (`android/`)
| File | Size | Destination / Purpose |
| :--- | :--- | :--- |
| **[`COC-HYMNS-V3.0.1.aab`](android/COC-HYMNS-V3.0.1.aab)** | **73 MB** | **Google Play Console** (Required format for publishing to Google Play Store). Automatically splits and delivers tiny 17MB packages to user devices. |
| **[`COC-HYMNS-V3.0.1-arm64-v8a.apk`](android/COC-HYMNS-V3.0.1-arm64-v8a.apk)** | **17.4 MB** | Direct download for 95%+ of modern smartphones (super-fast, optimized 64-bit). |
| **[`COC-HYMNS-V3.0.1-armeabi-v7a.apk`](android/COC-HYMNS-V3.0.1-armeabi-v7a.apk)** | **17.2 MB** | Direct download for older 32-bit Android phones. |
| **[`COC-HYMNS-V3.0.1-universal.apk`](android/COC-HYMNS-V3.0.1-universal.apk)** | **37 MB** | Universal direct download APK (contains all ABIs, compatible with all devices). |

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
- 📚 **Modular Hymn Books & Tab Manager**: Organize your hymns like a personal bookshelf. Manage **Sacred Selections (SS)**, **Songs of the Church (SOC)**, **Twi**, **Ewe**, **Ga**, **Dangme (274 hymns, praises & choruses)**, **Twi Choruses**, and **Songs of Praises**.
- 📌 **Pin Default Launch Hymnal**: Set any hymn book as your startup book directly from the rearrange sheet so it automatically opens first on app launch.
- 🔤 **9 Worship Typography Fonts**: Select from EB Garamond, Merriweather, Lora, Playfair Display, Cinzel, Inter, Roboto, Montserrat, and Open Sans with real-time live preview scaling.
- 🚀 **Streamlined Search & Quick Number Jump**: Type a hymn number in search and hit search/enter to leap straight to the song without any cluttered modal dialogs.
- ↔️ **Fluid Animated Swipe Transitions**: Directional slide transitions between hymns with automatic scroll-to-top reset.
- ⚙️ **Modern Grouped Settings**: Redesigned settings into clean section cards with responsive centering on desktop, tablet, and mobile.
- 📺 **YouTube Melody Player**: Interactive audio and video player with tempo controls (0.75x, 0.5x) and YouTube app deep-linking for learning 4-part acappella singing.
