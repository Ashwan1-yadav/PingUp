<h1 align="center">
   PingUp.io
</h1>

<h3 align="center">
  End-to-end encrypted mobile application

PingUp.io is an end-to-end encrypted mobile application built with [Expo](https://expo.dev) and React Native. This application ensures secure, private communication with encryption that protects your messages from end to end.

## About

PingUp.io provides a secure messaging platform where all communications are encrypted end-to-end, ensuring that only you and your intended recipients can read your messages. Built with modern mobile development technologies, PingUp.io offers a seamless and secure communication experience.

## Getting Started

### Prerequisites

- Node.js (v18 or later recommended)
- npm or yarn package manager
- Expo CLI (installed globally or via npx)
- For iOS development: Xcode and iOS Simulator (macOS only)
- For Android development: Android Studio and Android Emulator

### Installation & Setup

1. **Install dependencies**

   ```bash
   npm install
   ```

2. **Start the development server**

   ```bash
   npm start
   # or
   npx expo start
   ```

3. **Run on your preferred platform**

   After starting the development server, you can run the app on:
   
   - **iOS Simulator** (macOS only):
     ```bash
     npm run ios
     # or press 'i' in the Expo CLI
     ```
   
   - **Android Emulator**:
     ```bash
     npm run android
     # or press 'a' in the Expo CLI
     ```
   
   - **Web Browser**:
     ```bash
     npm run web
     # or press 'w' in the Expo CLI
     ```
   
   - **Expo Go** (for quick testing on physical devices):
     - Install Expo Go app on your iOS or Android device
     - Scan the QR code displayed in the terminal or browser
     - Note: Some native features may be limited in Expo Go

### Development

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction) with Expo Router.

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
