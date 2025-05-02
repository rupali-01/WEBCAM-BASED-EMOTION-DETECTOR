# WEBCAM-BASED-EMOTION-DETECTOR
Webcam-Based Emotion Detection
A simple project that detects emotions from a webcam image in real-time using the FER (Facial Expression Recognition) library.

Features
   -Real-Time Emotion Detection: Captures an image from your webcam and detects the emotion.
   -Confidence Score: Displays the emotion with its confidence level.
   -Easy Setup: Works easily in Google Colab and can be adapted for local environments.

Requirements
     -Python 3.x
     -opencv-python for webcam access and image processing.
     -fer for emotion recognition.

How to Use
     In Google Colab:
          -Run the code block with the webcam capture logic.
          -Click on the "📸 Take Photo" button to capture a photo from your webcam.
          -The emotion will be detected, and the result will be displayed.

      Locally:
          -Modify the webcam capture part to use OpenCV’s cv2.VideoCapture().
