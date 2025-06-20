# Ride Sharing App Prototype

"COMPANY" : CODTECH IT SOLUTIONS

"NAME" : VIVEK KUMAR RAI

"INTERN ID" : CT06DK725

"DOMAIN" : ANDROID DEVELOPMENT

"DURATION" : 6 WEEKS

"MENTOR" : NEELA SANTOSH

## Overview

The Ride Sharing App is an Android application that allows users to book rides in real-time, view nearby drivers on a map, and manage their profiles. The app integrates Google Maps API for location tracking and Firebase Authentication for secure user sign-up and login processes. 
There are two options are there 1.Driver and 2.Customer go where else you want to go. 
Here you have to first register and using those same credentials to sign in to the app.

## Features

- **User Registration & Login:** Firebase Authentication for secure sign-in.
- **Real-Time Ride Booking:** Users can book rides instantly.
- **Map Integration:** Display nearby drivers and users' location using Google Maps API.
- **Driver Location Tracking:** Real-time tracking of driver’s location.
- **Profile Management:** Users can manage their personal profiles.
- **Ride History & Fare Calculation:** Track past rides and calculate fares.

## Technology Stack

- **Programming Language:** Java
- **IDE:** Android Studio
- **Mapping Services:** Google Maps API
- **Authentication:** Firebase Authentication
- **Database:** Firebase Firestore (optional for storing ride history and user profiles)
- **Dependency Management:** Gradle


## Prerequisites

Before starting, ensure you have the following:

- **Android Studio** installed (latest version recommended)
- **Java Development Kit (JDK)** installed
- A **Google account** for accessing Firebase and Google Maps API
- An **emulator or Android device** for testing


### Set Up Firebase Authentication
Go to the Firebase Console.
Create a new project or select an existing one.
In the project settings, add your Android app:
Enter your app's package name.
Download the google-services.json file and place it in the app/ directory.
Enable authentication methods in Firebase:
Navigate to Authentication and enable the preferred sign-in methods.
### Add Dependencies
Open build.gradle (Module: app) and add the following dependencies:
gradle
```
dependencies {
    implementation 'com.google.firebase:firebase-auth:YOUR_VERSION'
    implementation 'com.google.firebase:firebase-firestore:YOUR_VERSION' // Optional
    implementation 'com.google.android.gms:play-services-maps:YOUR_VERSION'
    // Other dependencies...
}
```
Don’t forget to sync your Gradle files.
###Build the App
Connect an Android device or start an emulator.
Click the Run button (green triangle) in Android Studio.

OUTPUT

![Image](https://github.com/user-attachments/assets/c78b9134-8ad7-4117-9772-13fc84be4e02)
![Image](https://github.com/user-attachments/assets/581a3db3-395c-43f0-8374-575e95c785d0)
![Image](https://github.com/user-attachments/assets/a6cfda02-b0cb-4342-9439-2065b979cae3)
![Image](https://github.com/user-attachments/assets/96bf320f-42ce-4879-ac56-51c16fb9d267)
![Image](https://github.com/user-attachments/assets/2a0b2794-1ac4-4462-b1c5-5c5170584277)
![Image](https://github.com/user-attachments/assets/d34e87c2-dffd-4b9f-9238-e87b3be20d04)
![Image](https://github.com/user-attachments/assets/51b3777a-501d-4f97-93cf-390a0ca272c8)



