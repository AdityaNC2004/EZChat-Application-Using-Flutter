# EZChat-Application-Using-Flutter

## Overview

EZChat is a real-time chat application built using the Flutter framework and Dart programming language. 
The application leverages Firebase for authentication and real-time data synchronization, providing users with a seamless and responsive chatting experience.
This application allows users to chat in real-time, share multimedia content, and enjoy a seamless messaging experience. 
The integration with Firebase ensures reliable data storage and synchronization across multiple devices.

## Features

- Real-time messaging: Experience instant messaging with real-time updates.
- Multimedia support: Share images and videos seamlessly within the chat.
- Authentication: Firebase authentication ensures secure access to the application.
- Cloud Firestore: Firebase's Cloud Firestore is used for efficient data storage and synchronization.
- User-friendly interface: Intuitive design for a smooth user experience.

## Prerequisites

Before you begin, ensure that you have the following installed:

- [Flutter](https://flutter.dev/docs/get-started/install)
- [Firebase Account](https://firebase.google.com/)

## Getting Started

1. Download the repository:


2. Navigate to the project directory:

    cd EZChat

3. Install dependencies:

    flutter pub get

4. Set up Firebase:
   
    - Create a new project on the [Firebase Console](https://console.firebase.google.com/).
    - Add an Android and/or iOS app to your Firebase project.
    - Download the `google-services.json` (Android) and/or `GoogleService-Info.plist` (iOS) files and place them in the respective app directories (`android/app` and `ios`).
    - Enable Authentication and Firestore in your Firebase project.

5. Run the application:

    flutter run

## Configuration

Update the Firebase configuration in `lib/utils/firebase.dart` with your Firebase project configuration:

const String firebaseApiKey = 'YOUR_API_KEY';
const String firebaseAuthDomain = 'YOUR_AUTH_DOMAIN';
const String firebaseDatabaseURL = 'YOUR_DATABASE_URL';
const String firebaseProjectId = 'YOUR_PROJECT_ID';
const String firebaseStorageBucket = 'YOUR_STORAGE_BUCKET';
const String firebaseMessagingSenderId = 'YOUR_MESSAGING_SENDER_ID';
const String firebaseAppId = 'YOUR_APP_ID';
const String firebaseMeasurementId = 'YOUR_MEASUREMENT_ID';


## Contact

For issues and inquiries, please contact [adityanchavan123@gmail.com](mailto:adityanchavan123@gmail.com).

Happy Coding! 🚀
