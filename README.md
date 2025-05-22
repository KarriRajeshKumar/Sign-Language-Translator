# 🤟 Sign Language to Text and Speech Conversion

A machine learning-powered project that converts American Sign Language (ASL) gestures into real-time text and speech using computer vision and gesture recognition.

## 📌 Overview
This project recognizes ASL alphabets, digits, and special gestures (space, full stop) from a webcam feed and translates them into text, which is then spoken aloud using text-to-speech (TTS). It's designed to help improve accessibility and bridge communication gaps.

![asl](https://github.com/user-attachments/assets/0d7e21b0-fe97-4649-93ef-dacecf0aae21)

## 🎯 Features

- 📷 **Real-time Sign Detection** using a webcam
- 🔍 **ASL Gesture Recognition**: Supports A-Z, 0–9, Space, and Full Stop
- 🔊 **Text-to-Speech (TTS)** using `pyttsx3`
- 🧠 **Pre-trained Model** using a Random Forest Classifier
- 👨‍💻 **Custom Dataset Creation & Training Scripts** included

## 🛠️ Tech Stack

- **Languages**: Python
- **Libraries**: OpenCV, MediaPipe, scikit-learn, pyttsx3, Tkinter
- **ML Model**: Random Forest Classifier

## 🚀 Getting Started

### 1. Clone the Repository
git clone https://github.com/Praveen1425/Sign-Language-Translation.git

cd Sign-Language-Translation
### 2. Install Requirements
pip install -r requirements.txt
### 3. Run the Application
Ensure your webcam is connected
python main.py

### 🔮 Future Improvements
Improve accuracy with deep learning models (e.g., CNNs)
Build a mobile/web version
### 🙌 Acknowledgments
Inspired by open-source contributions in the accessibility and ML community.


## 📂 Project Structure

```plaintext
├── collectImgs.py         # Capture gesture images
├── createDataset.py       # Process and extract features
├── trainClassifier.py     # Train Random Forest model
├── main.py                # Real-time recognition and speech
├── model.p                # Pre-trained model
├── requirements.txt       # Python dependencies
├── LICENSE
└── README.md


