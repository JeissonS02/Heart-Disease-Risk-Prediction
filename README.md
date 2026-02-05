# Heart Disease Risk Prediction: Logistic Regression Homework

## Repository Overview
This repository contains a complete implementation of logistic regression
for heart disease prediction, including exploratory data analysis (EDA),
model training and visualization, regularization experiments, and a
deployment-oriented workflow using Amazon SageMaker.

---

## Exercise Summary
Implements logistic regression for heart disease prediction: EDA,
training and visualization, regularization, and SageMaker deployment.

---

## Dataset Description
The project uses the Kaggle Heart Disease Dataset, which contains
303 patient records with clinical and demographic features.

- Age range: 29–77 years
- Cholesterol range: 112–564 mg/dL
- Target variable: presence of heart disease (1) or absence (0)
- Class distribution: approximately 55% positive cases

Dataset source:
https://www.kaggle.com/datasets/neurocipher/heartdisease

---

## Deployment Evidence

The best-performing logistic regression model was prepared for deployment
using Amazon SageMaker. Model parameters (weights and bias) were exported
as NumPy arrays and an inference script was implemented to load the model
and return prediction probabilities.

Due to restricted IAM permissions in the academic AWS environment, the
creation of a real-time SageMaker endpoint was not permitted. Therefore,
the deployment process was simulated within SageMaker AI, mirroring the
logic of a production inference endpoint.

### Inference Test
Test input:
- Age = 60
- Cholesterol = 300

Model output:
- Predicted probability =  **1.000** (very high risk)

Screenshots documenting the deployment workflow and inference results are
included in the /images directory.

---

## Repository Structure

```
/
├── README.md
├── heart_disease_lr_analysis.ipynb
├── Heart_Disease_Prediction.csv
├── model/
│ ├── weights.npy
│ └── bias.npy
├── images/
│ ├── eda_overview.png
│ ├── training_convergence.png
│ ├── decision_boundary.png
│ └── inference_response.png
```
--- 

## Notes
This project demonstrates an end-to-end logistic regression workflow, including
deployment considerations, while respecting real-world constraints such as
restricted cloud permissions in educational environments.

---

## Author
**Jeisson David Sanchez Gomez**

---

## License
This project is intended for **academic use only**.




