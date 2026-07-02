<div align="center">

# 🫧 Glass Effect Container — SwiftUI

**A hands-on demo of iOS 26's Liquid Glass APIs — morphing, unioning, and animating glass effects in SwiftUI.**

![Platform](https://img.shields.io/badge/Platform-iOS_26-black?style=flat-square&logo=apple)
![Swift](https://img.shields.io/badge/Swift-5.0-orange?style=flat-square&logo=swift)
![SwiftUI](https://img.shields.io/badge/SwiftUI-Liquid_Glass-blue?style=flat-square)
![Xcode](https://img.shields.io/badge/Xcode-26-147EFB?style=flat-square&logo=xcode)
![Stars](https://img.shields.io/github/stars/ahmetbostanciklioglu/Glass_Effect_SwiftUI?style=flat-square&color=6E48AA)
![Last Commit](https://img.shields.io/github/last-commit/ahmetbostanciklioglu/Glass_Effect_SwiftUI?style=flat-square&color=4776E6)

</div>

## 📖 Overview

Glass Effect Container is a small SwiftUI sample that explores Apple's new **Liquid Glass** design system introduced in iOS 26. It renders a photo card with a floating control that expands into a set of glass buttons, showcasing how `GlassEffectContainer` coordinates and morphs multiple glass elements into a single fluid surface. The project is a focused learning reference for the `.glassEffect`, `.glassEffectUnion`, and `.buttonStyle(.glass)` modifiers.

## ✨ Features

- **`GlassEffectContainer`** groups nearby glass views so they blend and morph together with a configurable spacing.
- **`.glassEffectUnion(id:namespace:)`** fuses two icons (a heart and a magnifying glass) into one continuous glass capsule.
- **Expand / collapse animation** driven by a `.glass` styled button and a `withAnimation(.smooth(...))` transition.
- **`.buttonStyle(.glass)`** applies the native Liquid Glass appearance to an interactive control.
- Ships with an inline note on `.glassEffectTransition(.identity)` for opting out of the morphing effect.

## 📸 Preview

<div align="center">

<img width="1731" height="752" alt="Glass effect container demo" src="https://github.com/user-attachments/assets/d1d8627d-6d6c-46ad-b02a-62fc0106b5bd" />
<img width="1701" height="764" alt="Expanded glass buttons" src="https://github.com/user-attachments/assets/a2b90fd3-c875-4677-a512-c25d43174618" />
<img width="1726" height="763" alt="Glass effect union" src="https://github.com/user-attachments/assets/c8f519ec-d096-419c-9817-34169874f91c" />
<img width="1052" height="631" alt="Liquid Glass button" src="https://github.com/user-attachments/assets/5b8d384b-bc7e-4d22-912e-5ba5918dcd67" />

</div>

## 🚀 Getting Started

```bash
git clone https://github.com/ahmetbostanciklioglu/Glass_Effect_SwiftUI.git
cd Glass_Effect_SwiftUI
open GlassEffectContainer.xcodeproj
```

Then select an iOS 26 simulator (or a device running iOS 26) and press **⌘R** to build and run.

## 📋 Requirements

- iOS 26.1 or later
- Xcode 26 or later
- Swift 5.0

## 🧑‍💻 Author

**Ahmet Bostancıklıoğlu** — [@ahmetbostanciklioglu](https://github.com/ahmetbostanciklioglu) · ahmetbostancikli@gmail.com

---

> ⭐ If this helped you, consider giving the repo a star!
