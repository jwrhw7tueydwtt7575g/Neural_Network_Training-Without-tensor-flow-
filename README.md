# MNIST Digit Classifier using NumPy

This project implements a basic 2-layer neural network from scratch using NumPy to classify handwritten digits (0-9) from the MNIST dataset.

---

## 📁 Project Structure

mnist-numpy/
│
├── DATA.csv # Pre-downloaded dataset from Kaggle
├── mnist_nn.ipynb # Main Jupyter Notebook (training & testing)
├── README.md # Project documentation

yaml
Copy
Edit

---

## 📌 Dataset Info

The dataset used is a CSV file version of the MNIST dataset from Kaggle:

- `DATA.csv` format:
  - First column: Label (digit 0-9)
  - Remaining 784 columns: Pixel values (28x28 image flattened)

Make sure your file path is correct when reading the CSV.

---

## 🧠 Model Architecture

- **Input Layer**: 784 neurons (28x28 pixels)
- **Hidden Layer**: 10 neurons (ReLU activation)
- **Output Layer**: 10 neurons (Softmax activation)

---

## 🔧 Key Components

- Data preprocessing
- One-hot encoding of labels
- ReLU and Softmax activation functions
- Forward propagation
- Backpropagation with gradient descent
- Accuracy evaluation on training and development sets

---

## ▶️ How to Run

1. Clone or download this repository.
2. Place your `DATA.csv` file in the same directory.
3. Open `mnist_nn.ipynb` in Jupyter Notebook.
4. Run the cells step by step.

---

## 📈 Sample Output

Iteration 0 : Training Accuracy = 9.87
Iteration 50 : Training Accuracy = 86.21
...
Dev Set Accuracy: 84.65

yaml
Copy
Edit

---

## ✅ Requirements

- Python 3.x
- NumPy
- Pandas
- Jupyter Notebook (or any Python IDE)

Install dependencies using:

```bash
pip install numpy pandas notebook
🧪 Notes
No external ML libraries (like TensorFlow or PyTorch) are used.

All operations (forward pass, backward pass, updates) are implemented manually using NumPy.

Great for learning how neural networks work under the hood.

✍️ Author
Vivek Mohan Chaudhari
IT Department, VIT Pune
