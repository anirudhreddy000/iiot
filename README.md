# 🏋️ Deadlift Form Tracker

This project uses **MediaPipe** and a pre-trained **TensorFlow/Keras** model to analyze and track a person’s **deadlift form** in real time through webcam video.  
It classifies the form into categories: **good**, **bad**, or **ugly**, helping lifters get instant feedback on their technique.

---

## 🚀 Features
- 📸 **Real-time pose estimation** using MediaPipe Holistic  
- 🧠 **Deep learning model (`lift_v2.h5`)** for classification of deadlift form  
- 🎨 **Visualization of landmarks** (pose & hands) on live video feed  
- 📊 **Probability visualization** (bar indicators for prediction confidence)  
- ✅ **Form feedback** displayed as live text overlay  

---

## 🛠️ Tech Stack
- **Python 3.x**
- **OpenCV** – for webcam video capture and visualization  
- **MediaPipe** – for real-time pose & hand landmark detection  
- **TensorFlow / Keras** – for training and loading the deadlift classification model  
- **NumPy** – for handling keypoints  
- **Matplotlib** (optional, for visualization during experiments)

---

## 📦 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/deadlift_form_tracker.git
   cd deadlift_form_tracker
