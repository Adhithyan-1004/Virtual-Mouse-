AI Virtual Mouse using OpenCV
🔍 Introduction
This project revolutionizes traditional human-computer interaction by replacing the physical mouse with intuitive hand gestures. Using a standard webcam and computer vision algorithms, users can control mouse functions like cursor movement, clicking, and more — all without touching any device.

🎯 Objective
To create an AI-powered virtual mouse system that interprets hand gestures in real time, enhancing usability, hygiene, and accessibility for users, especially those with physical disabilities.

🧠 Problem Statement
Traditional input devices are restrictive and not always accessible. Our solution provides a gesture-based interaction platform that is contactless, adaptive, and inclusive.

🛠️ System Summary
Uses MediaPipe for hand landmark detection
Gesture encodings mapped with a Gest class
Gesture-to-mouse control (move, click, volume, brightness)
Real-time video feed analysis with OpenCV
📋 Key Features
Finger tracking via webcam
Dynamic gesture recognition
Click simulation and pointer control
Custom brightness & volume adjustments
No external hardware required
✅ Results
The system demonstrated high accuracy in gesture recognition and smooth real-time mouse control. It successfully worked on multiple laptops and under different lighting conditions.

📚 References
Real-time hand gesture recognition by Ozturk et al.
Gesture-control interaction models in smart environments
OpenCV virtual mouse implementations
