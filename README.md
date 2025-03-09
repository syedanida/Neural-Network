# 🚀 Deep Neural Network for Non-Linear Regression  

## 🔥 Overview  
This repository contains **multiple implementations** of a **3-layer deep neural network** for non-linear regression, built from scratch using **NumPy, PyTorch, and TensorFlow**.  

Each implementation follows the required constraints:  
✅ **Custom 3-layer architecture**
✅ **Uses `tensorflow.einsum` instead of `matmul`**  
✅ **Implements a 3-variable non-linear equation** instead of 2-variable  
✅ **Generates synthetic data & visualizes it in a 4D plot**  

---

## 📌 Project Structure  

| Folder/File | Description |
|------------|-------------|
| `colab_numpy/` | NumPy-based 3-layer deep neural network with manual backpropagation |
| `colab_pytorch_manual/` | PyTorch implementation **without built-in layers** (fully custom) |
| `colab_pytorch_classes/` | PyTorch implementation **with built-in modules** |
| `colab_pytorch_lightning/` | PyTorch **Lightning** version |
| `colab_tf_low_level/` | TensorFlow implementation **from scratch** (without high-level API) |
| `colab_tf_builtin/` | TensorFlow implementation **using built-in layers** |
| `colab_tf_functional/` | TensorFlow **Functional API** version |
| `colab_tf_high_level/` | TensorFlow **high-level API** version |
| `plots/4D_plot.ipynb` | **4D visualization of synthetic data** for 3-variable non-linear function |

---

## 📌 Part A: NumPy Implementation  

🔹 **Manual 3-layer deep neural network from scratch**  
🔹 **Uses non-linear activation functions**  
🔹 **Manual backpropagation with chain rule**  

📌 **Colab Notebook:** [🔗 NumPy Neural Network](#)  

---

## 📌 Part B: PyTorch Implementations  

### 🚀 **PyTorch Custom (No Built-in Layers)**  
✅ Implements a **fully custom 3-layer neural network**  
✅ Uses **manual weight updates & activation functions**  

📌 **Colab Notebook:** [🔗 PyTorch Manual](#)  

### 🔥 **PyTorch Classes-Based (With Built-in Modules)**  
✅ Uses **`nn.Module` for defining the network**  
✅ Implements **backpropagation & loss optimization**  

📌 **Colab Notebook:** [🔗 PyTorch Classes](#)  

### 🏆 **PyTorch Lightning Implementation**  
✅ Uses **PyTorch Lightning** for structured model training  
✅ Automatically handles **training loop, loss tracking, and optimization**  

📌 **Colab Notebook:** [🔗 PyTorch Lightning](#)  

---

## 📌 Part C: TensorFlow Implementations  

### 📜 **TensorFlow from Scratch (No High-Level API)**  
✅ Implements **low-level TensorFlow ops**  
✅ Uses **`tensorflow.einsum` instead of matrix multiplication**  

📌 **Colab Notebook:** [🔗 TensorFlow Low-Level](#)  

### 🚀 **TensorFlow with Built-in Layers**  
✅ Uses **`tf.keras.layers` to build the 3-layer network**  

📌 **Colab Notebook:** [🔗 TensorFlow Built-in Layers](#)  

### 🔥 **TensorFlow Functional API**  
✅ Uses **Functional API for model definition**  
✅ Easily extends for complex architectures  

📌 **Colab Notebook:** [🔗 TensorFlow Functional API](#)  

### 🏆 **TensorFlow High-Level API**  
✅ Uses **`tf.keras.Sequential` for simple model definition**  

📌 **Colab Notebook:** [🔗 TensorFlow High-Level API](#)   

---

## 📌 Part D: 4D Plot Visualization  

📌 **Colab Notebook:** [🔗 4D Visualization](#)   

✅ Generates **synthetic data** using the **3-variable non-linear equation**  
✅ Uses **Matplotlib to create a 4D scatter plot**  

---

## 🎬 Video Demonstrations  

**Each notebook is accompanied by a video walkthrough:**  
🔗 **[Full Playlist](#)**  
