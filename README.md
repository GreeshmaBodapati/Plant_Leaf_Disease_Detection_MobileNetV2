# 🌿 Plant Leaf Disease Detection Using MobileNetV2

## 📌 Project Overview
This project uses deep learning and transfer learning with MobileNetV2 to identify plant leaf diseases from images. The model classifies leaf images into 38 plant health and disease categories.

## 🎯 Objectives
- Detect plant leaf diseases using image classification.
- Apply transfer learning with a pretrained MobileNetV2 model.
- Evaluate performance using accuracy, precision, recall, and F1-score.
- Support early identification of possible plant diseases.

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- MobileNetV2
- NumPy and Matplotlib
- Scikit-learn
- Google Colab
- GitHub

## 📊 Model Performance
The previous evaluated model achieved:
- **Test Accuracy:** 95.94%
- **Test Loss:** 0.1239
- **Number of Classes:** 38
- **Test Images:** 8,146

*Note: These metrics refer to the previous evaluated run. Results from a fresh training run may differ.*

## 🧠 Methodology
1. Load and prepare the PlantVillage dataset.
2. Split images into training, validation, and test sets.
3. Train a MobileNetV2-based classifier using transfer learning.
4. Evaluate the model on a separate test set.
5. Generate a classification report and confusion matrix.
6. Predict the class of an uploaded leaf image.

## 🚀 How to Run
1. Open the notebook in Google Colab.
2. Connect Google Drive.
3. Place the dataset ZIP file at the path expected by the notebook, or update the dataset path.
4. Run the notebook cells in order.
5. Train and evaluate the model.
6. Upload a leaf image to try a prediction.

## 📁 Repository Contents
- `Plant_Leaf_Disease_Detection.ipynb` — project notebook
- `README.md` — project documentation

## ⚠️ Limitations
The model was trained on the PlantVillage dataset. Performance on real-world images may be lower due to differences in lighting, backgrounds, camera quality, and leaf conditions. Predictions are not a substitute for expert plant-disease diagnosis.


