This project demonstrates how to integrate the gemini-1.5-flash-latest model with an Android application using Jetpack Compose, Kotlin Coroutines, and CameraX for capturing images and making predictions.

Features

Camera Integration: Uses CameraX to capture images.
Google AI Integration: Uses gemini-1.5-flash-latest model for making predictions.
Jetpack Compose UI: Modern UI with Compose.
Kotlin Coroutines: Handles asynchronous tasks efficiently.

Prerequisites

Android Studio (Latest Version)
Kotlin & Jetpack Compose setup
Google Cloud API Key for Gemini
Internet Permission in AndroidManifest.xml

Permissions
Add the required permissions in AndroidManifest.xml:

<uses-permission android:name="android.permission.CAMERA" />
<uses-feature android:name="android.hardware.camera" />


Running the Project

Clone the repository.
Open in Android Studio.
Set up an API Key for Gemini and add it to local.properties.
Run the app on a physical device with a camera.
Capture an image and view the AI predictions.

Conclusion
This project enables real-time image capturing and AI-based analysis using Gemini-1.5 Flash. With Jetpack Compose, CameraX, and Coroutines, the app offers a smooth and efficient user experience.

Future Enhancements

Support for video analysis
UI improvements with animations
Offline model inference

License
MIT License
