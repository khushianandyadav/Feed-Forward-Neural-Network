**# Feedforward Neural Network on MNIST**

This project implements a simple **feedforward neural network** using TensorFlow and Keras to classify handwritten digits from the **MNIST dataset**.  
It demonstrates data preprocessing, model building, training, evaluation, and visualization of results.

---

**##  Features**
- Loads and explores the MNIST dataset (60,000 training and 10,000 test images of handwritten digits).
- Preprocesses data by normalizing pixel values.
- Builds a **3-layer feedforward neural network**:
  - Input: Flattened 28x28 pixels  
  - Hidden Layers: Two Dense layers (50 neurons each, ReLU activation)  
  - Output Layer: Dense layer with 10 neurons (Softmax activation)  
- Trains the model with SGD optimizer and sparse categorical crossentropy loss.
- Evaluates the model on the test dataset.
- Plots **accuracy** and **loss curves** for training and validation sets.
- Predicts and visualizes a random test image with predicted vs. actual label.

---

**##  Project Structure**
```

.
├── feedforward\_neural\_network.py   # Main Python script
└── README.md                       # Project documentation

````

---

**##  Requirements**
Make sure you have the following installed:

- Python 3.8+
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn

You can install dependencies with:

```bash
pip install tensorflow numpy matplotlib seaborn
````

---

##  Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/feedforward-neural-network.git
   cd feedforward-neural-network
   ```
2. Run the script:

   ```bash
   python feedforward_neural_network.py
   ```

---

##  Results

* The model achieves around **95–97% test accuracy** after training for 10 epochs (may vary).
* Example training curves:

*Model Accuracy*

* Shows increasing accuracy on training and validation sets.

*Model Loss*

* Displays decreasing loss for both training and validation sets.

---

##  Sample Prediction

The script visualizes a random test image and shows both the **predicted label** and the **actual label**.

---
