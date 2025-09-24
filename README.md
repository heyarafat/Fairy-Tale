# Logistic-Regression
#  Iris Logistic Regression Classifier  

This project implements a **logistic regression model from scratch** using NumPy to classify Iris flowers as **Setosa** or **Non-Setosa** based on petal length and petal width. It covers every step of the machine learning workflow, including **data preprocessing, model training with gradient descent, evaluation, and decision boundary visualization**.  

---

##  Project Structure  

- **`notebook.ipynb` / `main.py`** → Core implementation of logistic regression  
- **`README.md`** → Project overview and instructions  
- **Data** → Hardcoded inside the implementation (no external dataset required)  

---

##  Features  

- **Custom Logistic Regression Implementation**  
  - Sigmoid activation function  
  - Binary cross-entropy loss function  
  - Gradient descent optimization  
  - Prediction function  

- **Visualization Tools**  
  - Cost function history over iterations  
  - Decision boundary on standardized petal features  

- **Educational Focus**  
  - No external libraries for ML (only NumPy + Matplotlib)  
  - Step-by-step breakdown for clarity and learning  

---

##  Requirements  

Install the required dependencies:  

```bash
pip install numpy matplotlib
```

---

##  Usage  

1. Clone the repository or download the project files.  
2. Run the Jupyter Notebook (`notebook.ipynb`) or Python script (`main.py`).  
3. The script will:  
   - Load the hardcoded Iris dataset subset (petal length & petal width).  
   - Standardize features.  
   - Train logistic regression using gradient descent.  
   - Plot the **cost function curve** and **decision boundary**.  

---

##  Results  

- Model correctly separates **Setosa** from other Iris species using only 2 features.  
- Training demonstrates **convergence of the cost function**.  
- Decision boundary plot provides a clear visual explanation of classification.  

---

##  Learning Outcomes  

- Understand logistic regression fundamentals.  
- Implement gradient descent manually.  
- Visualize decision boundaries in 2D feature space.  
- Gain intuition behind optimization and classification.  

---

##  Future Improvements  

- Extend classification to **3 Iris species** (multi-class logistic regression).  
- Add **regularization** to prevent overfitting.  
- Implement **accuracy metrics** and a more detailed evaluation.  

---

 *This project is designed to be a simple yet powerful demonstration of how machine learning models can be built from scratch using only NumPy. Perfect for learning, experimentation, and academic evaluation.*  
