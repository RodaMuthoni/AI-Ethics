# AI-Ethics

# COMPAS Dataset Bias Audit and Mitigation

This project performs a fairness audit and bias mitigation analysis on the COMPAS (Correctional Offender Management Profiling for Alternative Sanctions) dataset. The goal is to identify and visualize potential racial biases in risk assessments, demonstrate the impact of those biases, and explore possible remediation techniques.

## 📊 Project Overview

The COMPAS dataset has been widely criticized for exhibiting racial bias in criminal risk prediction. In this project, we:

- Analyze the dataset for disparities in risk scores and recidivism predictions across racial groups.
- Visualize key patterns and potential sources of bias.
- Apply fairness metrics such as **Disparate Impact Ratio** and **False Positive Rate**.
- Demonstrate bias mitigation strategies using machine learning techniques.

## ⚙️ Features

- ✅ Data Loading using AIF360 or synthetic fallback
- ✅ Exploratory data analysis
- ✅ Fairness metric calculations
- ✅ Visual bias diagnostics using Matplotlib and Seaborn
- ✅ Disparate impact and false positive rate analysis
- ✅ Baseline model training with Random Forest
- ✅ Bias mitigation strategies overview
- ✅ Text-based bias audit report generation
- ✅ Visual output in `compas_bias_analysis.png`

## 🧪 Technologies Used

- Python
- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib
- AIF360 (AI Fairness 360 by IBM)

## 📂 File Structure

```bash
.
├── compas_bias_analysis.png           # Generated visualizations
├── compas_bias_audit_report.txt       # Full audit report
├── bias_audit_script.py               # Main Python script
├── README.md                          # Project documentation

🚀 How to Run
Install required packages:

pip install pandas numpy matplotlib seaborn scikit-learn aif360

If aif360 fails to install, the code will fallback to generating synthetic COMPAS-like data.

Run the script:

python bias_audit_script.py

Outputs:

compas_bias_analysis.png - Visual representation of biases.

compas_bias_audit_report.txt - A detailed textual audit report.

📈 Metrics Included
Disparate Impact Ratio
Measures fairness of high-risk classification between protected and unprotected groups. A ratio < 0.8 indicates potential bias.

False Positive Rate (FPR)
Measures the rate at which individuals are incorrectly classified as high risk.

📷 Sample Visuals
Visualizations include:

Risk score distribution by race

Recidivism rate by race

High-risk classification rate by race

False positive rates across racial groups

✅ Mitigation Strategies Suggested
Data Rebalancing

Fairness Constraints During Training

Post-Processing Adjustments

Use of Algorithms like Reweighing or Prejudice Remover

👥 Contributors
This project was developed by:

Roda Nyamai

Valentine Sabulkong

Rose Onyango

Michael Randa

We collaboratively implemented the bias audit logic, designed visualizations, and drafted the audit report in line with AI fairness principles.

📜 License
This project is released under the https://opensource.org/licenses/MIT





