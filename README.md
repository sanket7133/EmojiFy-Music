# EmojiFy-Music - Music Recommendation Android Application Using Emotion Recognition

![WhatsApp Image 2024-07-28 at 23 25 33_a694f029](https://github.com/user-attachments/assets/5f2acc5d-d316-4bf5-b293-cec66555aa80)



It is an academic project build as Final year project. It is an android app which recommends music based on your emotion . Its backbone or engine is its backend which runs the CNN to detect the emotion and recommends the music


![Picture1](https://github.com/user-attachments/assets/5b1f18ed-dbe4-47e4-8d69-a21d458d2817)

## Introduction
This report outlines the architecture and key technologies employed in a music recommendation application that leverages real-time emotion recognition to personalize music selection for users. The system aims to enhance user experience by tailoring music recommendations based on the user's emotional state.

## System Overview
The application operates in the following stages:

**User Input**: The system captures a user's image through the device's camera.

**Face Detection**: A Haar Cascade algorithm is employed to detect and isolate the user's face within the captured image.

**Emotion Classification**: A Convolutional Neural Network (CNN) model, trained on a dataset of 27,000 images, is used to classify the detected face into one of five emotions.

**Music Recommendation**: Based on the classified emotion, the system recommends a music playlist tailored to the user's emotional state.

**Music Playback**: The recommended music is presented to the user through a built-in music player.

## Technology Stack
The application utilizes a combination of technologies to achieve its functionalities:

**Android**: As the platform for the mobile application.

**Firebase:** As the backend infrastructure for database management, authentication, and cloud functions

**Python**: For developing the CNN model and potentially other backend components.

**Haar Cascade**: For face detection in images.

**Convolutional Neural Networks (CNN)**: For emotion classification.

**TensorFlow Lite**: used for deploying the CNN model on the Android device for real-time processing.

**Java**: For Android app development.

**CameraX**: used for camera access and image capture.

**Cloud Firestore**: Could be used for storing user preferences or other data.

**Authentication method (e.g., Firebase Authentication)**: For user management and security.

## Conclusion
By integrating computer vision, machine learning, and a robust technology stack, this music recommendation application offers a unique and personalized user experience. The system's ability to accurately detect and classify user emotions enables it to provide music selections that align with the user's emotional state, enhancing overall user satisfaction.
