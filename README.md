
# 🧮 Multi-Feature Linear Regression

This project implements a **multi-variable linear regression** model using Python and NumPy. It shows how linear regression can be extended from one feature to multiple features and includes step-by-step implementation of the hypothesis function, cost function, and gradient descent algorithm.

---

## 🧠 What You’ll Learn

- How linear regression works with multiple input features.
- Vectorized implementation of the hypothesis function.
- Efficient cost function computation using matrix operations.
- Applying gradient descent to optimize model parameters.
- Data normalization for faster convergence.

---

## 📂 Project Structure

```
multi-feature-linear-regression.ipynb
README.md
data.csv (optional)
```

---

## 🧪 How to Run

### 🔧 Requirements

- Python 3.x
- NumPy
- Matplotlib
- Jupyter Notebook

### ▶️ Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/multi-feature-linear-regression.git
   cd multi-feature-linear-regression
   ```

2. Install dependencies:
   ```bash
   pip install numpy matplotlib
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook multi-feature-linear-regression.ipynb
   ```

---

## 📊 Example

Given a dataset with multiple features `X1, X2, ..., Xn`, the model fits a linear function of the form:

```
y = w1*x1 + w2*x2 + ... + wn*xn + b
```

It uses **gradient descent** to minimize the **Mean Squared Error** between predicted and actual values.

---

## 📌 Key Functions

- `compute_cost(X, y, w, b)`
- `gradient_descent(X, y, w, b, alpha, iterations)`
- `predict(X, w, b)`
- `z_score_normalize_features(X)` (optional for normalization)

---

## 📎 Dataset

You can use a CSV file or hardcoded matrix with multiple features and a target value:

```csv
X1,X2,X3,y
2104,5,1,460
1600,3,2,330
...
```

---

## 📈 Output Visualization

The notebook may visualize:
- Convergence of cost function
- Optional 3D plots (for 2-feature cases)
- Final learned weights and bias

---

## ✅ Status

✅ Fully implemented  
✅ Vectorized & efficient  
✅ Works on any number of features  
✅ Easy to customize

---

## 🧑‍💻 Author

**Bharath**  
_Contact for suggestions or contributions_

---

## 📄 License

This project is licensed under the MIT License.
