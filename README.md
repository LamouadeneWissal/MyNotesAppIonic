MyNotesApp
MyNotesApp is a simple, mobile-ready notes application developed using Ionic Framework, Angular, and Cordova.
The application allows users to create, view, and manage notes seamlessly, with offline support for a smooth user experience.

Table of Contents
Features

Built With

Installation

Running the Application

Building for Android

Prerequisites

Screenshots

Author

Features
Create and save notes.

Delete notes.

Responsive and mobile-friendly interface.

Offline usage support with Cordova.

Fast performance and lightweight design.

Built With
Ionic Framework

Angular

Cordova

TypeScript

Installation
Clone the Repository

bash
Copy
Edit
git clone https://github.com/LamouadeneWissal/MyNotesAppIonic.git
cd MyNotesAppIonic
Install Project Dependencies

bash
Copy
Edit
npm install
Install Global Dependencies (if not already installed)

bash
Copy
Edit
npm install -g @ionic/cli cordova
Running the Application (Development)
To run the app in your browser (for testing and development):

bash
Copy
Edit
ionic serve
The app will be available at http://localhost:8100/ by default.

Building for Android
Add the Android platform:

bash
Copy
Edit
ionic cordova platform add android
Build the Android APK (production build):

bash
Copy
Edit
ionic cordova build android --prod
Locate the APK: After building, the APK can be found at:

swift
Copy
Edit
platforms/android/app/build/outputs/apk/debug/app-debug.apk
Install the APK on a device:

Transfer the APK to your Android device.

Install manually (ensure "Install from Unknown Sources" is enabled on the device).

Prerequisites
Node.js and npm

Ionic CLI

Cordova CLI

Android Studio (for building and testing APKs)

A physical Android device or emulator (for installation)

Screenshots
<!-- Insert screenshots here if available -->
Example placeholder:


Author
Wissal Lamouadene
GitHub: @LamouadeneWissal

License
This project is licensed under the MIT License.
