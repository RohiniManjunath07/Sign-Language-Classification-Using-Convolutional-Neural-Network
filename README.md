# 🖐️ Sign Language Classification using CNN

## 📌 Project Overview
This project implements a **Convolutional Neural Network (CNN)** to recognize American Sign Language (ASL) alphabets (A–Z) using the **Sign Language MNIST dataset**.  
The goal is to accurately classify hand gestures into their corresponding letters, forming a base for real-time sign language interpretation systems.

---

## 📊 Dataset
- **Source:** [Sign Language MNIST Dataset](https://www.kaggle.com/datamunge/sign-language-mnist)
- **Training Data:** `sign_mnist_train.csv`  
- **Testing Data:** `sign_mnist_test.csv` 
- **Images:** 28x28 grayscale hand signs for 26 English alphabets.  

---

## ⚙️ Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib, Seaborn  

---

## 🧠 Model Architecture
- Conv2D (32 filters, 3×3, ReLU)  
- MaxPooling2D (2×2)  
- Conv2D (32 filters, 3×3, ReLU)  
- MaxPooling2D (2×2)  
- Flatten Layer  
- Dense (512, ReLU)  
- Dense (26, Softmax) – Output layer  

---

## 🚀 Training
- **Optimizer:** Adam  
- **Loss Function:** Sparse Categorical Crossentropy  
- **Metric:** Accuracy  
- **Epochs:** 10  
- **Data Augmentation:** Rotation, shift, shear, zoom, horizontal flip  

---

## 📈 Results
- Achieves strong classification accuracy on ASL alphabet gestures.  
- Demonstrates robustness with augmented data.  

---

## 📂 Project Structure
- Sign_language.ipynb # Main Jupyter Notebook
- sign_mnist_train.csv # Training dataset
- sign_mnist_test.csv # Testing dataset

---

# 🔮 Future Work
- Real-time detection using webcam.
- Extension to dynamic gestures (not just static signs).
- Integration with speech synthesis for accessibility applications.
