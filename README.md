<div align="center">
  
 <img src="logo1.png" alt="Automated-Plant-Species-Identification-System Logo" width="40%">
 
</div>

# Automated-Plant-Species-Identification-System


## **Introduction**
This project focuses on building an **Automated Plant Species Detection System** using **Deep Learning** techniques. With an increasing need for precise plant species identification, this system is designed to assist botanists, researchers, and agricultural experts in classifying plant species based on leaf images. The model leverages a Convolutional Neural Network (CNN) architecture to analyze and identify plant species from a dataset of images effectively.

---

## 🎯**Objectives**
1. **Automate Plant Species Classification**: Develop a reliable deep learning model for accurately identifying plant species based on leaf images.  
2. **Build a Comprehensive Dataset**: Utilize a collection of labeled plant images to create a structured dataset for training and validation.  
3. **Achieve High Classification Accuracy**: Aim for robust and generalized performance across diverse plant species by training the CNN model effectively.  
4. **Deploy for Practical Use**: Create a user-friendly and deployable solution for end users like agriculturists and researchers.  

---
## 🚀**Features**
1.**Comprehensive Plant Species Recognition** :Identifies multiple plant species with high accuracy.Handles classification across a diverse dataset of plant species.

2.**Deep Learning Architecture**: Powered by a Convolutional Neural Network (CNN).Model trained to generalize well on unseen plant images.

3.**User-friendly Implementation**: Provides an intuitive interface for end users to upload and analyze plant leaf images. 

4.**Scalability**: Can be adapted for larger datasets or additional species.Easily modifiable to include new plant categories.

---

## 🏗️**Workflow**

### 1. **Data Collection**
- Images of 10 different plant species were collected, each labeled appropriately in directories.  
- Each species corresponds to a unique folder containing its respective images.  

### 2. **Data Preprocessing**
- Images were resized to a uniform dimension of `(256x256x3)`.  
- Data normalization was applied to scale pixel values between 0 and 1.  
- Labels were encoded and converted into categorical one-hot representations.  

### 3. **Model Architecture**
- A **Convolutional Neural Network (CNN)** was designed with the following key layers:  
  - **Conv2D Layers**: For feature extraction.  
  - **MaxPooling2D**: For down-sampling feature maps.  
  - **Dropout Layers**: To prevent overfitting.  
  - **Dense Layers**: For classification based on extracted features.  
  - Final activation as **Softmax** to predict probabilities for 10 classes.  

### 4. **Training**
- The model was trained over **150 epochs** with a batch size of **32** using the **Adam optimizer**.  
- `Categorical Cross-Entropy` was used as the loss function to handle multi-class classification.  

### 5. **Validation**
- The dataset was split into 80% training and 20% validation.  
- Validation accuracy and loss were monitored to ensure the model's generalizability.  

### 6. **Testing and Evaluation**
- Evaluated on a separate validation dataset to ensure high performance with real-world data.  

### 7. **Prediction**
- Tested the system with unseen images to predict the species accurately.  
- Outputs included class probabilities and corresponding species labels.  

---
