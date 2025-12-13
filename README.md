😴 Driver Drowsiness Detection Using CNN
High-Accuracy Real-Time Fatigue Monitoring with Deep Learning

A real-time Driver Drowsiness Detection System built using custom Convolutional Neural Networks (CNNs) to enhance road safety by monitoring driver alertness.
The system independently analyzes facial state and eye state using deep learning models and triggers alerts when fatigue is detected.

🚀 Key Highlights

🔬 Designed, trained, and evaluated 15+ custom CNN architectures

📊 Final model performance:

🔹 Face State Model Accuracy: 98.4%

🔹 Eye State Model Accuracy: 98.71%

🧠 Researched and curated driver-focused datasets from Kaggle

🎥 Real-time video processing using OpenCV

✂️ MediaPipe-based face cropping during dataset preparation to remove background noise

🚨 Intelligent alert system with user acknowledgment

⚡ Optimized for real-time inference

🧠 System Architecture & Workflow

Live video feed captured using webcam

Face & eye detection using Haar Cascades

Preprocessed inputs:

Grayscale conversion

Resizing

Normalization

Independent CNN inference:

Eye State Model → Open / Closed

Face State Model → Alert / Drowsy

Decision logic with temporal smoothing

Threshold-based alert activation

User acknowledgment required to resume monitoring

🧪 Dataset Preparation

📦 Datasets sourced from Kaggle

✂️ MediaPipe Face Detection used to:

Crop only the driver’s face

Remove background clutter

Improve model generalization

🧼 Cleaned, labeled, and balanced datasets for robust training

🧰 Tech Stack

Programming Language: Python 3.x

Deep Learning: TensorFlow, Keras

Computer Vision: OpenCV, Haar Cascades

Face Processing: MediaPipe

Data Handling: NumPy

Visualization: Matplotlib

🚨 Alert Mechanism

Maintains a drowsiness score across frames

Triggers alarm if threshold is exceeded

Requires manual user confirmation to prevent false positives

Ensures continuous and reliable monitoring

💡 Applications

🚗 In-vehicle driver monitoring systems

🚚 Fleet safety and fatigue management

🧠 AI-based behavioral analysis

🛣️ Accident prevention systems

🔮 Future Enhancements

👁️ Facial activity monitoring

Trigger alerts when facial movement falls below a threshold

🎯 Driver attention & distraction detection

Detect gaze diversion and prolonged inattention

🔊 Audio & vibration-based alert systems

📱 Edge deployment for mobile and embedded systems

🏁 Conclusion

This project demonstrates a robust, real-time AI-powered drowsiness detection system combining deep learning and computer vision.
Its modular design, high accuracy, and intelligent alerting logic make it suitable for real-world safety applications.
