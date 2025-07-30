😴 Driver Drowsiness Detection Using CNN
High-Accuracy Real-Time Fatigue Monitoring with Deep Learning

Driver Drowsiness Detection is a real-time safety system built using two custom CNN models that monitor a driver's alertness by analyzing eye and face states independently. It uses live video input, intelligent prediction logic, and an alert system to prevent accidents caused by fatigue.

🚀 Key Highlights
🔬 Developed and evaluated 15+ custom CNN architectures

📊 Final selected models achieved:

🔹 Face State Model Accuracy: 🔥 99.94%

🔹 Eye State Model Accuracy: 🔥 99.71% (without overfitting)

🧠 Researched and curated relevant driver-focused datasets from Kaggle

🎥 Real-time processing with OpenCV + Haar Cascades

✂️ MediaPipe used during dataset preparation to crop only the driver’s face, removing background noise and irrelevant features

🧪 Image preprocessing: grayscale conversion, resizing, normalization

🚨 Smart threshold system triggers alarms and requires user input to confirm alertness

🔍 How It Works
Webcam captures real-time video

Haar Cascades detect the face and eyes

MediaPipe crops clean facial regions during dataset preparation

Each region is processed and passed to its respective CNN

CNNs classify states (open/closed, alert/drowsy)

Drowsiness is tracked using a threshold counter

If exceeded, an alarm is raised, and user must respond

🧰 Tech Stack
Python 3.x

TensorFlow / Keras

OpenCV

MediaPipe

Haar Cascades

NumPy, Matplotlib

💡 Applications
In-vehicle driver monitoring systems

Fleet safety and fatigue management

AI-driven behavioral analysis tools
