# 🦷 Teeth X-ray Classification – Dental Disease Detection

This project focuses on identifying dental conditions from panoramic X-ray images using deep learning. The model classifies images into **7 categories** of dental abnormalities to assist in diagnostic automation.

## 📊 Dataset
- **Source:** Panoramic dental X-ray dataset (source unspecified)
- **Classes:** 7 different dental issues
- **Preprocessing:** Images were resized, normalized, and augmented to enhance generalization

## 📌 Project Highlights

###  1. Preprocessing
- Resizing, grayscale conversion, normalization
- Data augmentation techniques: flipping, rotation, zoom, etc.
- Dataset split into training, validation, and test sets

###  2. Models Implemented
- ✅ Custom CNN from scratch
- ✅ Transfer learning models: VGG16, ResNet50
- ✅ Fine-tuned model weights and compared performance

###  3. Evaluation Results
- Achieved **up to 92% accuracy** using fine-tuned models
- High F1 scores across multiple classes
- Visualized performance using confusion matrix, accuracy/loss plots

###  4. Deployment
The trained model was deployed as an interactive web app using **Streamlit**, allowing users to upload X-ray images and view classification results in real-time.
- Styled the UI using **HTML/CSS**
- Displayed confidence scores for each class
- Includes clear error handling and prediction display
