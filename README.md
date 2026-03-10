# ML for Thermal Engineers

Machine learning concepts explained through **thermal systems engineering examples**.

This repository documents a structured journey into **Machine Learning and AI from the perspective of an automotive thermal systems engineer**.

The goal is to bridge ideas from:

- Automotive HVAC systems  
- Vehicle thermal management  
- System identification and calibration  
- Data-driven modeling  

with modern **Machine Learning techniques**.

---

## Why Machine Learning for Thermal Engineers?

Thermal engineers frequently model relationships such as:

- Ambient temperature → compressor power  
- Cabin conditions → comfort perception  
- Battery temperature → cooling demand  
- Solar load → cabin heat gain  

Traditionally these relationships are captured using:

- empirical equations  
- calibration maps  
- curve fitting  
- system identification  

Machine learning extends this idea by allowing models to **learn these relationships directly from data**.

---

## Example Concept

```
Ambient Temperature + Solar Load + Cabin Conditions
                ↓
        Machine Learning Model
                ↓
      Predicted Compressor Power
```

A machine learning model can learn relationships between environmental conditions and HVAC system behavior.

---

## Repository Structure

```
ML-for-thermal-engineers/

README.md

notebooks/
    01_linear_regression_basics.ipynb
    02_gradient_descent.ipynb
    03_overfitting.ipynb
    04_multivariable_regression.ipynb
```

Each notebook introduces a concept and demonstrates it using **engineering-inspired examples**.

---

## Lessons Overview

| Lesson | Topic | Key Concept |
|------|------|------|
| 01 | Linear Regression | Learning relationships from data |
| 02 | Gradient Descent | How models learn parameters |
| 03 | Overfitting | When models learn noise |
| 04 | Multivariable Regression | Learning relationships from multiple inputs |
| 05 | Feature Engineering | Designing meaningful input variables |

---

## Learning Philosophy

Each notebook follows a consistent structure:

1. Problem Motivation  
2. Mathematical Intuition  
3. Engineering Analogy  
4. Python Implementation  
5. Visualization  
6. Key Takeaways  

The goal is to **connect machine learning concepts with real engineering intuition**.

---

## Example Applications

Examples explored in this repository may include:

- Compressor power prediction  
- Cabin comfort modeling  
- Thermal load estimation  
- EV battery thermal behavior  
- Energy optimization in vehicle climate systems  

---

## Tools Used

The notebooks use common Python ML tools including:

- numpy  
- matplotlib  
- scikit-learn  

All notebooks are designed to run easily in **Google Colab**.

---

## Author

Srikantan Natarajan  
Automotive Systems Engineer – HVAC / Thermal Systems

---

## Status

This repository is an evolving **learning journal** and will continue to grow as new machine learning concepts and experiments are added.
