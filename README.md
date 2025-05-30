# 📱 Android Chat App (WhatsApp-Inspired Clone)

Welcome to my very first Android Studio project! This application is a feature-rich chat app inspired by WhatsApp, built from the ground up to help me learn and demonstrate modern Android development practices. While it doesn’t include every feature of WhatsApp, it covers all the core essentials: real-time messaging, group chats, internet calling, phone number authentication, and status sharing.

---

## 🌟 Project Overview

This project is a comprehensive chat application that enables users to communicate seamlessly with their friends and groups. The app leverages Firebase for authentication and real-time data synchronization, ensuring a secure and responsive user experience. My goal was to replicate the most important functionalities of popular messaging apps, focusing on usability, reliability, and a clean interface.

---

## ✨ Key Features

- **Phone Number Authentication:**  
  Users can sign up and log in securely using their phone number, powered by Firebase Authentication.

- **Add Friends from Contacts:**  
  Effortlessly add friends who are already using the app by syncing with your device’s contact list.

- **Private & Group Chatting:**  
  Start one-on-one conversations or create group chats for collaborative discussions. Group management features allow you to add or remove members easily.

- **Internet Calling:**  
  Make high-quality voice calls to your contacts over the internet, with a simple and intuitive call interface.

- **Status Updates (Stories):**  
  Share photos, text, or videos as status updates, visible to your contacts for 24 hours—just like WhatsApp Status or Instagram Stories.

- **Modern & Responsive UI:**  
  Designed with Material Design principles, the app provides a smooth and visually appealing user experience.

- **Real-Time Messaging:**  
  All chats update instantly using Firebase Realtime Database, ensuring conversations stay up-to-date.

- **Notifications:**  
  Receive push notifications for new messages and calls (optional, can be enhanced in future versions).


---

## 📸 Screenshots

<!-- Add actual screenshots in your repository and update the paths below -->
<p align="center">
  <img src="screenshots/login.png" width="200" alt="Login Screen"/>
  <img src="screenshots/home.png" width="200" alt="Home Screen"/>
  <img src="screenshots/chat.png" width="200" alt="Chat Screen"/>
  <img src="screenshots/status.png" width="200" alt="Status Screen"/>
</p>

---

## 📚 Table of Contents

- [Project Overview](#-project-overview)
- [Key Features](#-key-features)
- [Screenshots](#-screenshots)
- [Future Improvements](#-future-improvements)
- [Contributing](#-contributing)
- [License](#-license)

---

## Installation

### Using Android Studio (Emulator/Physical Device)

1.  **Clone the Repository:**

    ```bash
    git clone https://github.com/Priyanshu-Ghosh-unplugged/Food_Loops
    ```

2.  **Open in Android Studio:**

    -   Open Android Studio.
    -   Select "Open an existing Android Studio project".
    -   Navigate to the cloned repository directory and select the `build.gradle` file.

3.  **Build and Run:**

    -   Connect your physical Android device via USB with USB debugging enabled, or start an Android Emulator.
    -   Click the "Run" button (green play icon) in Android Studio.
    -   Select your target device/emulator.
    -   The app will be built and installed on the selected device/emulator.

### Direct APK Installation (Physical Device)

1.  **Download the APK:**

    -   Navigate to the `app/build/outputs/apk/release/` or `app/build/outputs/apk/debug/` directory in your repository.
    -   Download the `app-release.apk` (or `app-debug.apk`) file to your computer.
    -   Transfer the APK file to your Android device via USB or other means.

2.  **Enable "Install Unknown Apps":**

    -   On your Android device, go to "Settings" > "Apps & notifications" (or similar).
    -   Find and tap "Special app access" or "Install unknown apps".
    -   Select the file manager app you used to transfer the APK.
    -   Toggle the "Allow from this source" switch to enable installation.

3.  **Install the APK:**

    -   Use your file manager app to navigate to the location of the APK file.
    -   Tap the APK file to begin the installation process.
    -   Follow the on-screen instructions to complete the installation.

---

## ▶️ Usage

- **Sign Up / Log In:**  
Enter your phone number to receive an OTP and authenticate via Firebase.

- **Add Friends:**  
Sync your contacts and add friends who also use the app.

- **Start Chatting:**  
Select a contact or group to begin chatting. Send text messages, images, or make internet calls.

- **Create Groups:**  
Start a new group chat, add members, and manage group details.

- **Share Status:**  
Post a status update (photo, text, or video) visible to your contacts for 24 hours.

---

## 💡 Future Improvements

- **Media Sharing:** Send images, videos, and documents in chats.
- **Profile Customization:** Add profile pictures and status messages.
- **Enhanced Notifications:** Implement advanced push notifications for messages and calls.
- **Message Reactions & Replies:** Add emoji reactions and threaded replies.
- **Dark Mode:** Support for dark/light theme switching.

---

## 🤝 Contributing

I welcome contributions, suggestions, and feedback! To contribute:

1. **Fork** the repository.
2. **Create a new branch** for your feature or bugfix.
3. **Commit** your changes.
4. **Push** to your branch.
5. **Open a Pull Request** with a clear description of your changes.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).  
Feel free to use, modify, and distribute as per the license terms.


> **Thank you for checking out my first Android project! Your feedback, suggestions, and contributions are highly appreciated. I hope this app inspires you as much as it has helped me learn!**
