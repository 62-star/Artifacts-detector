# Artifacts-detector
an object detection model using YOLOv8 pretrained model to identify museum artifacts from image or camera.
The model is designed for a museum mobile application integration ,enabling real-time artifact recognition and enhancing visitor experience through AI-powered visual understanding.
Project Overview
Museums often rely on static information displays. This project leverages computer vision to automatically detect museum artifacts from images captured by users and provide relevant information via a mobile app.
The pipeline covers the full AI lifecycle:
* Data preprocessing and annotation
* Model training and evaluation
* Deployment-ready design for mobile integration

Features
* Detects multiple museum artifacts from images
* Custom-trained YOLOv8 object detection model
* High-speed and accurate inference
* Scalable dataset using Roboflow
* Mobile-app integration friendly

Technologies Used
Python
YOLOv8
Roboflow (data preprocessing & annotation)
Computer Vision

Dataset & Preprocessing
The national museum of Egyption civilisation Dataset annotated using Roboflow
Applied:
* Image resizing
* Data augmentation
* Class balancing
Exported dataset in YOLOv8 format

Model Training
Framework: YOLOv8
Task: Object Detection
Evaluation metrics:
* Precision
* Recall
* mAP (Mean Average Precision)

The model was optimized for both accuracy and real-time performance.
