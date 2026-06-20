Plant Disease Detection Using Deep Learning

Project Report for AI/ML
1. Introduction
Agriculture is a critical global sector, but crop yields and food quality are continuously threatened by plant diseases. Traditionally, identifying these diseases is a time-consuming process that requires specialized expert knowledge, often unavailable in remote or rural areas.
This project addresses this challenge by developing an automated, deep learning-based image classification system. This system utilizes Convolutional Neural Networks (CNNs) to instantly analyze images of plant leaves to detect and classify the presence of a disease, offering a fast and accessible diagnostic tool for farmers and researchers.

2. Objectives
The main objectives successfully accomplished by this project are:
To build a machine learning model capable of accurately detecting and classifying specific plant diseases using leaf images.
To preprocess and augment a large collection of leaf images to train an efficient CNN model.
To evaluate the model's performance rigorously using standard accuracy and classification metrics.
To develop a user-friendly interface for image upload and real-time prediction.
To provide a fast and automated solution for plant disease diagnosis in agricultural settings.

3. Dataset Description
The core of this project relies on high-quality labeled images.
The primary dataset utilized is the PlantVillage dataset, which is widely adopted for this problem due to its comprehensive nature:
Size: Over 87,000 RGB images.
Classes: Approximately 38 classes, covering a variety of plant species and diseases.
Examples: Healthy, Early Blight, Late Blight, Leaf Rust, Powdery Mildew, Mosaic Virus, and Bacterial Spot.
The images are organized into folder-based classes, which facilitates direct implementation with deep learning frameworks.
Link of data set- https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset

4. Methodology: System Architecture
The project employs a standard machine learning pipeline, moving from data preparation to real-time deployment.
4.1. Overall System Workflow
The user-facing system operates through these steps:
User uploads a leaf image.
Image is preprocessed (resized, normalized).
Image is passed through the trained CNN model.
Model outputs the predicted disease class and its confidence probability.
The final result is displayed to the user.
