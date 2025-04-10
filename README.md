# 🥔 Potato Leaf Disease Classification using CNN

This project uses **Convolutional Neural Networks (CNNs)** built with **TensorFlow/Keras** to classify potato leaves into three categories:

- **Potato___Early_blight**
- **Potato___Late_blight**
- **Potato___healthy**

The dataset is sourced from the **PlantVillage Dataset** and is trained using **Google Colab** with GPU acceleration.

---

## 📁 Dataset Structure

The dataset is structured in the following directory format:


- **Total Images:** 2159  
- **Training:** 1728 (80%)  
- **Validation:** 431 (20%)  

---

## 🚀 Project Workflow

- 📦 **Mount Google Drive**
- 📚 **Load Dataset with TensorFlow**
- 📈 **Visualize Sample Images**  
  A batch of 5 images is plotted from the training set with their corresponding labels.
- ⚙️ **Dataset Pipeline Optimization**
- 🧪 **Data Augmentation**  
  Applied transformations:
  - Resizing  
  - Normalization  
  - Horizontal Flip  
  - Rotation  
  - Zoom  
  - Contrast Adjustment

---

## 🧠 CNN Model Architecture


- **Input Shape:** (128, 128, 3)  
- **Output Layer:** 3 neurons with softmax activation  
- **Total Parameters:** 692,835  

---

## 🏃 Model Training

- **Optimizer:** Adam  
- **Loss Function:** sparse_categorical_crossentropy  
- **Metric:** accuracy  
- **Technique:** EarlyStopping to prevent overfitting  

---

## 📊 Training Performance

- **Best Validation Accuracy:** 98.14%  
- **Best Validation Loss:** 0.0795  

Training and validation **accuracy/loss curves** are plotted for analysis.

---

## ✅ Evaluation on Validation Set

loss, accuracy = model.evaluate(val_ds)
🔮 Model Prediction Visualization
16 images from the validation set are shown with:
Ground Truth
Predicted Label

## 💾 Save the Trained Model
## 🛠️ Technologies Used
Python
TensorFlow / Keras
Google Colab (GPU)
Matplotlib
NumPy / Pandas

## 🧠 Key Learnings
Image classification with CNNs

Conv2D → MaxPool → Dropout →

Conv2D → MaxPool → Dropout →

Conv2D → MaxPool → Dropout →

Conv2D → MaxPool → Dropout →

Flatten → Dense → Dropout → Output

Data augmentation and pipeline optimization

Early stopping for better generalization

Training deep learning models on Google Colab

Visualizing model predictions and performance

## 📌 Future Work
Add support for more crop types and diseases

Convert the model to TensorFlow Lite for mobile deployment

## 📎 Author
**Md Shihabul Islam Shihab**

**Undergraduate Student, Mechatronics Engineering**

**Rajshahi University of Engineering & Technology (RUET)**

📧 shihabul.islam.shihab.004@gmail.com
