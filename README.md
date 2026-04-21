# Hand-Gesture-Volume-Controller

Project Title: Hand Gesture Volume Controller
A real-time Computer Vision application that allows users to control system audio levels through hand geometry and motion tracking.

Overview
This project uses OpenCV and MediaPipe to detect hand landmarks in real-time. By calculating the distance between the thumb and index finger, the application maps physical movement to system volume levels.

✨ Key Features
Real-time Hand Tracking: Uses MediaPipe’s 21-point landmark model for high-accuracy detection.
Dynamic Volume Mapping: Leverages NumPy to translate pixel distance into decibel ranges (0% to 100%).
Visual HUD: Displays a real-time volume bar and percentage directly on the webcam feed.
Zero-Latency Performance: Optimized frame processing for a smooth, lag-free user experience.

🛠 Tech Stack
Language: Python 3.x
Computer Vision: OpenCV, MediaPipe
Math/Logic: NumPy
System Integration: PyCaw (Windows) or Osascript (macOS)
