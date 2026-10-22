# CSET485 — AI and Society
## Assignment 1: Predictive Models, Stress Tests, and Fairness

### Overview
This project evaluates Linear Regression (OLS) and Logistic Regression using the Adult Census Income dataset. It examines model predictions, subgroup differences, omitted-variable bias, adversarial errors, and fairness trade-offs.

### Dataset
- **Name:** Adult Census Income
- **Source:** UCI Machine Learning Repository
- **Dataset ID:** 2
- **Python package:** `ucimlrepo`
- **Random state:** 737
- **Train-test split:** 70% training, 30% testing

### Objectives
- Import and explore the dataset.
- Clean and preprocess numerical and categorical features.
- Train and evaluate OLS and Logistic Regression models.
- Compare model predictions and identify disagreements.
- Analyse differences across demographic subgroups.
- Test sensitivity to omitted variables.
- Investigate high-confidence incorrect predictions.
- Evaluate fairness using demographic parity, equalized odds, and predictive parity.

### Tools and Libraries
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Statsmodels
- Scikit-learn
- SciPy
- UCI ML Repository (`ucimlrepo`)

### Project Files
- `CSET485_Assignment.ipynb` — notebook containing the code, analysis, and outputs.
- `requirements.txt` — Python dependencies, if included.
- Result tables and charts — generated analysis outputs, if included.

### How to Run
1. Install Python.
2. Install the required packages using `pip install -r requirements.txt`.
3. Open `CSET485_Assignment.ipynb` in VS Code or Jupyter Notebook.
4. Run the cells from top to bottom.

An internet connection is required to retrieve the dataset from the UCI repository.

### Key Findings
The analysis compares OLS and Logistic Regression predictions, examines the effects of subgroup differences and omitted variables, and evaluates fairness metrics across decision thresholds. The results highlight that overall predictive performance alone does not fully describe model reliability or fairness.

### Conclusion
This project demonstrates the importance of testing predictive models beyond overall performance metrics. Model disagreement, subgroup behaviour, high-confidence errors, and fairness trade-offs should all be considered before a model is used to support consequential decisions.

---
**Course:** CSET485 — AI and Society  
**Assignment:** Assignment 1
