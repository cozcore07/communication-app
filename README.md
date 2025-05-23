# 📱 Cross-Platform Communication App

A real-time communication mobile app for iOS and Android, featuring chat, voice/video calls, and social media login—built with Flutter and integrated with a custom SDK.

---

## 🚀 Features

- 📞 One-on-one voice and video calling
- 💬 Instant chat messaging
- 🔐 Email/password and social logins (Google, Facebook, Twitter)
- 🔔 Push notifications
- 🧩 SDK integration for media and messaging
- 🧪 Tested and optimized for iOS and Android deployment
- 🧑‍🎨 Clean, modern UI with responsive layouts

---

## 🛠️ Tech Stack

- **Frontend:** Flutter (Dart)
- **Authentication:** Firebase Auth, Google Sign-In, Facebook Auth
- **Communication SDK:** Custom SDK (provided)
- **Push Notifications:** Firebase Cloud Messaging (FCM)
- **Design:** Material Design

---

## 📂 Project Structure

```
communication_app/
├── lib/
│   ├── main.dart
│   ├── screens/
│   ├── widgets/
│   └── services/
├── android/
├── ios/
├── pubspec.yaml
└── README.md
```

---

## ⚙️ Setup & Installation

1. **Clone the repo:**
   ```bash
   git clone https://github.com/your-username/communication_app.git
   cd communication_app
   ```

2. **Install dependencies:**
   ```bash
   flutter pub get
   ```

3. **Add SDK credentials & config files:**
   - Add `google-services.json` for Android
   - Add `GoogleService-Info.plist` for iOS

4. **Run on device or emulator:**
   ```bash
   flutter run
   ```

---

## 📦 Deployment

- Configure app signing for Android and iOS
- Build release versions:
  ```bash
  flutter build apk --release
  flutter build ios --release
  ```

## 📜 License

This project is licensed for demo and development purposes. Contact us for full licensing and production deployment options.

