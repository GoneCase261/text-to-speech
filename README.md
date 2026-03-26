🗣️ Text To Speech Converter (React Native + Expo)

A simple mobile application built using React Native and Expo that converts user-entered text into spoken audio using device text-to-speech capabilities.

📌 Overview

This project demonstrates how mobile applications can integrate speech synthesis to improve accessibility and user interaction.

Users can type any word or sentence, press a button, and instantly hear the spoken output.

The app uses Expo Speech API to perform real-time text-to-speech conversion.

✨ Features
🔤 User text input
🔊 Converts text into speech
📱 Mobile-friendly UI
⚡ Instant speech playback
✅ Input validation (alerts if empty)
🛠️ Tech Stack
React Native
Expo
JavaScript (ES6)
expo-speech
react-native-elements
📱 How It Works
User enters text into the input box.
The text is stored in React state.
When the button is pressed:
The app checks if input exists.
Expo Speech API converts text into audio.
Device plays the spoken output.
🧠 Key Concepts Demonstrated
React Native component lifecycle
State management
Event handling
Mobile UI design
Native device capability integration
Speech synthesis APIs
🚀 Getting Started
Prerequisites
Node.js installed
Expo CLI installed
npm install -g expo-cli
Installation

Clone the repository:

git clone https://github.com/YOUR_USERNAME/text-to-speech-app.git

Navigate into the project:

cd text-to-speech-app

Install dependencies:

npm install

Run the app:

expo start

Scan the QR code using the Expo Go app on your phone.

📂 Project Structure
project-root/
│
├── App.js
├── package.json
├── babel.config.json
├── .gitignore
└── README.md
📸 Demo

(Add screenshots or screen recording GIF here)

Example:

Input text screen
Speech playback button interaction
🔮 Future Improvements
Language selection
Voice speed & pitch control
Save speech as audio file
Dark mode UI
Speech history
🎯 Learning Purpose

This project was built to explore:

Mobile app development with React Native
Expo ecosystem
Speech synthesis integration
