# Face Emotion Recognition Web App

## Overview

The Face Emotion Recognition Web App is a real-time application that utilizes artificial intelligence to detect and analyze human emotions based on facial expressions. This project employs advanced computer vision techniques to provide an interactive user experience, allowing users to see their emotions displayed on the screen.

## Features

- **Real-Time Emotion Detection**: Detects emotions such as happiness, sadness, anger, surprise, and more in real-time.
- **User-Friendly Interface**: Simple and intuitive design for easy interaction.
- **Emotion Visualization**: Displays the recognized emotion prominently on the screen.
- **Responsive Design**: Optimized for use on various devices, including desktops and mobile devices.
- **Dlib Integration**: Utilizes the Dlib library for precise face detection and landmark identification.

## How It Works

1. **Face Detection**: The application uses the Dlib library to identify faces in the camera feed. Dlib's pre-trained models detect facial landmarks, which are essential for recognizing emotions accurately.

2. **Emotion Recognition**: Once a face is detected, the application processes the facial features and predicts the emotion using a trained AI model. The model has been trained on a diverse dataset of facial expressions to ensure accurate predictions.

3. **Display Results**: The recognized emotion is displayed on the web interface, providing instant feedback to the user. 

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Demodotcom/Face-emotion-detection-api.git

2. Navigate to the project directory:
  cd Face-emotion-webp

3. Install the required packages
  pip install -r requirements.txt

4. Start the application
   python app.py

5. Open your web browser and navigate to http://localhost:5000

