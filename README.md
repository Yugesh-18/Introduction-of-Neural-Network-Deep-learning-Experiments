# 🧠 Neural Networks Lab Experiments

A comprehensive collection of **Neural Networks and Machine Learning lab experiments** implemented using Python. This repository covers fundamental concepts starting from NumPy basics to advanced architectures like CNNs, RNNs, and Hopfield Networks.

---

## 🎯 Objective

The objective of this lab is to:

- Understand the **foundations of Neural Networks**
- Implement core ML concepts from scratch
- Explore different architectures like:
  - Perceptron
  - Multi-Layer Perceptron (MLP)
  - CNN & RNN
  - Hopfield Networks
- Visualize learning using graphs and decision boundaries

---

## 📂 Experiments Overview

| Experiment No. | Title |
|----------------|------|
| Exp 1 | NumPy Operations |
| Exp 2 | Pandas Data Analysis |
| Exp 3 | SciPy Operations |
| Exp 4 | Data Visualization using Matplotlib |
| Exp 5 | Perceptron Model (AND/OR Gates) |
| Exp 6 | XOR Problem using Neural Network |
| Exp 7 | Activation Functions |
| Exp 8 | Multi-Layer Perceptron (MLP) |
| Exp 9 | Optimizers (Gradient Descent vs Adam) |
| Exp 10 | CNN + RNN Models |
| Exp 11 | Hopfield Network |

---

## 📊 Dataset

### Description
- Synthetic datasets are used in most experiments.
- Logical datasets (AND, OR, XOR) are used for neural learning.
- Random data is generated for CNN and RNN models.

### Examples
- XOR Dataset → Used for non-linear classification  
- CNN Image Data → Random 8x8 grayscale images  
- RNN Sequence Data → Time-series random inputs  

### Preprocessing
- Normalization (implicit via small values)
- One-hot encoding (CNN/RNN)
- Train-test split (80:20 in CNN/RNN)

---

## 🏗️ Model Architecture

### 🔹 Perceptron (Exp 5)
- Single-layer neural network
- Step activation function
- Used for AND & OR classification  

---

### 🔹 XOR Neural Network (Exp 6)
- Input Layer: 2 neurons  
- Hidden Layer: 4 neurons  
- Output Layer: 1 neuron  
- Activation: Sigmoid  
- Learns non-linear separation  

---

### 🔹 Multi-Layer Perceptron (Exp 8)
- Input Layer: 2 neurons  
- Hidden Layers: 5 → 4 neurons  
- Output Layer: 1 neuron  
- Fully connected deep network  

---

### 🔹 CNN Model (Exp 10)
- Conv2D → MaxPooling → Conv2D → Dense  
- Activation: ReLU, Softmax  
- Used for image classification  

---

### 🔹 RNN Model (Exp 10)
- SimpleRNN → Dense → Dropout  
- Used for sequence prediction  

---

### 🔹 Hopfield Network (Exp 11)
- Recurrent associative memory model  
- Stores and recalls patterns using energy minimization  

---

## ⚙️ Training Process

### Common Configurations
- **Loss Functions**:
  - MSE (XOR, MLP)
  - Categorical Crossentropy (CNN, RNN)
- **Optimizers**:
  - Gradient Descent
  - Adam Optimizer  
- **Epochs**:
  - XOR: 5000
  - MLP: 6000
  - CNN/RNN: 10

### Techniques Used
- Forward Propagation  
- Backpropagation  
- Gradient Descent  
- Weight Updates using derivatives  

---

## 📈 Results

### Key Observations

- Perceptron correctly classifies **linearly separable data**
- XOR requires **hidden layers**
- MLP improves learning of complex patterns
- Adam optimizer converges faster than Gradient Descent
- CNN & RNN achieve good accuracy on synthetic data

### Metrics (Example)

| Model | Accuracy |
|------|---------|
| Perceptron (AND/OR) | ~100% |
| XOR Network | ~100% |
| MLP | ~100% |
| CNN | ~85–95% |
| RNN | ~80–90% |

### Visualizations
- Loss vs Epoch graphs  
- Decision boundaries  
- Optimizer comparison graphs  
- CNN/RNN accuracy curves  

---

## 📁 Code Structure

Neural-Networks-Lab\
│── Exp1.py # NumPy Basics\
│── Exp2.py # Pandas Operations\
│── Exp3.py # SciPy Functions\
│── Exp4.py # Data Visualization\
│── Exp5.py # Perceptron\
│── Exp6.py # XOR Neural Network\
│── Exp7.py # Activation Functions\
│── Exp8.py # MLP\
│── Exp9.py # Optimizers\
│── Exp10.py # CNN + RNN\
│── Exp11.py # Hopfield Network\
│── README.md

---

## 🧰 Setup and Dependencies

### Required Libraries

- Python 3.x  
- NumPy  
- Pandas  
- Matplotlib  
- SciPy  
- TensorFlow  
- Scikit-learn  

### Installation

```bash
pip install numpy pandas matplotlib scipy tensorflow scikit-learn
```

▶️ How to Run

Run any experiment individually:
```bash
python exp5.py
```
Examples:
```bash
python exp6.py   # XOR Neural Network
python exp10.py  # CNN + RNN
```
## 📌 Conclusion

This lab experiment series successfully demonstrates the **fundamental concepts and practical implementation of Neural Networks**, starting from basic numerical operations to advanced deep learning architectures.

Throughout the experiments, we observed the progression:

- From simple data manipulation (NumPy, Pandas, SciPy)
- To visualization techniques (Matplotlib)
- To core neural models (Perceptron, XOR Network, MLP)
- To advanced architectures (CNN, RNN, Hopfield Network)

### 🔍 Key Insights

- **Perceptron** works only for linearly separable problems  
- **Hidden layers** are essential for solving non-linear problems like XOR  
- **Activation functions** significantly impact model performance  
- **Optimizers** like Adam converge faster than standard Gradient Descent  
- **Deep learning models (CNN & RNN)** handle complex data such as images and sequences effectively  
- **Hopfield Networks** demonstrate associative memory and energy-based learning  

### ⚠️ Limitations

- Most datasets used are **synthetic**, not real-world  
- Models are relatively **small-scale**  
- Limited hyperparameter tuning  
- CNN/RNN experiments use random data instead of benchmark datasets  

### 🚀 Future Work

- Use real-world datasets like **MNIST, CIFAR-10**  
- Implement advanced optimizers (**RMSProp, AdamW**)  
- Explore deeper architectures and regularization techniques  
- Apply concepts to real-world applications (image classification, NLP)  

---

Overall, this lab provides a **strong foundation in Neural Networks**, combining theoretical understanding with hands-on implementation.
