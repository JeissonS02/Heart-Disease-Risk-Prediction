# Heart Disease Risk Prediction: Logistic Regression Homework
## Introductory Context
Heart disease is the world's leading cause of death, claiming approximately 18 million lives each year, as reported by the World Health Organization. Predictive models like logistic regression can enable early identification of at-risk patients by analyzing clinical features such as age, cholesterol, and blood pressure. This not only improves treatment outcomes but also optimizes resource allocation in healthcare settings. In this homework, you'll implement logistic regression on the Heart Disease Dataset—a real-world UCI repository collection of 303 patient records with 14 features and a binary target (1 for disease presence, 0 for absence). You'll train models, visualize boundaries, apply regularization, and explore deployment via Amazon SageMaker to mimic a production pipeline.


## Repository Structure

```
/
├── README.md                           # Project documentation
├── heart_disease_lr_analysis.ipynb     # Linear Regression with one feature
├── Heart_Disease_Prediction.csv        # DataSet
├── /images                             # Screenshoots of laboratory evidence
```

## Dataset and Notation

| 🧬 Column Name | 📝 Description |
|--------|------------- |
| **🧓 Age** | Age of the patient (in years) |
| **🚹 Sex** | Gender of the patient (**1 = Male, 0 = Female**) |
| **💔 Chest pain type** | Stellar luminosity | 
| **💉 BP** | Resting blood pressure (mm Hg) | 
| **🧈 Cholesterol** | Serum cholesterol level (mg/dL) | 
| **🍬 FBS over 120** | Fasting blood sugar > 120 mg/dL (1 = True, 0 = False) | 
| **📈 EKG results** | Resting electrocardiogram results: | 
| **❤️ Max HR** | Maximum heart rate achieved | 
| **🏃 Exercise angina** | Exercise-induced angina (**1 = Yes, 0 = No**) | 
| **📉 ST depression** | ST depression induced by exercise relative to rest | 
| **⛰️ Slope of ST** | Slope of the peak exercise ST segment | 
| **🩸 Number of vessels fluro** | Number of major vessels (0–3) colored by fluoroscopy | 
| **🧬 Thallium** | Thallium stress test result (categorical medical indicator) | 
| **🎯 Heart Disease** | Target variable: | 


