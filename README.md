⚡️ FlashChat
FlashChat is a modern, real-time chat application for Android. It's built with a 100% Kotlin-first approach, featuring a sleek UI crafted with Jetpack Compose and powered by Firebase for backend services. This project is a perfect showcase of modern Android development best practices.

✨ Core Features
🔐 Secure Authentication: Easy and secure user sign-up and login powered by Firebase Authentication.

💬 Real-time Messaging: Instant message delivery and synchronization using Firebase Cloud Firestore.

📱 Modern & Responsive UI: A beautiful, clean, and responsive user interface built entirely with Jetpack Compose.

🚀 Kotlin-First: Developed entirely in Kotlin, leveraging coroutines for asynchronous operations.

🛠️ Technology Stack
UI: Jetpack Compose

Language: Kotlin

Backend: Firebase (Authentication & Cloud Firestore)

Asynchronous Programming: Kotlin Coroutines

Build Tool: Gradle

🚀 Getting Started
Follow these steps to get a local copy of the project up and running on your machine.

1. Prerequisites
Android Studio (Arctic Fox or newer is recommended)

A Google account to create a Firebase project

2. Clone the Repository
git clone https://github.com/Krishkevin12/ChatConnect_A_Real_Time_Chat_and_Communication_Appt.git
cd FlashChat

3. Firebase Setup
This app requires a Firebase project to handle authentication and the real-time database.

Go to the Firebase Console and create a new project.

Add a new Android app to your project:

Use the applicationId found in the app/build.gradle file.

You can skip the SHA-1 key for now.

Download the google-services.json file provided by Firebase.

Place the downloaded google-services.json file into the app/ directory of the project.

In the Firebase Console, navigate to the Authentication section and enable the Email/Password sign-in method.

Navigate to the Cloud Firestore section and create a database. Start in test mode for easy setup (you can secure it later with security rules).

4. Build and Run
Open the project in Android Studio.

Let Gradle sync all the dependencies.

Run the app on an Android emulator or a physical device.

🤝 Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

