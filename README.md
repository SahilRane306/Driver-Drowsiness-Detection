Driver Drowsiness Detection System

A real-time computer vision system to detect driver fatigue and prevent accidents.
The project uses Python, OpenCV, and Haar cascades to monitor eye activity, identify drowsiness, and trigger an audio alert when the driver shows signs of falling asleep.

🔍 Problem Statement

Driver fatigue is a leading cause of road accidents worldwide. Microsleep episodes or prolonged eye closure often go unnoticed until it’s too late. This project aims to build a low-cost, real-time drowsiness detection system that alerts the driver before a critical event occurs.

✨ Features

👁 Eye Tracking – Detects open/closed eye states using Haar cascades.

😴 Drowsiness Detection – Measures continuous eye closure duration to classify fatigue.

🔔 Audio Alert System – Plays an alarm if drowsiness is detected.

🎥 Live Monitoring – Processes webcam feed in real time for continuous monitoring.

🛠 Tech Stack

Programming Language: Python 3

Libraries: OpenCV, NumPy, Pygame

Model/Algorithm: Haar Cascade Classifiers

🚀 Workflow

Capture real-time video stream from the webcam.

Detect the driver’s face and eyes using Haar cascades.

Continuously track eye states (open/closed).

Measure duration of eye closure across frames.

If closure exceeds threshold → trigger an audio alert.

Resume monitoring once eyes reopen.

📊 Future Improvements

Integrate deep learning models (CNNs) for more accurate eye state detection.

Add head pose estimation to detect nodding off.

Deploy on Raspberry Pi / IoT devices for in-car usage.
