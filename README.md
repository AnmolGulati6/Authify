# Authify
Authify is an iOS application that provides user authentication functionalities such as login, signup, and password reset using Firebase Authentication. The app is built using SwiftUI and interacts with Firestore for storing user data. Stored for future use

## Features
- User Registration: Users can create a new account by providing their full name, email address, and password
- User Login: Registered users can log in to their accounts using their email address and password
- Password Reset: Users can request a password reset email to reset their account password if they forget it
- User Data Storage: User information, including full name, email address, and unique identifier, is stored in Firestore

## Prerequisites
Before running the application, ensure that you have the following:
- Xcode installed on your macOS device.
- An active Firebase project set up with Firebase Authentication and Firestore

## Usage
Upon launching the Authify app, you will see the login screen. From there, you can:
- Create a new account by tapping on the "Sign Up" button and providing your full name, email address, and password
- Log in to an existing account by entering your email address and password
- Reset your password by tapping on the "Forgot Password?" button and following the instructions
  - Enter your email, and you'll recieve an email to change your password
- Explore other features and functionalities of the app based on your requirements

## Dependencies
- Firebase/Authentication: Provides Firebase Authentication services for user login, signup, and password reset.
- FirebaseFirestoreSwift: Allows interaction with Firestore to store and retrieve user data.
- SwiftUI: The user interface framework used to develop the application's views and components.


