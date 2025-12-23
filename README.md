## Basil Agboola

Machine Learning & Quantitative Research Engineer  
BS Computer Science (Minor in Mathematics)  
Aspiring PhD in Statistics

I focus on building **machine learning systems from first principles**, combining
statistical rigor, mathematical reasoning, and low-level systems engineering.
My interests lie at the intersection of **statistical inference, machine learning theory,
and performance-oriented implementation**.

---

## 🔬 Signature Project — LavaLamp

**LavaLamp** is a high-performance, from-scratch machine learning and statistical toolkit
written in **Rust**, designed for researchers and engineers who require
**precision, transparency, and rigorous evaluation**.

LavaLamp avoids high-level ML frameworks entirely, prioritizing full algorithmic
control, numerical stability, and interpretability.

### Implemented from Scratch
- **Artificial Neural Networks (`LavaNN`)**  
  Fully-connected networks for controlled experimentation.
- **Linear Regression (`LinearRegression`)**  
  Predictive modeling with statistical evaluation.
- **Logistic Regression (`LogisticRegression`)**  
  Binary and multiclass classification with performance metrics.
- **Data & Image Loading (`Load`)**  
  CSV pipelines and image preprocessing for modeling workflows.

LavaLamp also integrates **statistical significance testing**, including
p-value analysis and model comparison against randomized baselines.

**Design Principles**
- From-scratch implementations (no high-level ML dependencies)
- Rust-based performance and memory safety
- Research-grade experimentation
- Emphasis on interpretability and statistical validity

---

## 📊 Quantitative Research Project — Breast Cancer Diagnosis Modeling

**Final Research Product**

Breast cancer has a **12.9% lifetime probability of affecting a woman** and a
**1 in 43 probability of death following diagnosis**, representing the highest
post-diagnosis mortality odds among major cancers.

This project explored the use of classical machine learning and statistical models
as **decision-support tools for screening recommendations**, not automated diagnosis.

### Models Implemented
- Linear Regression
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Trees
- Sinusoidal Regression (comparative baseline)

### Statistical Findings
- **BMI**, when isolated against **Race**, increased feature significance in
  **3 out of 5 models**, excluding Decision Tree and Sinusoidal Regression.
- **BMI and Race jointly** increased feature significance **only in KNN**,
  based on comparative p-value analysis.
- Each model instantiation was evaluated against a **randomized baseline**
  using **Chi-Square testing** to validate statistical significance.

Results were consistent with prior literature and the project’s original hypothesis,
reinforcing the importance of feature isolation in medical inference.

---

## 🧠 Research Interests
- Statistical learning theory
- Hypothesis testing and model validation
- Machine learning from first principles
- Linear algebra, stochastic processes, graph theory
- High-performance and systems-level ML

---

## 🛠 Languages & Tools
- **Rust** — primary language for ML systems and numerical implementations
- **Python** — prototyping, data analysis, experimentation
- **SQL** — structured data handling
- **Git** — reproducible research workflows

---

## 📌 Selected Work
- **LavaLamp** — Rust-based ML & statistical toolkit from scratch
- **Breast Cancer Diagnosis Modeling** — quantitative ML and statistical inference study
