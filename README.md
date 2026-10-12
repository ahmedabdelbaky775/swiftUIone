# swiftUIone 📱

A modern iOS application built with **SwiftUI** demonstrating core UI components, interactive 3D rotation animations, custom gradient transitions, dynamic Grid layouts, and multi-view navigation with form validation.

---

## ✨ Features

- **Interactive 3D Animations:** Dynamic `rotation3DEffect` and spring-like transitions triggered by tap gestures.
- **Dynamic Gradients:** Smooth transition between linear color gradients and layout alignments.
- **Adaptive Grid Layout:** Utilizes SwiftUI's `Grid` and `GridRow` with custom column spans (`gridCellColumns`).
- **User Input & Validation:** Form inputs for user data with number-pad validation and conditional navigation feedback.
- **Navigation Flow:** Structured using `NavigationStack` passing data seamlessly to a detailed `ResultView`.

---

## 🛠 Tech Stack & Requirements

- **Language:** Swift 5.9+
- **Framework:** SwiftUI
- **Minimum iOS Version:** iOS 16.0+
- **IDE:** Xcode 15.0+

---

## 📂 Project Structure

```text
swiftUIone/
├── ContentView.swift      # Main container handling state, inputs, and animations
│   ├── ContentView        # Primary screen with hero animation, grid, and inputs
│   ├── Resultview         # Destination view validating and displaying submitted data
│   └── Rect               # Reusable styled component for custom grid cells
└── swiftUIoneApp.swift    # Application entry point



![Uploading Screenshot 2026-10-12 at 1.05.14 PM.png…]()
![Uploading Screenshot 2026-10-12 at 1.05.42 PM.png…]()






