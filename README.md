# 🎵 Emotion-Based Music Recommender

An AI-powered music recommendation system that detects the user's facial emotion and suggests songs that match their current mood. This project combines facial emotion recognition and audio content filtering to create a personalized and immersive listening experience.

## 💡 Features

- 🎥 Real-time facial emotion detection using OpenCV and a CNN model.
- 😊 Emotion categories: Happy, Sad, Angry, Neutral, etc.
- 🎶 Dynamic music recommendations based on detected emotion.
- 🧠 Pre-trained models for accurate emotion classification.
- 🎵 Audio playback integrated directly into the app.

## 📁 Project Structure

```bash
Emotion-based-Music-Recommender/
├── Music/                      # Emotion-wise categorized music
│   ├── angry/
│   ├── happy/
│   ├── neutral/
│   └── sad/
├── model/                      # Pre-trained CNN model for emotion detection
│   └── emotion_model.h5
├── haarcascade_frontalface.xml  # Face detection cascade
├── main.py                     # Main script to run the application
├── requirements.txt            # List of dependencies
├── README.md                   # Project documentation
└── utils.py                    # Helper functions for music recommendation
