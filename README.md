Face Emotion Recognition with Deep Learning 🤖🎭

This project focuses on face emotion recognition using deep learning techniques. The goal is to classify human emotions (angry, happy, sad, neutral, surprise, etc.) from facial expressions, even under challenging conditions such as wearing face masks.

📌 Introduction

Facial emotion recognition plays an important role in human-computer interaction and empathetic AI systems. While humans naturally use facial cues (eyes, eyebrows, mouth) to interpret emotions, machines require algorithms to detect and classify these expressions. The COVID-19 pandemic introduced new challenges, as masks obscure key facial regions like the mouth, making recognition more complex.

🚀 Project Significance

Our work aims to:

Improve emotion recognition accuracy in real-world conditions.

Enable robots/devices to recognize and respond to users’ emotions in real time.

Contribute to better human-robot interaction by allowing machines to adapt based on emotional states.

📊 Dataset

FER-2013 (Kaggle): 48x48 grayscale face images categorized into 7 emotions.

Masked FER-2013 (Kaggle): Adapted dataset to simulate face mask scenarios.

🛠️ Methods & Tools

Deep Learning Framework: PyTorch

Model: Convolutional Neural Network (CNN) with dropout to reduce overfitting

Key Libraries: torch, torchvision, cv2, os, random, shutil

Techniques: Vision-based face detection, data augmentation, and real-time classification with camera input

⚡ Experiments & Results

Achieved 95% training accuracy and 59% test accuracy.

Challenges such as overfitting were addressed using dropout and dataset expansion.

Initial TensorFlow model showed higher accuracy, but was converted to PyTorch for compatibility with the NVIDIA Jetson Nano robot system.

🤖 Robot Integration

The trained models are deployed on a robot equipped with cameras for real-time emotion recognition. This allows the robot to interpret and respond to human emotions, enhancing interaction quality.

🔮 Future Work

Improve robustness with larger and more diverse datasets.

Integrate voice recognition alongside facial emotion recognition for multimodal emotion detection.

✨ By combining computer vision and deep learning, this project contributes to building more empathetic and adaptive AI systems that can understand and respond to human emotions.
