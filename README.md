# Neural Network from Scratch for Handwritten Digit Recognition

This project implements a feedforward neural network **from scratch** (using only Python and NumPy) to classify handwritten digits from the **MNIST dataset**.
The aim is to understand the inner workings of neural networks without relying on deep learning libraries like TensorFlow or PyTorch.

---

## 🚀 Features

* Manual implementation of:

  * Weight initialization
  * Forward propagation
  * Activation functions (ReLU, Softmax)
  * Backpropagation with gradient descent
* Trains on the MNIST dataset (28x28 grayscale images).
* Loss and accuracy tracking across epochs.
* Visualization of predictions and training progress.

---

## 🛠️ Tech Stack

* **Python**
* **NumPy**
* **Matplotlib**
* **Jupyter Notebook**

---

## 📂 Project Structure

```
Neural_Network_from_Scratch/
│── Neural_Network_from_Scratch_for_Handwritten_Digit_Recognition.ipynb  # Main notebook
│── README.md
│── requirements.txt  (optional, if you want to include dependencies)
```

---

## 📊 Results

* The model is able to learn digit classification through backpropagation.
* Predictions on test samples show correct recognition of digits.
* Training and loss curves are plotted for better understanding.

*(You can add accuracy numbers or sample output images here once you run and save them.)*

---

## ⚡ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/Neural_Network_from_Scratch.git
   cd Neural_Network_from_Scratch
   ```
2. Install dependencies:

   ```bash
   pip install numpy matplotlib
   ```
3. Open the notebook and run:

   ```bash
   jupyter notebook Neural_Network_from_Scratch_for_Handwritten_Digit_Recognition.ipynb
   ```

---

## 📌 Learning Outcome

By building this project, I gained a deeper understanding of:

* How neural networks learn from data.
* The role of forward propagation, activation functions, and backpropagation.
* Implementing optimization from first principles.

---

## 🔮 Future Work

* Add more hidden layers for deeper architecture.
* Experiment with different optimizers (SGD with momentum, Adam).
* Deploy as a simple web demo with Gradio or Streamlit.

---

## 👨‍💻 Author

**Vaibhav Anand**

* [LinkedIn](https://www.linkedin.com/in/vaibhav-anand-037540232)
* [GitHub](https://github.com/3-vaibhav)
