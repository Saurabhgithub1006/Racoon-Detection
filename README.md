# 🦝 Raccoon Detection using CNN (Bounding Box Prediction)

## 📌 Project Overview
This project focuses on building a computer vision model to detect raccoons in images and localize them using bounding boxes. A Convolutional Neural Network (CNN) is trained to directly predict bounding box coordinates from input images.

---

## 📊 Dataset
- ~200 raccoon images  
- Bounding box annotations provided in CSV format  
- Each image contains a single raccoon  

---

## 🎯 Objective
To develop a deep learning model that can:
- Detect raccoons in images  
- Predict bounding box coordinates (x, y, width, height)  

---

## ⚙️ Workflow

### 1. Data Preparation
- Loaded image paths and annotation data  
- Resized images to a fixed size  
- Adjusted bounding box coordinates after resizing  

### 2. Image Processing
- Applied preprocessing and normalization  
- Converted annotations into structured format  

### 3. Visualization
- Displayed images with bounding boxes using Matplotlib  
- Verified annotation correctness  

### 4. Model Development
- Built a custom CNN using TensorFlow/Keras  
- Used Conv2D, BatchNormalization, and MaxPooling layers  
- Fully connected layers output 4 bounding box coordinates  

### 5. Training
- Optimizer: Adam  
- Callbacks used:
  - EarlyStopping  
  - ReduceLROnPlateau  
  - ModelCheckpoint  

### 6. Evaluation
- Used Intersection over Union (IoU) to evaluate predictions  
- Monitored training and validation performance  

### 7. Prediction
- Visualized predicted bounding boxes on images  
- Compared predictions with actual annotations  

---

## 🧠 Model Architecture
- Convolutional layers with ReLU activation  
- Batch Normalization for stability  
- MaxPooling layers for feature extraction  
- Fully connected layers  
- Output layer predicts 4 bounding box values  

---

## 🧰 Tech Stack
- Python  
- TensorFlow / Keras  
- OpenCV  
- NumPy, Pandas  
- Matplotlib  

---

## 📈 Results
- Successfully trained a CNN model for object localization  
- Achieved reasonable bounding box predictions on a small dataset  
- Built a complete pipeline from preprocessing to prediction  

---

## 🚀 Key Learnings
- Object detection vs classification  
- Bounding box regression  
- Image preprocessing and annotation handling  
- IoU evaluation metric  
- Building end-to-end deep learning pipelines  

---

## 📷 Sample Output
(Add images here showing predicted bounding boxes)

---

## 🤝 Acknowledgements
Dataset originally collected by Dat Tran.
