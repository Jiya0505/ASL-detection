# ASL-detection
✋ Real-Time ASL Detection in Video Calls
This project is a real-time American Sign Language (ASL) letter recognition system built for seamless communication during peer-to-peer video calls. It uses MediaPipe Hands, JavaScript, and PeerJS to detect and interpret static ASL gestures directly from live video streams.

🎯 Features
🔍 Real-time hand tracking using MediaPipe Hands

✍️ ASL letter recognition based on joint angles and fingertip distances

📹 WebRTC video calling powered by PeerJS

🎨 Live canvas overlay for gesture visualization

🌐 Works entirely in the browser – no backend needed!

🛠️ How It Works
Hand Detection: MediaPipe extracts 21 3D landmarks from the user’s hand in each frame.

Feature Extraction: The system calculates the sum of angles between joints for each finger, along with distances like the one between index and middle fingertips.

Gesture Classification: A rule-based algorithm maps these values to specific ASL letters such as A, L, C, V, etc.

Live Display: The detected letter is displayed in real time on a canvas overlay, along with the hand skeleton.

🚀 Getting Started
Clone the repo and open app.html in your browser.

Allow webcam permissions.

Create or join a room to start recognizing ASL gestures in a video call.

📌 Future Plans
Replace rule-based classification with a trained ML model

Extend to dynamic ASL gestures and full-sentence recognition

Add multilingual gesture support and UI enhancements

💡 Why ASL-Detection?
It aims to bridge the communication gap for the Deaf and Hard-of-Hearing community by integrating ASL directly into everyday video interactions, making digital communication more inclusive, accessible, and natural.

