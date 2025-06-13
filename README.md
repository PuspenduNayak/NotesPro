# 📓 NotesPro

**NotesPro** is a personal, secure, and easy-to-use note-taking Android application built using **Java** and **Firebase**. It allows users to create, edit, and manage their notes in the cloud with a clean and modern user interface.

![App Icon](note_pro_icon.png)

---

## ✨ Features

- 🔐 User Authentication (Firebase)
- ☁️ Real-time Firestore DB integration
- ✏️ Create, Read, Update, Delete notes
- 📱 Beautiful Material Design UI
- 🚀 Fast splash screen and smooth navigation
- 🔒 User-specific notes isolation
- 🌐 Internet connectivity check

---

## 📸 App Screenshot

![Screenshot](https://github.com/PuspenduNayak/NotesPro/blob/master/Screenshot.png?raw=true)


---

## 🛠️ Tech Stack

- **Java** (Android App Development)
- **Firebase Authentication** (User login/signup)
- **Cloud Firestore** (Realtime NoSQL DB)
- **FirebaseUI Firestore** (Effortless integration)
- **Material Design Components**
- **RecyclerView** for list display
- **AndroidX libraries**
- **Gradle (Kotlin DSL)** for build configuration

---

## 📁 Project Structure (Simplified)

NotesPro/
│
└── app/
  └── src/
  └── main/
    ├── java/com/example/notespro/
    │ ├── CreateAccountActivity.java
    │ ├── LoginActivity.java
    │ ├── MainActivity.java
    │ ├── Note.java
    │ ├── NoteAdapter.java
    │ ├── NoteDetailsActivity.java
    │ ├── SplashActivity.java
    │ └── Utility.java
    └── res/
    ├── layout/ (UI XMLs)
    ├── drawable/ (Assets)
    └── values*/ (Themes & Strings)



---

## 🔧 Setup Instructions

### 🔨 Prerequisites

- Android Studio (latest version)
- Firebase project with Authentication & Firestore enabled
- Google Services JSON

### ⚙️ Steps

1. **Clone the repo**
   ```bash
   git clone https://github.com/PuspenduNayak/NotesPro.git
2. Open in Android Studio

3. Set up Firebase
    ->Go to Firebase Console
    ->Add an Android app using package name: com.example.notespro
    ->Download google-services.json and place it inside /app

4. Sync Gradle

5. Run the app on emulator or physical device

✅ Functionality Overview
SplashActivity: Launch screen logic

LoginActivity: Handles user sign-in

CreateAccountActivity: Registration logic

MainActivity: Lists all notes for the user

NoteDetailsActivity: View, update, delete a note

NoteAdapter: RecyclerView adapter

Note.java: Model class for Firestore

Utility.java: Utility functions (e.g., showToast, formatDate)

🧠 Future Enhancements
  🔍 Search and filter notes

  🌙 Dark Mode toggle

  📎 Add image/file attachments

  🌐 Offline note saving (Firestore caching)

  📝 Rich-text/Markdown note support

🧪 Testing
  Unit tests: ExampleUnitTest.java

  UI Tests: Espresso-ready structure

  Use Android Studio test runner

🙋‍♂️ About the Developer
  Developed by Puspendu Nayak
  An enthusiastic Java & Android developer passionate about building impactful, efficient apps.
💡 “Write your ideas, anywhere, anytime — with NotesPro.”

yaml
Copy
Edit

---

### 📥 To Use:

1. Copy the above content into a new file named `README.md`.
2. Place it in the **root of your repository** (`NotesPro/README.md`).
3. Commit and push:

```bash
git add README.md
git commit -m "Add detailed README"
git push origin main
