# Autism Detection from Facial Images 🌟  

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)  
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)  
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white) 

This repository contains the code, resources, and documentation for a **deep learning project** aimed at detecting Autism Spectrum Disorder (ASD) from facial images using a **Convolutional Neural Network (CNN)**. It explores the potential of advanced image analysis techniques for non-invasive and early autism detection.  

## 📋 Project Overview  
Autism Spectrum Disorder (ASD) affects communication, behavior, and social interactions. Early detection is critical for effective interventions. This project leverages CNNs to analyze facial features and predict the likelihood of ASD. It includes a **Streamlit-based web application** for interactive use.  

---

## 🧠 Background  
ASD is a developmental condition that impacts social, behavioral, and communicative abilities. Early diagnosis can improve life outcomes by enabling timely interventions. This project applies deep learning to facial image analysis to support early autism detection, aiming to complement traditional diagnostic approaches.  

---

## 📊 Dataset  
The dataset comprises facial images categorized by autism diagnosis status:  
- **Training Dataset**: Used to train the CNN to recognize autism-specific features.  
- **Testing Dataset**: Evaluates the model's accuracy and reliability.  

---

## 🔧 Data Preprocessing  
- **Image Resizing**: Adjusted dimensions to \(150 \times 150\).  
- **Grayscale Conversion**: Standardized inputs by converting images to grayscale.  
- **Normalization**: Scaled pixel values for efficient training.  

---

## 🏗️ Model Development  
A CNN architecture was designed for binary classification (Autistic or Non-Autistic):  
1. **3 Convolution Layers**: Extract spatial features.  
2. **3 Pooling Layers**: Downsample feature maps.  
3. **Dropout Layers**: Prevent overfitting.  
4. **Dense Layers**: Classify based on extracted features.  

The model was compiled using the **Adam optimizer** and trained on the dataset for **20 epochs** with a batch size of 15.  

---

## 🌐 Prediction and Web App  
A **Streamlit web app** provides an intuitive interface to interact with the model:  
- **Upload Image**: Users can upload a facial image for analysis.  
- **Capture Image**: Allows real-time image capture via webcam for predictions.  

---

## 📊 Results and Insights  
The CNN model demonstrated promising results, offering a step towards enhancing autism detection using facial images. The web app provides a hands-on tool for testing and encourages further research.  

---

## ⚠️ Camera Access Issues  
If webcam access issues arise:  
1. **Browser Permissions**: Ensure your browser allows webcam access.  
2. **Deployment Restrictions**: Run the app locally to bypass deployment constraints.

---

## 🚀 **How to Use**
1. Clone the repository.  
   ```bash
   git clone https://github.com/athirasuresh338/DL_Autism_Detection.git
   cd DL_Autism_Detection
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:  
   ```bash
   streamlit run autism_app.py
   ```
4. Follow the interactive guide to upload or capture facial images.  

---

## 📌 Conclusion  
This project combines deep learning with a user-friendly web app to aid autism detection. While not a substitute for professional diagnosis, it highlights the potential of machine learning in healthcare. Further research is essential to refine the model and validate its effectiveness.  

