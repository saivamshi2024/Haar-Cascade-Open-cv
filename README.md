# 👁️🚗 Haar Cascade Detection using OpenCV (Face, Eye, Car, Full Body)

This repository contains multiple real-time computer vision projects using **Haar Cascade Classifiers** in **OpenCV** to detect:

- 👀 Eyes  
- 🙂 Faces  
- 🚗 Cars  

These projects demonstrate how traditional computer vision techniques can be used for object detection without deep learning.

---

## 📌 What is Haar Cascade?

**Haar Cascades** are a type of object detection algorithm based on **Haar features**. They are fast, efficient, and ideal for real-time detection using pre-trained classifiers provided by OpenCV.

---

## 🎯 Project Features

### 🙂 Face Detection
- Uses `haarcascade_frontalface_default.xml`
- Real-time face detection via webcam
- Draws bounding boxes around detected faces

### 👁️ Eye Detection
- Uses `haarcascade_eye.xml`
- Detects and highlights eyes within the detected face region

### 🚗 Car Detection
- Uses `haarcascade_car.xml`
- Detects cars in video frames or from a webcam

---

## 🛠 Tools & Libraries Used

- **Python**
- **OpenCV**
- **Haar Cascade Classifiers (XML files)**

---

## 🖼️ Output Preview
Add your screenshots or video clips here

✅ Face with bounding box
✅ Eyes inside face box
![Image](https://github.com/user-attachments/assets/6f6a88b2-33ad-4a9c-ba9f-0920f559f144)

✅ Cars detected in motion
![Image](https://github.com/user-attachments/assets/7bf2716c-565a-4fdc-8860-060756fda538)

✅ Full Body detected in motion
![Image](https://github.com/user-attachments/assets/2f3a8447-94ac-4673-b79b-10be2b06fca4)

---

## 💡 Notes
Haar cascades are lightweight but can have false positives.

Works best in good lighting conditions and frontal views.

Suitable for demo or learning purposes (not production-grade).

---

## 🔮 Future Enhancements
Add face detection with mask detection

Combine with Deep Learning models (like YOLO or SSD)

Improve accuracy with image preprocessing 
