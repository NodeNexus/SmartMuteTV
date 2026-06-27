# SmartMute TV

<div align="center">

# 📺 SmartMute TV

### Automatically mute advertisements. Enjoy uninterrupted entertainment.

[![Android TV](https://img.shields.io/badge/Android-TV-34A853?style=for-the-badge\&logo=android\&logoColor=white)]()
[![Kotlin](https://img.shields.io/badge/Kotlin-2.x-7F52FF?style=for-the-badge\&logo=kotlin\&logoColor=white)]()
[![Jetpack Compose](https://img.shields.io/badge/Jetpack-Compose-4285F4?style=for-the-badge)]()
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)]()

*A modern Android TV utility that detects advertisements across supported streaming apps and automatically mutes audio until your content resumes.*

</div>

---

## ✨ Features

* 🔇 Automatic ad muting
* 📺 Android TV optimized interface
* 🎯 Accessibility-based detection
* 📊 Usage statistics
* 📜 Detection logs
* ⚙️ Customizable sensitivity
* 🎨 Beautiful Material 3 TV UI
* 🚀 Lightweight background service
* 🔊 Automatic volume restoration
* 🌙 Modern dark theme

---

## Supported Platforms

* YouTube
* ZEE5
* JioHotstar
* SonyLIV
* MX Player
* Prime Video
* Netflix
* Easily extendable for additional apps

> **Note:** Actual functionality depends on the accessibility information exposed by each streaming application and Android platform capabilities.

---

## Tech Stack

* Kotlin
* Jetpack Compose for TV
* Material 3
* MVVM Architecture
* Clean Architecture
* Hilt
* Kotlin Coroutines
* Flow
* DataStore
* Accessibility Service
* Foreground Service

---

## Project Structure

```
app/
 ├── data/
 ├── domain/
 ├── presentation/
 ├── services/
 ├── accessibility/
 ├── repository/
 ├── navigation/
 ├── ui/
 ├── model/
 ├── utils/
 └── di/
```

---

## Screens

* Dashboard
* Monitoring
* Statistics
* Logs
* Settings
* About

---

## Roadmap

* AI-assisted detection
* Detection confidence scoring
* Better platform recognition
* Plugin architecture
* Analytics dashboard
* TV remote shortcuts
* Localization
* Performance improvements

---

## Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/SmartMuteTV.git
```

Open with Android Studio and run on an Android TV device or emulator.

---

## Permissions

* Accessibility Service
* Foreground Service
* Usage Statistics (optional)
* Audio Control

---

## Disclaimer

SmartMute TV uses supported Android APIs to automate audio muting based on available accessibility and system information. It does **not** modify streaming applications, bypass DRM, or intercept network traffic. Compatibility varies depending on how individual apps expose their interfaces.

---

## Contributing

Pull requests, feature requests, and bug reports are welcome.

---

## License

MIT License

---

<div align="center">

Made with ❤️ for Android TV users.

</div>
