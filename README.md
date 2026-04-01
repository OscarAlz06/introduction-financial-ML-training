# Machine Learning Training: Credit Approval

## Project Overview

This repository contains the material from an **introductory Machine Learning training** focused on financial applications, specifically **credit approval prediction**.

The project demonstrates how to build a simple and interpretable model using a **Decision Tree** to classify whether a credit should be approved or rejected.

---

## Objective

To show, in a practical and intuitive way, how Machine Learning can support decision-making using structured data.

The model predicts:

> **Credit Status** → Approved (True) or Rejected (False)

---

## Dataset

A **synthetic dataset** was created to simulate a real financial scenario.

### Input Features (X)

- `Ingreso_mensual` → Ingresos del cliente  
- `Tipo_ingreso` → Empleado / Independiente  
- `Edad` → Edad del cliente  
- `Ratio_deuda_ingreso` → Nivel de endeudamiento (%)  
- `Historial_mora` → Con mora / Sin mora  
- `Monto_credito` → Monto solicitad 

### Target Variable (Y)

- `Estado_credito` → True (Aprobado) / False (Rechazado)

---

## Model

A **Decision Tree Classifier** was used due to its:

- Interpretability  
- Simplicity  
- Ability to explain decisions step-by-step  

The model learns rules such as:
- Higher debt → higher risk  
- Past delinquency → likely rejection  

---

## Evaluation

Model performance is evaluated using:

- Accuracy  
- Confusion Matrix  

This helps understand not only how many predictions are correct, but also **where the model makes mistakes**.

---

## Data Leakage

The project includes a practical demonstration of **data leakage**, using variables such as:

- `Approved_amount`  
- `Interest_rate`  

These variables artificially improve performance because they contain **future information**.

> Key takeaway:  
> A highly accurate model is not always a good model.

---

## Key Learnings

- Machine Learning is about **learning patterns from data**  
- Data quality and timing matter more than model complexity  
- Interpretability is crucial in financial applications  
- Avoiding data leakage is essential for real-world deployment  

---

## Notes

- This project is designed for **educational purposes**  
- Focused on simplicity and clarity rather than complexity  

---

## Additional Resources

Presentation used in the training:  https://canva.link/xjmlknmd9t3subz

