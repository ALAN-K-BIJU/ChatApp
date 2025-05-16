# 💬 ChatApp

**ChatApp** is a real-time messaging Android application developed in Java. It leverages Firebase Authentication, Realtime Database, and Firebase Cloud Messaging (FCM) to provide seamless and secure communication between users.

---

## 🚀 Features

- 📲 Phone number & username-based login (OTP authentication)
- 💬 One-to-one chat with real-time updates
- 🔍 Search and connect with other users
- 🔔 Firebase Cloud Messaging for push notifications
- 👤 Profile viewing and editing
- 🎨 Smooth navigation with modern UI components

---

## 🧭 Project Structure

### 📂 Activity Files
- **`ChatActivity.java`**: Manages individual chat sessions.
- **`LoginOtpActivity.java`**: Handles OTP-based user authentication.
- **`LoginPhoneNumberActivity.java`**: Manages login using phone numbers.
- **`LoginUsernameActivity.java`**: Allows login via username.
- **`MainActivity.java`**: Primary app hub and screen controller.
- **`SearchUserActivity.java`**: Enables searching users to initiate chats.
- **`SplashActivity.java`**: Displays the splash screen during initialization.

### 🧩 Fragment Files
- **`ChatFragment.java`**: Chat UI and logic.
- **`ProfileFragment.java`**: User profile view/edit.
- **`SearchUserFragment.java`**: User search results and chat options.

### 🛎️ Service File
- **`FCMNotificationService.java`**: Firebase Cloud Messaging integration for push notifications.

---

## 🔧 Tech Stack

- **Language:** Java
- **Architecture:** MVVM
- **Database:** Firebase Realtime Database
- **Auth:** Firebase Authentication
- **Notifications:** Firebase Cloud Messaging
- **UI:** Material Design + Fragments

---

## 📸 Screenshots

<p align="center">
  <img src="https://github.com/ALAN-K-BIJU/ChatApp/blob/main/screenshots/update.jpg" alt="Update UI" width="250" height="500"/>
  <img src="https://github.com/ALAN-K-BIJU/ChatApp/blob/main/screenshots/chat1.jpg" alt="Chat Screen 1" width="250" height="500"/>
  <img src="https://github.com/ALAN-K-BIJU/ChatApp/blob/main/screenshots/chat2.jpg" alt="Chat Screen 2" width="250" height="500"/>
  <img src="https://github.com/ALAN-K-BIJU/ChatApp/blob/main/screenshots/chars.jpg" alt="User List Screen" width="250" height="500"/>
</p>

---

## 🔍 Explore the Code

Each file is well-commented and modular, making it beginner-friendly for those learning Android app development with Firebase integration.

---

## 🚀 Getting Started

### Clone & Run
```bash
git clone https://github.com/ALAN-K-BIJU/ChatApp.git

