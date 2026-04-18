# Assignment12_AI
# Image Classification Using a Feedforward Neural Network

## 📌 Project Overview
This project demonstrates the application of a **feedforward neural network** (fully connected neural network) to an **image classification** task using the **Fashion‑MNIST** dataset. The goal is to gain hands‑on experience with neural network architectures and understand how deep learning approaches differ from traditional machine learning techniques in handling image data.

The project was developed in **Google Colab** using **TensorFlow/Keras** and evaluates the model using multiple performance metrics, including accuracy, precision, recall, F1‑score, and confusion matrices.

---

## 📂 Dataset
**Fashion‑MNIST**  
- 70,000 grayscale images (28×28 pixels)  
- 10 clothing categories  
- Split:
  - 60,000 training images
  - 10,000 test images  

📎 Dataset source:  
https://github.com/zalandoresearch/fashion-mnist

**Class Labels**
- T‑shirt/top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle boot

---

## 🧠 Model Architecture
This project uses a **simple feedforward neural network** (not a CNN):

- **Input Layer:** Flattened 28×28 image (784 features)
- **Hidden Layer 1:** 256 neurons, ReLU activation
- **Hidden Layer 2:** 128 neurons, ReLU activation
- **Output Layer:** 10 neurons, Softmax activation

**Optimizer:** Adam  
**Loss Function:** Categorical Crossentropy  
**Evaluation Metric:** Accuracy  

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Normalization of pixel values to the range **[0,1]**
- One‑hot encoding of class labels
- Visualization of sample images from each class

### 2. Model Training
- Batch size: 64  
- Epochs: 15  
- Validation split: 20%  

### 3. Model Evaluation
- Classification accuracy on test dataset
- Precision, recall, and F1‑score
- Confusion matrix visualization
- Training and validation accuracy/loss plots

---

## 📊 Results
- Achieved strong classification performance for a non‑convolutional neural network
- Most confusion occurs between visually similar classes (e.g., *Shirt*, *T‑shirt/top*, and *Pullover*)
- Demonstrates the advantages of deep learning over traditional ML even with a simple architecture

---

## 💡 Practical Application
A trained version of this model could be applied in:
- Fashion retail product categorization
- Automated inventory management
- Image‑based product search systems

**Deployment Considerations**
- Scalability for large‑scale systems
- Real‑time inference requirements
- Integration with existing databases and APIs

---

## 🚀 Future Improvements
- Replace the feedforward model with **Convolutional Neural Networks (CNNs)**
- Apply **data augmentation** to improve generalization
- Use **transfer learning** with pretrained models
- Optimize the model for real‑time deployment (TensorFlow Lite)

---

## 🛠️ Technologies Used
- Python 3
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit‑learn

---

## ▶️ How to Run
1. Open the provided notebook in **Google Colab**
2. Ensure GPU runtime is enabled (optional but recommended)
3. Run all cells sequentially
4. Review generated plots, metrics, and model outputs

---

## 📄 License
This project is intended for educational purposes only.

---

## ✍️ Author
**Patricia Sekai Mapimbiro**

---

If you'd like, I can also:
✅ Create a **short README version**  
✅ Align this README to a specific course rubric  
✅ Generate the **2‑page PDF report**  
✅ Add **badges and visuals** for GitHub  

Just let me know!
