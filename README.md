# Machine Learning for Thermal Engineers

A hands-on learning repository exploring how machine learning concepts can be applied to real-world thermal engineering problems — with a focus on automotive HVAC systems.

---

## 🔍 Overview

This repository documents a structured learning journey through machine learning fundamentals, built from the perspective of a thermal systems engineer.

Rather than using generic datasets, the focus is on:

- applying ML to physically meaningful problems  
- connecting engineering intuition with data-driven models  
- building interpretable models aligned with real system behavior  

---

## 🚗 Featured Notebook

### Physics-Informed HVAC Cooling Predictor

This notebook demonstrates how machine learning can be used to model HVAC compressor power using engineering-informed features.

#### Key Concepts:
- Temperature error as base cooling demand  
- Solar load as an amplification factor  
- Interaction features (CoolingIndex = TempError × SolarLoad)  
- Feature scaling for fair comparison  
- Ridge regression for stability  

#### Key Insight:
Instead of relying on raw variables, the model learns that **interaction between temperature error and solar load** plays a dominant role in cooling demand — closely reflecting real HVAC behavior during solar soak conditions.

🔗 Open Notebook:  
[www.github.com/natnakirs/ML-for-thermal-engineers/blob/main/notebooks/08_HVAC_Cooling_Predictor_Model.ipynb]

---

## 📘 Lessons Covered

### 1. Linear Regression Basics
- Understanding relationships between variables  
- Connecting regression to engineering curve fitting  

### 2. Gradient Descent
- Optimization fundamentals  
- Learning rate and convergence behavior  

### 3. Overfitting
- Model complexity vs generalization  
- Bias-variance tradeoff  

### 4. Multivariable Regression
- Multiple inputs affecting system behavior  
- Extending simple models to realistic systems  

### 5. Feature Engineering
- Creating meaningful variables (e.g., TempError)  
- Using engineering insight to improve models  

### 6. Regularization (Ridge & Lasso)
- Handling correlated features  
- Stabilizing models  
- Automatic feature selection  

### 7. Feature Scaling & Normalization
- Why scaling matters  
- Interpreting coefficients correctly  
- Ensuring fair regularization  

### 8. HVAC Cooling Predictor (Applied ML)
- Combining all concepts into a real engineering problem  
- Physics-informed feature design  
- Interpretable machine learning model  

---

## 🧠 Learning Philosophy

This repository follows a simple idea:

> Machine learning becomes significantly more powerful when combined with domain expertise.

Instead of treating ML as a black box:

- physics guides feature design  
- models are interpreted, not just trained  
- results are validated against real-world intuition  

---

## ⚙️ Tools Used

- Python  
- NumPy & Pandas  
- Matplotlib  
- Scikit-learn  
- Google Colab  

---

## 🚀 Future Work

- Time-dependent cabin cooling models  
- Incorporation of thermal mass effects  
- Control-oriented ML models for HVAC systems  
- Integration with real-world datasets  

---

## 🤝 Contributions & Feedback

If you're working in:

- thermal systems  
- automotive HVAC  
- controls engineering  
- applied machine learning  

I’d love to hear your thoughts and feedback.

---

[## 🔗 Connect]

Feel free to connect with me on LinkedIn to discuss:

- thermal systems engineering  
- machine learning applications  
- automotive HVAC challenges  

[www.linkedin.com/in/srikantan-natarajan/]
