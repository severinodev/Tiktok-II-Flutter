# TikTok Clone - Flutter

![Flutter Version](https://img.shields.io/badge/Flutter-%5E3.11.5-blue.svg)
![Provider](https://img.shields.io/badge/Provider-6.1.5-blue.svg)

A professional TikTok clone built with Flutter, focused on clean architecture, smooth animations, and high performance. This project demonstrates how to build a scalable and modular mobile application capable of handling video playback seamlessly.

## ✨ Features

- **Vertical Video Scrolling**: Smooth, TikTok-like vertical video swiping experience.
- **Video Player Integration**: Efficient video playback using the official `video_player` plugin.
- **Clean Architecture**: Highly decoupled codebase divided into Domain, Infrastructure, and Presentation layers.
- **State Management**: Robust state management using `Provider`.
- **Micro-Animations**: Beautiful UI transitions and animations using `animate_do`.
- **Data Mocking**: Simulated API requests with local data models for quick prototyping.

## 🏗️ Architecture

This project follows **Clean Architecture** principles to ensure scalability and maintainability:

- **`domain/`**: Contains the core business logic and entities (e.g., `VideoPost`). Independent of any external packages.
- **`infrastructure/`**: Handles data models (e.g., `LocalVideoModel`) and the transformation of raw data into domain entities.
- **`presentation/`**: Contains the UI layers (Screens and Widgets) and the state managers (`Providers`).
- **`config/`**: App-wide configurations, including custom themes.
- **`shared/`**: Shared static data and mock assets.

## 🚀 Getting Started

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install) (Version 3.11.5 or higher)
- A supported IDE (VS Code, Android Studio, IntelliJ)

### Installation

1. Clone the repository (if applicable):
   ```bash
   git clone https://github.com/your-username/tiktok-clone.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Tiktok-II-Flutter
   ```
3. Install the dependencies:
   ```bash
   flutter pub get
   ```
4. Run the app:
   ```bash
   flutter run
   ```

## 📦 Key Dependencies

- [`provider`](https://pub.dev/packages/provider): State management.
- [`video_player`](https://pub.dev/packages/video_player): Video playback control.
- [`animate_do`](https://pub.dev/packages/animate_do): Elegant animations.
- [`intl`](https://pub.dev/packages/intl): Internationalization and formatting.

## 📱 Preview

https://github.com/user-attachments/assets/296805e7-5eb7-4ff0-aee7-9b13a3da03df

## 🛠️ Future Improvements

- [ ] Implement the Repository pattern to fetch videos from a real remote API.
- [ ] Add Infinite Scrolling / Pagination support.
- [ ] Implement error handling and loading states.

---
*Developed with best practices in mind.*
