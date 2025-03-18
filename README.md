# Ethical Considerations in Data Science

## About This Repository
This repository explores ethical considerations in data science through practical labs and analyses. The content focuses on understanding biases, disparities, and ethical challenges that arise in real-world data. Each lab includes data exploration, visualizations, and discussions to foster critical thinking about responsible data use.

## Repository Structure
This repository includes multiple Jupyter Notebooks that analyze different aspects of fairness, bias, and interpretability in machine learning models. Below is an overview of the key files:

### Bias in Algorithmic Risk Assessment
- **Description:** This notebook reproduces and analyzes ProPublica's investigation into the COMPAS risk assessment tool. It explores racial and gender disparities in the predictive accuracy of COMPAS scores.
- **Key Analyses:**
  - Data preprocessing and exploratory data analysis (EDA)
  - Logistic regression model to assess bias in COMPAS scores
  - False positive and false negative rate calculations by race and gender
  - Discussion on fairness and ethical implications

### Exploring Randomized Response
- **Description:** Investigates the concept of randomized response, a technique used in differential privacy to protect individual responses.
- **Key Analyses:**
  - Implementation of multiple randomized response algorithms
  - Calculation of privacy parameter (epsilon) for different approaches
  - Simulated dataset demonstrating the balance between privacy and accuracy
  - Discussion on privacy-preserving techniques in data collection

### Gender-Based Salary Disparities
- **Description:** Analyzes salary disparities based on gender, highlighting potential discrimination in promotion practices.
- **Key Analyses:**
  - EDA and salary distribution comparisons across genders
  - Bar plots visualizing salary differences over time
  - Rank distribution analysis
  - Discussion on potential biases in hiring and promotion

### Interpretable Machine Learning with LIME
- **Description:** Introduces the LIME (Local Interpretable Model-Agnostic Explanations) framework to explain machine learning predictions.
- **Key Analyses:**
  - Feature importance analysis for gradient-boosted decision trees
  - Generating local explanations with LIME for individual predictions
  - Global explanations using submodular pick (SP-LIME)
  - Comparison with SHAP values for model interpretability

### Mitigating Bias in Machine Learning: SMOTE
- **Description:** Examines fairness in machine learning models and applies Synthetic Minority Over-sampling Technique (SMOTE) to address dataset imbalances.
- **Key Analyses:**
  - Training a logistic regression model and analyzing bias in predictions
  - Fairness metrics evaluation for privileged vs. unprivileged groups
  - Applying SMOTE to rebalance the dataset and re-evaluating fairness metrics
  - Discussion on pre-processing bias mitigation techniques

## Key Ethical Themes Addressed
- Algorithmic fairness and bias
- Privacy-preserving data collection
- Disparities in predictive accuracy across demographic groups
- Interpretability and explainability of machine learning models
- Strategies for mitigating bias in machine learning

## Tools & Libraries Used
- Python (`pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, `scikit-learn`, `imbalanced-learn`)
- LIME for explainable AI
- SHAP for feature importance analysis
- Logistic regression and decision trees for predictive modeling

## Contributors
- **Lance Santana**
- **Cole Hammes**

## References & Acknowledgments
- ProPublica's COMPAS Analysis
- UCI Machine Learning Repository
- Academic discussions on fairness, bias, and interpretability in AI
- ChatGPT as a teaching and instructional tool for code explanations and concept reinforcement

## License
This repository is for educational and research purposes. Please cite appropriately if using any of the content in academic or professional work.
