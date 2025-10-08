***Studying and Implementing Logistic Regression from Scratch***
🧩 **Introduction**

This project aims to understand and implement Logistic Regression as a fundamental Machine Learning model.
The primary goal was to explore how prediction, loss, and optimization interact during training — connecting theoretical understanding with practical implementation.

The focus was on building a working model from scratch, emphasizing the mathematical foundation of model learning rather than using pre-built ML libraries.

⚙️ **Methodology**

The Logistic Regression model was implemented step-by-step using NumPy for mathematical operations and scikit-learn for dataset preprocessing.
The main steps were:

**Defining the Hypothesis Function**

<img width="141" height="52" alt="image" src="https://github.com/user-attachments/assets/eb4be6ff-0968-4129-9b0b-481df6cb986d" />

where 𝜎 is the sigmoid activation function.

**Applying the Binary Cross-Entropy (BCE) Loss Function**

Used to measure how far predictions are from the actual labels.

**Training with Gradient Descent**

The parameters 𝑤 and 𝑏 were updated iteratively according to:
​

<img width="272" height="62" alt="image" src="https://github.com/user-attachments/assets/0dc0d3cf-e12a-4ba4-88aa-53419edbea4a" />


All learning components — the hypothesis, loss, and optimization — were implemented manually to gain a deep understanding of how Logistic Regression learns from data.

📊 **Results**

The trained model achieved an accuracy of ~97% on the Breast Cancer Wisconsin dataset.

Both loss and accuracy curves showed smooth, consistent learning and convergence.

The experiment clearly demonstrated how optimization through Gradient Descent leads to systematic improvement compared to random parameter sampling.

💡 **Reflection**

This project provided hands-on insight into how parameters, loss, and optimization interact in a Machine Learning model.
By building Logistic Regression manually, the process revealed the foundation on which more complex models — like neural networks — are built.

**Key Learnings:**

Understanding the relationship between parameter updates and model accuracy.

Observing the role of the loss function in guiding optimization.

Appreciating how gradient-based learning improves performance over time.

🧠 **Technologies Used**

**Python 3**

**NumPy** (for vectorized mathematical operations)

**scikit-learn** (for dataset loading and preprocessing)

**Matplotlib** (for plotting loss and accuracy curves)

🏁 **Summary**

This project demonstrates the complete workflow of Logistic Regression — from theoretical understanding to a working NumPy implementation.
It shows how a simple mathematical model can learn to classify real-world data accurately through systematic optimization.
