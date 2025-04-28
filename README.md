# Machine Learning and Deep Learning Projects

This repository contains **five projects** covering different machine learning and deep learning tasks, from computer vision to natural language processing.

---

## 📚 Project List

### 1. MNIST - CNN with Parameter Constraint
**Task:**  
Design and train a Convolutional Neural Network (CNN) with **no more than 7000 trainable parameters** to achieve the best possible accuracy on the MNIST dataset.

---

### 2. Predicting Default Payments with Fully-Connected Neural Networks
**Dataset:**  
Credit card default payments of Taiwanese clients from **April 2005 to September 2005**.

**Task:**  
Build and train fully-connected neural networks (MLPs) to predict customer default behavior based on demographic data, credit history, and bill statements.

**Dataset Highlights:**
- Demographic features
- Credit data
- Payment history
- Bill statements

---

### 3. Predicting Multi-MNIST Digits

**Tasks:**
1. **Multi-class classification** of grayscale images containing **double-digit numbers** created by concatenating MNIST digits.
2. **Unsupervised learning:** implement an **Autoencoder** to encode and reconstruct the images.
3. **Additional task (choose one):**
   - Use the **latent representations** from the autoencoder for feature reduction.
   - **Explain** neural network predictions.

**Dataset Notes:**
- The original 0–100 labels were reduced for simplicity.

---

### 4. Mercari Price Suggestion Challenge (Main Project)

> This is the **largest project** in the repository and includes its own detailed README.md.

**Challenge Objective:**  
Predict product prices based on user-provided information such as:
- Product name
- Product category (three-level hierarchy)
- Brand (optional)
- Item condition (1 = New, 5 = Used)
- Text description

**Goal:**  
Assist online sellers in setting competitive prices by predicting fair values automatically.

---

### 5. Next Character Prediction on "Divina Commedia"

**Task:**  
Build a model to perform **next-character prediction** on text sequences extracted from Dante Alighieri’s **Divina Commedia**.

**Requirements:**
- Properly split sequences into training, validation, and test sets (optionally, use external text for testing).
- Evaluate the model based on **prediction accuracy**.
- Tune the **chunk length** to optimize performance.
- Modify and optimize the **network architecture** to improve results.

---

## 📂 Repository Structure

```plaintext
/
├── mnist_cnn/
├── default_prediction/
├── multi_mnist/
├── mercari_price_suggestion/
│   └── README.md
├── divina_commedia_char_prediction/
└── README.md (this file)
```

## 📢 Notes
- Each project is self-contained.
- Some projects include **additional notebooks** for exploratory analysis or model tuning.
- The repository is designed for educational purposes and highlights different machine learning techniques.
