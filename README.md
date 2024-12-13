# Signify

Signify is a sign language learning application that uses cutting-edge machine learning techniques to detect hand gestures and convert them into corresponding alphabet letters. It helps users learn and practice sign language in an interactive and engaging way.

## Features
- **Sign Language Recognition**: Detects hand gestures and translates them into alphabet letters.
- **Interactive Learning**: Users can practice their gestures and do quizzes.
- **User-Friendly Interface**: Designed for both beginners and advanced learners to improve their sign language skills.

## How It Works

1. **Hand Gesture Detection**:  
   The app uses **MediaPipe** to extract hand landmarks from input images or live camera feeds.

2. **Gesture Classification**:  
   A Convolutional Neural Network (CNN) is trained on a dataset of hand gestures representing the alphabet. The app predicts the corresponding letter based on the gesture.

3. **Learning Mode**:  
   Users can interact with the app to learn sign language, with features like guided practice and quizzes.

---

## Technology Stack

- **MediaPipe**: For hand tracking and landmark extraction.
- **Convolutional Neural Network (CNN)**: For gesture classification.
- **Python**: Backend for training and inference.

---
