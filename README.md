# Explainable-Deep-Learning-Model-to-Diagnose-Alzheimer-s-Disease-with-Tabular-Data
Interpretable AI for Alzheimer's diagnosis using tabular clinical data and SHAP explanations.


# Interpretable AI for Alzheimer's Diagnosis

This project explores the development of interpretable deep learning models for the diagnosis of Alzheimer's Disease using clinical data from the NACC (National Alzheimer's Coordinating Center) database.

## 🔍 Objectives

- Build a robust binary classifier to distinguish between healthy individuals and patients with Alzheimer's.
- Integrate SHAP (SHapley Additive exPlanations) for local and global model interpretability.
- Enable clinician-friendly visualizations and diagnostic reports.
- Explore potential extensions to neuroimaging data (MRI/PET) in future phases.

## 🧠 Data

- **Source**: NACC Uniform Data Set (UDS)
- **Features**: Demographics, cognitive test scores, clinical assessments, and medical history
- **Preprocessing**: Missing value handling, standardization, feature selection

## 🛠️ Technologies

- Python, TensorFlow/Keras
- SHAP for explainability
- Optuna for hyperparameter tuning
- Pandas, NumPy, Scikit-learn
- Streamlit (planned) for frontend integration
- PDF/Markdown generation for clinical reports

## 📊 Key Contributions

- Interpretable predictions at individual and population level
- Automated report generation combining model outputs and textual analysis via LLMs
- Modular and extensible codebase for future data types and modalities

## 🧪 Work in Progress

- Integration of MRI-based CNN models
- Deployment of a clinician-oriented diagnostic dashboard
- Clinical validation and feedback loops

## 📄 License

MIT License

---

> This project is part of an academic research initiative focused on building trustworthy AI for neurodegenerative disease diagnosis.
