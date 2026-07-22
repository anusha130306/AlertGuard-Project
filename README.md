# AlertGuard-Project
AlertGuard - Driver Drowsiness Detection System
📌 Overview

ALERTGUARD is a real-time driver safety monitoring system designed to reduce road accidents caused by driver fatigue. The system continuously analyzes the driver's facial features using AI and Computer Vision to detect signs of drowsiness such as eye closure, yawning, and head movement. When fatigue is detected, the system immediately alerts the driver and, in critical situations, sends an emergency SMS with the driver's live location to a registered guardian.

<b> Features </b>
👤 Face Registration & Login
🔐 Face Recognition with Liveness Detection
😴 Real-Time Driver Drowsiness Detection
👀 Eye Aspect Ratio (EAR) Detection
🥱 Yawn Detection
🙆 Head Pose Detection
📊 Live Driver Monitoring Dashboard
📈 Real-Time EAR Graph
🔊 Sound Alert System
📍 Google Maps Live Location Tracking
📱 Emergency SMS using Twilio API
📄 Document Upload Section
📝 Downloadable Driver Logs (PDF)
<br>
<b> Technologies Used </b>
Programming Language - Python
Backend - Flask
Frontend - HTML , CSS , JavaScript
Computer Vision - OpenCV , MediaPipe
APIs - Google Maps API , Twilio API
Database - SQLite
<br>
<b>Working </b>
User registers and logs in using Face Authentication.
Camera starts capturing live video.
MediaPipe detects facial landmarks.
Eye Aspect Ratio (EAR) is calculated.
System detects:
Eye Closure
Yawning
Head Pose
Driver status is classified as:
Active
Drowsy
Sleeping
Dashboard updates in real time.
Sound alert is triggered.
If sleeping continues, SMS with live location is sent to guardian.

This workflow is described in the system design and methodology sections of your report.
