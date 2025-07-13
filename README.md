# Vaani-AI
Real-time Indian Sign Language detection using LSTM

**Vaani-AI** is a deep learning-based gesture recognition system developed as part of our final-year capstone. It aims to detect and classify Indian sign language gestures by analyzing video sequences of human movements. The project explores how AI can understand visual communication — such as hand signs and body posture — and associate them with meaningful linguistic interpretations, especially in the context of Indian regional languages.

At its core, the system uses **MediaPipe Holistic** to extract detailed body, face, and hand landmarks from video input. These sequences are then passed into a **Long Short-Term Memory (LSTM)** model built with TensorFlow/Keras, which learns temporal patterns in gesture movements to classify them accurately. The ultimate goal of Vaani is to contribute towards making communication more inclusive, especially for the hearing and speech-impaired communities, where sign language plays a central role.

---

##  Motivation Behind the Project

India is a country rich in diversity — not just in spoken languages, but also in how people express themselves through gestures and body language. Despite this, sign language remains an underrepresented area in mainstream technology and education. I have always been fond of sign language,how it connects us,my goal with this project it to increase the inclusivity and break the language barrier.

With Project Vaani, we wanted to work on a problem that was both technically challenging and socially relevant. We were inspired to explore real-time gesture detection and temporal modeling, while also building something that could potentially contribute to accessibility solutions. Our focus was to develop a system that can process sequences of motion and classify them with minimal hardware and setup, making it practical and lightweight.

---

## 🔧 Tools & Technologies Used

This project integrates several powerful open-source tools from the computer vision and deep learning ecosystem:

- **MediaPipe Holistic** – for extracting landmarks from hands, pose, and facial features  
- **OpenCV** – for capturing and processing video input  
- **NumPy** – for storing structured keypoint data  
- **TensorFlow/Keras** – to design, train, and evaluate the LSTM-based classification model  
- **Matplotlib** – to visualize training metrics such as accuracy and loss

