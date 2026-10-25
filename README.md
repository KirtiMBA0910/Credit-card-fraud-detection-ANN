# Credit Card Fraud Detection & Risk Analytics

## Project Overview
This project explores credit card transaction data to identify potentially fraudulent transactions using machine learning. It combines data analysis, model evaluation, and business-focused risk visualisation.

## Business Problem
Credit card fraud is a highly imbalanced classification problem. The objective is to identify suspicious transactions while reducing missed fraud cases and unnecessary false alerts.

## Project Objectives
- Analyse transaction and fraud patterns.
- Prepare transaction data for machine learning.
- Explore classification techniques for fraud detection.
- Evaluate models using Precision, Recall, F1-score, Confusion Matrix, and ROC-AUC.
- Present useful business insights through a Power BI dashboard.

## Tools & Technologies
- Python
- Pandas and NumPy
- Scikit-learn
- Artificial Neural Networks (ANN)
- SQL
- Power BI
- Jupyter Notebook / Google Colab

## Repository Files
| File | Description |
|---|---|
| `fraud_dashboard.pbix` | Power BI dashboard file |
| `requirements.txt` | Python package requirements |
| `README.md` | Project documentation |
| `.gitignore` | Files excluded from Git tracking |

## Project Workflow
1. Load and inspect the transaction dataset.
2. Clean and prepare the data.
3. Explore class imbalance and transaction patterns.
4. Train and evaluate the implemented machine-learning model(s).
5. Review classification metrics.
6. Present findings through Power BI visualisations.

## Model Evaluation
Fraud detection requires more than accuracy because fraudulent transactions may represent a small fraction of all records. Precision, Recall, F1-score, the Confusion Matrix, and ROC-AUC provide a more informative evaluation.

**Verified model results:** Add the metrics produced by your actual notebook here. Do not enter estimated or unverified scores.

## Power BI Dashboard
The repository includes `fraud_dashboard.pbix`. Open it using Microsoft Power BI Desktop to inspect the available dashboard pages and visualisations.

*Add a dashboard screenshot here when available.*

## Limitations
- Results depend on the quality and representativeness of the dataset.
- Class imbalance can affect model evaluation.
- A predicted transaction risk is not definitive proof of fraud.
- Performance should be validated on unseen data before practical use.

## Future Improvements
- Compare additional classification algorithms.
- Improve model explainability.
- Add more detailed fraud-pattern analysis.
- Enhance the dashboard with additional business KPIs.

## Author
**Kirti Rajput**  
MBA — Data Science & Artificial Intelligence

## Academic Use
This project is developed for academic learning and portfolio demonstration.
