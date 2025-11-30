# 📘 Interpretable AI: Why Logistic Regression Still Matters in the Era of Deep Learning

This project demonstrates why **logistic regression remains one of the most important models in machine learning**, despite the rise of deep learning and large neural networks.

Using a real dataset and two models — a neural network and a logistic regression classifier — the project highlights interpretability, performance, and model transparency in high-stakes decision settings.

---

## 🔍 Project Motivation

As AI becomes powerful and complex, the need for **transparent, accountable, and interpretable** models becomes even more important, especially in:

- healthcare  
- humanitarian targeting  
- fraud detection  
- public policy  
- credit scoring  
- model fairness audits  

Logistic Regression (LR) is still widely used because:

- every parameter has a clear meaning  
- feature effects can be quantified  
- decision boundaries are mathematically simple  
- the model is stable, predictable, and explainable  
- it satisfies regulatory requirements for explainability  

This notebook shows this **side-by-side with a neural network**.

---

## 🧪 Models Included

### **1. Neural Network (Deep Learning)**
A simple feed-forward neural network was trained as a baseline “modern” model.

- Non-linear  
- Higher representational power  
- Harder to interpret  
- Often overkill for tabular data  

### **2. Logistic Regression**
Classical interpretable model.

- Coefficients show *direction* of impact (positive or negative)
- Odds ratios show *strength* of impact
- Easy to audit  
- Transparent decision process  

---

## 📊 Key Interpretability Outputs

### **✔ Odds Ratios**
The notebook computes odds ratios (OR):

- **OR > 1:** increases the odds of the positive outcome  
- **OR = 1:** no effect  
- **OR < 1:** decreases the odds  

This allows stakeholders to understand **which features truly matter**.

---

### **✔ ROC Curve & AUC**

Your model achieved:

- **AUC = 0.996** (outstanding!)  
- The ROC curve hugs the **top-left corner**, showing:
  - extremely high true positive rate  
  - extremely low false positive rate  

This proves that logistic regression can **match or outperform deeper models** on well-structured data.

---

### **✔ Confusion Matrix**

The confusion matrix (notebook output) helps explain:

- sensitivity  
- specificity  
- false positives  
- false negatives  

This provides clarity in high-stakes applications.

---

## 📂 Repository Structure

