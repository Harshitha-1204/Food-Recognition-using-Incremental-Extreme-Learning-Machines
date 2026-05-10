# food-recognition-using-incremental-extreme-learning-machine
Food image classification project using Incremental Extreme Learning Machine (I-ELM) with fast training, incremental learning, and scalable performance.
# Food Recognition Using Incremental Extreme Learning Machine (I-ELM)
# Real-Time Food Detection Using YOLOv3 and OpenCV DNN

##  Project Overview
This project implements an **image-based food recognition system** using **Incremental Extreme Learning Machine (I-ELM)**.  
The model efficiently classifies food images while supporting **incremental learning**, allowing new data and classes to be added **without retraining the entire model**.  
The approach focuses on **fast training, low computational cost, and scalability**, making it suitable for real-time and lightweight machine learning applications.


##  Objectives
- Classify food images accurately using machine learning  
- Enable **incremental learning** for scalability  
- Reduce training time compared to traditional neural networks  
- Support efficient model updates with new data  
## Introduction
Food detection is a fundamental computer vision task with applications in nutrition tracking, smart kitchens, and automated food analysis systems.  
This project presents a **real-time food detection system** implemented using **YOLOv3 (You Only Look Once)** and **OpenCV’s Deep Neural Network (DNN) module**.

The system processes both **static images and live webcam video streams**, detects **food-related objects**, and visualizes results using bounding boxes, class labels, and confidence scores.

---

##  Methodology
1. **Image Preprocessing**
   - Image resizing and normalization
   - Feature extraction using numerical representations
##  Project Objectives
- Detect food items in images and live video streams  
- Achieve real-time performance using YOLOv3  
- Apply Non-Maximum Suppression to improve detection accuracy  
- Display detection confidence and FPS for performance evaluation  
- Build a lightweight and modular computer vision pipeline  

2. **Model Training**
   - Implementation of **Incremental Extreme Learning Machine (I-ELM)**
   - Randomized hidden layer with analytical output weight computation
   - Incremental addition of neurons for improved learning
---

3. **Evaluation**
   - Model accuracy and prediction performance
   - Training speed comparison
   - Scalability assessment
##  System Architecture
1. Input image or webcam frame
2. Image preprocessing and blob creation
3. Forward pass through YOLOv3 network
4. Food-related class filtering
5. Confidence thresholding
6. Non-Maximum Suppression (NMS)
7. Visualization of results and FPS calculation

---

##  Key Features
- Image classification using **Incremental Extreme Learning Machine (I-ELM)**
- Incremental learning without full model retraining
- Fast training and low computational overhead
- Scalable architecture for adding new food categories
- Python-based, modular implementation
##  Key Functionalities
- **Food Object Detection:** Identifies food-related objects using YOLOv3 trained on the COCO dataset  
- **Real-Time Processing:** Supports live webcam detection  
- **Confidence-Based Filtering:** Removes weak predictions  
- **Non-Maximum Suppression:** Eliminates duplicate detections  
- **Performance Monitoring:** Displays real-time FPS  
- **Modular Design:** Easy to extend or retrain for food-only datasets  

---

## 🛠️ Technologies Used
##  Technologies and Tools
- Python  
- OpenCV (DNN Module)  
- YOLOv3 Deep Learning Model  
- NumPy  
- Pandas  
- OpenCV (Image Processing)  
- Machine Learning (ELM, I-ELM)
- Computer Vision  

---
