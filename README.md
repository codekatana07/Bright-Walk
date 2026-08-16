🚶 BrightWalk

AI-Powered Navigation Assistant for Visually Impaired Users

BrightWalk is an Android accessibility-focused navigation application designed to help visually impaired users explore their surroundings independently. It combines computer vision, location services, voice assistance, and accessible navigation to provide contextual information about nearby places and the user's environment.

---

✨ Features

- 🗺️ Explore Nearby — Discover nearby attractions, restaurants, museums, and other points of interest.
- 📍 Location-Based Navigation — Find places around the user's current location.
- 🔊 Voice Assistance — Provides voice-based instructions and descriptions.
- 👁️ Visual Understanding — Uses camera-based AI to understand the user's surroundings.
- 🗣️ Voice Control — Designed for hands-free interaction through accessibility services.
- 🌐 Multi-Language Support — Supports multiple languages for voice instructions and descriptions.
- 🏛️ Nearby Places — Displays information such as ratings and distance from the user.
- 🎧 Audio Descriptions — Allows users to listen to information about nearby locations.
- ♿ Accessibility-First UI — Large controls, high contrast, and simple interaction patterns.

---

🛠️ Tech Stack

Technology| Purpose
Kotlin| Android application development
CameraX| Camera integration
Google ML Kit| On-device computer vision
Google Maps SDK| Maps and navigation
GPS / Location APIs| Real-time location
Text-to-Speech| Voice instructions and descriptions
Android Accessibility APIs| Accessibility and voice interaction
Jetpack Components| Modern Android architecture
Material UI| Application interface

---

📱 Screenshots

Explore Nearby

Users can explore nearby attractions, restaurants, and museums with distance, ratings, map navigation, and audio information.

<p align="center">
  <img src="screenshots/explore_nearby.jpg" width="280">
</p>---

Accessibility Setup

BrightWalk provides an accessibility setup screen where users can enable Voice Control and select their preferred language.

<p align="center">
  <img src="screenshots/accessibility.jpg" width="280">
  <img src="screenshots/language_selection.jpg" width="280">
</p>---

Voice & Language Support

The application integrates with Android's speech recognition and text-to-speech services to provide voice-based interaction.

<p align="center">
  <img src="screenshots/language_selection.jpg" width="280">
  <img src="screenshots/voice_action.jpg" width="280">
</p>---

🧭 How It Works

                ┌─────────────────────┐
                │       User          │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │   Voice / Camera    │
                │      Input          │
                └──────────┬──────────┘
                           │
              ┌────────────┴────────────┐
              ▼                         ▼
      ┌───────────────┐         ┌───────────────┐
      │  ML / Vision  │         │  Location /   │
      │   Processing  │         │  Maps APIs    │
      └───────┬───────┘         └───────┬───────┘
              │                         │
              └────────────┬────────────┘
                           ▼
                ┌─────────────────────┐
                │  Contextual Result  │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │ Voice Instructions  │
                │   & Descriptions    │
                └─────────────────────┘

---

♿ Accessibility

BrightWalk is designed with accessibility as a core requirement rather than an additional feature.

The application focuses on:

- Voice-based interaction
- Audio descriptions
- Large and clearly identifiable controls
- High-contrast interface
- Minimal visual complexity
- Hands-free interaction
- Location-aware assistance
- Multi-language voice support

---

⚠️ Development Note

When running development/debug builds on newer Android devices, Android may display a 16 KB page-size compatibility warning if one or more native ".so" libraries are not aligned for 16 KB memory pages.

This is a build/dependency compatibility issue and does not represent an application feature.

---

🚀 Getting Started

1. Clone the repository

git clone https://github.com/codekatana07/Bright-Walk.git
cd Bright-Walk

2. Open in Android Studio

Open the project using the latest stable version of Android Studio.

3. Configure API Keys

Add the required API keys for services such as:

- Google Maps
- Places / location services
- Any external AI or vision APIs used by the project

Do not commit API keys or secrets to GitHub.

4. Build and Run

Connect an Android device or start an emulator and run the application from Android Studio.

---

📂 Project Structure

BrightWalk/
│
├── app/
│   └── src/
│       └── main/
│           ├── java/
│           ├── res/
│           └── AndroidManifest.xml
│
├── screenshots/
│   ├── explore_nearby.jpg
│   ├── accessibility.jpg
│   ├── language_selection.jpg
│   ├── voice_action.jpg
│   └── compatibility_warning.jpg
│
├── build.gradle
├── settings.gradle
└── README.md

---

🎯 Project Goal

The goal of BrightWalk is to make everyday navigation and exploration more accessible by combining AI, computer vision, location intelligence, and voice interaction into a single Android application.

«See the world. Hear the way. Walk independently.»

---

👨‍💻 Built With

Made with ❤️ using Kotlin and Android with a focus on accessibility, AI, and real-world navigation.
