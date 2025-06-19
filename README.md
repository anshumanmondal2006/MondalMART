# MondalMART (A basic E-Commerce Platform)

An E-Commerce app built using Flutter and Firebase featuring basic user authentication, cart management, and product listing. Includes login/logout, add/delete products from cart.

## Steps to test the application on your local machine

Follow the steps below to set up and run the project locally.

---

### 🚀 Clone the Repository

```bash
git clone https://github.com/anshumanmondal2006/MondalMART.git
cd MondalMART
```

---

### 📦 Install Dependencies

```bash
flutter pub get
```

---

### 🔧 Configure Firebase

To integrate Firebase services, follow these steps:
First, delete Firebase Integration from the project, then:
1. **Create your own Firebase Project** at [Firebase Console](https://console.firebase.google.com/).
2. **Register your app** (both Android and iOS if needed).
3. Download and add the configuration files:
   - For **Android**:  
     Place `google-services.json` inside `android/app/`.
   - For **iOS**:  
     Place `GoogleService-Info.plist` inside `ios/Runner/`.

4. Make sure you have added the appropriate Firebase SDKs and plugins in `pubspec.yaml` and at other necessary file paths.

More Firebase setup help: [firebase.flutter.dev](https://firebase.flutter.dev/docs/overview)

---

### ▶️ Run the App

Make sure an external device (phone) or emulator is running, then execute:

```bash
flutter run
```

---
## 🔌 Key Plugins & Packages in the project
- firebase_core – Core Firebase integration
- firebase_auth – User authentication
- cloud_firestore – NoSQL database for products & cart
- firebase_storage – Product image storage

## ❗ Requirements

- Flutter SDK 
- Firebase account
- Android Studio / VS Code with Flutter, Kotlin and other plugins.
- This project uses Firebase for backend services like authentication and Firestore.
- Make sure you configure Firebase before running the app.

---

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

To download the application click on the link below:
[![Download APK](https://img.shields.io/badge/Download-APK-green?logo=android)](https://drive.google.com/uc?export=download&id=1X8zXJU6YBouq2P4aEfjO6Fbrw3kKLZKR)

## 📃 License

This project is licensed under the [MIT License](LICENSE).


