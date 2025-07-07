# 🧠 Handwritten Digit Recognizer with RL-based Correction

This project combines the power of **Convolutional Neural Networks (CNN)** for handwritten digit recognition and a **simple Reinforcement Learning (Q-Learning)** agent to reinforce corrections based on misclassifications. The model is trained on the **MNIST dataset** and includes evaluation, visualization, and prediction examples.

---

## 📌 Features

- 📦 Uses **Keras CNN** for digit classification  
- 🧪 Achieves ~98% accuracy on test set  
- 📊 Visualizes confusion matrix, accuracy/loss graphs  
- 🎯 Implements **basic Q-Learning** to reinforce corrections  
- 🖼 Predicts and visualizes random & misclassified images  

---

## 🧰 Technologies Used

- Python
- TensorFlow & Keras
- NumPy, Matplotlib, Seaborn
- Scikit-learn
- Q-Learning (manual table-based RL)

---

## 📝 Dataset

- **MNIST**: 70,000 images of handwritten digits (0-9)  
  - 60,000 for training  
  - 10,000 for testing  

---

## 🧪 Evaluation Metrics

- **Classification Report**
- **Confusion Matrix**
- **Misclassified Samples**
- **Accuracy/Loss Curves**

---

## 🚀 How to Run

### ✅ Steps to Run on Google Colab

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the `.ipynb` notebook or paste the code
3. Ensure runtime type is set to GPU for faster training (optional)
4. Click "Runtime" > "Run All"

---

## 🤖 Reinforcement Learning Logic

A very basic **Q-learning agent** observes if a predicted digit is wrong and attempts to update a correction mapping table. Over time, it learns common misclassifications and improves results slightly.

> This is simulated and not actively improving predictions — but designed to show how RL can theoretically be used to reinforce corrections.

---

## 👨‍💻 Developed By

**Yagesh Kumar Jha**

> Completed and tested in Google Colab as part of ML mini-projects.  

---

## 📎 License

This project is free to use and modify for educational purposes.
