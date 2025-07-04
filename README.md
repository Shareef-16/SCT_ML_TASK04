# SkillCraft Internship - Task 04: Hand Gesture Recognition using CNN ✋🤚

## 🔍 Objective
Build a CNN-based classifier to recognize hand gestures from the Sign Language MNIST dataset.

## 🧠 Techniques Used
- Convolutional Neural Networks (CNN)
- Grayscale image normalization and reshaping
- Multi-class classification (24 gesture classes)
- Evaluation via accuracy, confusion matrix, and classification report

## 🛠️ Libraries Used
- numpy
- pandas
- matplotlib, seaborn
- tensorflow / keras
- scikit-learn

## 📊 Dataset Description
- **Dataset:** Sign Language MNIST
- **Training Samples:** 27,455
- **Test Samples:** 7,172
- **Image Size:** 28×28 grayscale
- **Classes:** 24 letters (A–Y excluding J)

## 🧪 Model Training & Evaluation
- **Model:** CNN (2 Conv2D + MaxPooling layers + Dense + Dropout)
- **Training:** 10 epochs, batch size 64
- **Evaluation Metrics:**
  - Accuracy Score: 98.67%
  - Confusion Matrix: *(shown as heatmap in notebook)*
  - Classification Report: *(precision, recall, f1-score for all 24 classes)*

## ✅ Results
The CNN model accurately classified hand gestures with high precision and recall, completing a full deep learning workflow.

## 📁 Project Files
```
├── SCT_ML_TASK04_HandGesture_CNN.ipynb
├── sign_mnist_train.csv
├── sign_mnist_test.csv
├── README.md
```

## 👨‍💻 Author
**Shaik Rahamat Shareef**  
SkillCraft Machine Learning Internship  
GitHub: https://github.com/Shareef-16

## 🔗 Links
- **Repository:** https://github.com/Shareef-16/SCT_ML_TASK04
- **Notebook:** SCT_ML_TASK04_HandGesture_CNN.ipynb
