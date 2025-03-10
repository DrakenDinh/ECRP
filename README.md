# Enhancing Cardiovascular Risk Prediction (ECRP):
This study aims to evaluate the significance of wall viscoelasticity in enhancing cardiovascular disease (CVD) risk prediction. We collected data on ten patient features, categorized into demographics (age, gender, blood pressure, smoking history), blood lab data (HDL, LDL, blood glucose levels), and wall mechanics (Peterson’s modulus, stiffness parameter, energy dissipation ratio). Outcome variables were classified as low or high CVD risk based on total plaque area computed from carotid ultrasound images. We employed eight machine learning classifiers and conducted a comparative analysis of feature importance. Incorporating mechanical attributes significantly improved predictive accuracies for all machine learning models. The Random Forest Bagging Method (RFBM) showed the best performance, achieving an accuracy of 93.0% and an AUC of 0.98 with all ten features. Including either elastic or viscous features alongside the conventional features enhanced prediction for all models. For the tree- based bagging models (DTBM and RFBM), including the viscous feature (energy dissipation ratio) alongside conventional features resulted in greater accuracy improvements compared to the elastic features. This study underscores the significant impact of integrating wall viscosity on CVD prediction and highlights the potential for combining both elastic and viscous wall characteristics to achieve more accurate risk assessment.

# Dataset:
All the data used by ECRP can be found in the "TPA_Datasets.csv" file.

# Dependency:
python 3.12.2

numpy 1.26.4

pandas 2.2.1

scikit-learn 1.4.1.post1

# Usage:
jupyter notebook train_and_test.ipynb

# Cite ECRP:
If you use ECRP for academic research, you are encouraged to cite the following paper:

@article{Dinh10032025,
author = {Duc-Manh Dinh, Belilla Yonas Berfirdu and Kyehan Rhee},
title = {Enhancing cardiovascular risk prediction: the role of wall viscoelasticity in machine learning models},
journal = {Computer Methods in Biomechanics and Biomedical Engineering},
pages = {1--12},
year = {2025},
publisher = {Taylor \& Francis},
doi = {10.1080/10255842.2025.2475479}
}
