# Sign-Language-convertion
## Table of content:
- Aim
- Abstract
- Project Overview
- Features
- Architecture diagram
- Sign-Language Examples
- Demo
- Result
## Aim:
- The aim of this project is to develop a real-time Sign Language Conversion System that recognizes hand gestures and converts them into meaningful text or speech, enabling effective communication between hearing-impaired individuals and people who do not understand sign language. The system uses machine learning, hand landmark detection, and Python-based technologies to achieve accurate gesture recognition.
## Abstract:
- Sign language is one of the oldest and most natural form of language for communication, but since most people do not know sign language and interpreters are very difficult to come by we have come up with a real time method using neural networks for fingerspelling based american sign language.
- In this method, the hand is first passed through a filter and after the filter is applied the hand is passed through a classifier which predicts the class of the hand gestures. This method provides 98.00 % accuracy for the 26 letters of the alphabet.
## Project Overview:
- Sign language is a crucial form of communication for individuals with hearing impairments. This project focuses on bridging the communication gap by creating a tool that can interpret sign language gestures in real-time and convert them into understandable text or speech.
- This project leverages Flask for the web interface and TensorFlow/Keras for the machine learning model to recognize sign language gestures in real-time from a webcam feed.
## Features:
- #### Real-time sign language recognition:Captures hand gestures using the Mediapipe library to track landmarks and movements.
- #### Landmark analysis: Utilizes Landmark module to extract key points and gestures from hand movements.
- #### Machine learning translation: Employs Random Forest algorithm to classify and interpret gestures into corresponding text.
- #### Text-to-speech: For better communication the text can be converted to spoken language using the speech synthesis.
## Architecture Diagram:
<img width="610" height="666" alt="image" src="https://github.com/user-attachments/assets/15610faf-3b05-41d4-be0c-b3e9d2cc5c9b" />

## Sign-Language Examples:
<img width="2000" height="1600" alt="signlanguage" src="https://github.com/user-attachments/assets/112b8f47-b8d6-4422-aa8c-a27c04e55efa" />

##  Demo
<img width="1920" height="1080" alt="Screenshot 2025-10-29 081626" src="https://github.com/user-attachments/assets/0c683a49-ab63-4d2f-b686-aab2fc23bf04" />

#### The Demo video was uploaded as a seperate file if u want check it out

##  Results

- Achieved 98% accuracy on ASL alphabet gestures
- Works in real-time with minimal delay
- Accurate for static signs
- Smooth hand tracking using Mediapipe
