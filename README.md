News Utility App
Overview

News Utility App is a utility-style Android application developed for CP3406 Assessment 1. The application provides users with quick, at-a-glance access to the latest news headlines from online news services. The goal is to present relevant information in a simple and efficient manner without overwhelming the user.

Features
Main Screen
Display latest news headlines
Show article images
Display publication time
Present concise news information for quick reading
Material Design 3 user interface
Settings Screen
Configure news preferences
Change display options
Control content shown on the main screen
Additional Features
Internet-based news retrieval
Responsive Jetpack Compose UI
Error handling for network failures
Loading indicators during data retrieval
Technologies Used
Kotlin
Android Studio
Jetpack Compose
Material Design 3
ViewModel
Repository Pattern
Retrofit
Gson
Coroutines
GitHub
Architecture

The application follows modern Android development practices:

UI Layer (Jetpack Compose)
ViewModel Layer
Repository Layer
Network Layer (Retrofit API)

This architecture improves maintainability, scalability, and separation of concerns.

API Used

The application retrieves news data from an external news service API using Retrofit.

Example data includes:

News title
Description
Publication date
Article image
Source information

Open the project in Android Studio
Sync Gradle files
Run on an emulator or Android device
