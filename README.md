# 🚀 Deep Learning Repository

A structured collection of implementations and experiments covering core **Deep Learning architectures** including **ANN, CNN, RNN, LSTM, and GRU**, built using **PyTorch**, with **TensorFlow/Keras** used for dataset loading and preprocessing where applicable.

---

## 📂 Project Structure

```bash
DL/
│
├── ANN.ipynb                # Artificial Neural Networks
├── CNN.ipynb                # Convolutional Neural Networks
│
├── LSTM&GRU/
│   └── lstm_gru.ipynb       # LSTM vs GRU comparison (IMDB dataset)
│
├── NLP/
│   ├── Task1/
│   └── Task2/
│
├── RNN/
│   ├── data/                # Dataset storage
│   ├── RNN_image.ipynb      # RNN applied on image data
│   └── RNN_text.ipynb       # RNN applied on text data
```

---

## 🧠 Key Concepts Covered

### 🔹 **Artificial Neural Networks (ANN)**

* Basic feedforward networks
* Activation functions
* Loss functions and optimization

---

### 🔹 **Convolutional Neural Networks (CNN)**

* Image feature extraction
* Convolution, pooling, flattening
* Real-world image-based tasks

---

### 🔹 **Recurrent Neural Networks (RNN)**

* Sequence modeling
* Hidden state flow and temporal dependency
* Limitations (**vanishing gradient problem**)

---

### 🔹 **LSTM & GRU**

* **Long Short-Term Memory (LSTM)**
* **Gated Recurrent Unit (GRU)**
* Bidirectional sequence learning
* Performance comparison on text classification

---

### 🔹 **NLP Pipeline**

* Tokenization
* Vocabulary building
* Encoding & padding
* Sequence modeling using **RNN / LSTM / GRU**

---

## ⚙️ Tech Stack

* **PyTorch** → Model building, training, and evaluation
* **TensorFlow / Keras** → Dataset loading (e.g., IMDB)
* **NumPy** → Data handling
* **Matplotlib** → Visualization

---

## 🔄 Workflow Used

```text
Dataset (TensorFlow/Keras)
        ↓
Preprocessing (Tokenization, Padding)
        ↓
Conversion to PyTorch Tensors
        ↓
Model Training (RNN / LSTM / GRU)
        ↓
Evaluation & Visualization
```

---

## 📊 Experiments Included

### 🔸 **RNN vs LSTM vs GRU**

* Performance comparison on text data
* Accuracy and loss visualization
* Understanding sequence learning differences

---

### 🔸 **Custom RNN Implementation**

* Built from scratch pipeline:

  * Tokenization
  * Vocabulary
  * Encoding
  * Padding
  * DataLoader
* Applied on text classification

---

### 🔸 **LSTM vs GRU (IMDB Dataset)**

* Dataset loaded using **TensorFlow**
* Models implemented in **PyTorch**
* Graph comparison:

  * Training vs Validation Accuracy
  * Training vs Validation Loss

---

## 📈 Results & Insights

### 🔹 **RNN**

* Struggles with long-term dependencies
* Lower accuracy on long sequences

---

### 🔹 **LSTM**

* Better memory handling
* More stable training
* Slightly higher accuracy

---

### 🔹 **GRU**

* Faster training
* Comparable performance to LSTM
* Computationally efficient
I’ll fix **exact rendering issue** (sometimes indentation or tabs cause it).
