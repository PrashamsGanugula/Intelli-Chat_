# Intelli-Chat

## Introduction

Welcome to Intelli-Chat! This real-time messaging application is designed to provide users with a seamless and interactive messaging experience. With features similar to WhatsApp, including read status, last seen, and intelligent response generation, Intelli-Chat is your go-to app for instant communication.

## Features

- **Real-Time Messaging**: Send and receive messages instantly using Firebase.
- **Google Sign-In**: Easily sign in with your Google account, no need for a separate account or mobile number.
- **User Profiles**: Create user profiles with photos, a brief description, last-seen status, and account creation date.
- **Message Read Status**: Know when your messages have been read by the recipient.
- **Message Deletion and Editing**: Delete and edit your sent messages.
- **Smart Reply Generation**: Get intelligent reply suggestions using MLKit TensorFlow Lite for on-device machine learning.

## Screens

### Chat Screen

- Real-time messaging interface.
- Displays message read receipts and last-seen status.
- Options to delete and edit messages.

### Home Screen

- Overview of recent chats.
- Navigation to other screens such as profile and settings.

### Login Screen

- Google Sign-In for user authentication.
- Simple and intuitive login interface.

### Profile Screen

- View and edit user profiles.
- Upload profile photos.
- Display last-seen status and account creation date.

### Registration Screen

- Register new users with email.
- Collect necessary user information for profile creation.

### Splash Screen

- Initial loading screen with app logo.
- Transitions to the welcome screen.

### View Profile Screen

- View other users' profiles.
- Display user information such as photo, about, and last-seen status.

### Welcome Screen

- Introduction to the app for first-time users.
- Navigation to login or registration screens.

## Technical Details

### Theming

- Utilizes Flutter themes for a cohesive and branded user experience.
- Custom color palettes using hex codes.

### Navigation

- Implements multi-page navigation using Flutter Routes and Navigator.

### Widgets

- Extensive use of custom Flutter Widgets.
- GestureDetector Widget for detecting user interactions beyond basic taps.

### Code Architecture

- Refactored and modularized code for better maintainability.
- Composition over inheritance approach for building custom UI components.

### Performance

- Efficient state management ensuring smooth and responsive UI.
- On-device machine learning for intelligent reply generation using MLKit TensorFlow Lite.

## Future Plans

- **Enhanced Messaging Features**: Adding voice and video calling capabilities.
- **Group Chats**: Implementing group chat functionality.
- **User Authentication**: Enhancing security with two-factor authentication.
- **Rich Media Messaging**: Supporting multimedia messages including images, videos, and audio.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Set up android studio for flutter environment](https://www.youtube.com/watch?v=hfz_AraTk_k&feature=youtu.be&ab_channel=GeeksforGeeks)
- [Integrate Firebase in the app](https://www.youtube.com/watch?v=sz4slPFwEvs)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Setting up the project in your local environment💻

1. Clone this repository.
2. After Cloning, open the project in android studio
3. Create a new project on [Firebase Console](https://console.firebase.google.com/)
4. Activate Email SignIn in Firebase auth, and activate Firebase Firestore and Firebase Storage in **test mode**.
5. Integrate firebase using the tutorial mentioned above to use your own database (Necessary step else the app wont work)
6. Run `flutter pub get` to get the dependencies.
7. Finally, run the app:

```
flutter run
```
7. To build the apk of the app, you can use the following command
```
flutter build apk --release
```
You can find the apk in build/app/outputs/flutter-apk folder
You can refer the following video for more [details](https://youtu.be/TOgfbyw6-Mw)

## Tech Stack

- **Flutter:** For building the user interface.
- **Firebase:** For real-time messaging, authentication, and data storage.
- **Firestore:** For storing chat messages and user data.
- **MLKit (TensorFlow Lite):** For generating smart replies using on-device machine learning.
