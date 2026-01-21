# Salary Prediction Dataset & Analysis
This project explores a dataset of salaries to identify key factors that influence compensation, such as job title, employment type, and company location. The goal is to clean, analyze, and prepare this data for machine learning models.
## 📊 Project Overview
The primary goal is to predict salaries based on professional and geographic features. By filtering for consistent variables (like currency and employment type), the model aims to provide accurate insights into market compensation trends.
## 🛠️ Data Cleaning & Preprocessing
The dataset underwent several cleaning steps using `pandas` and `numpy`:

* **Employment Type Filter:** Limited to Full-Time (`FT`) roles to standardize work hours.
* **Currency Standardization:** Filtered for `USD` to avoid exchange rate volatility in modeling.
* **Job Title Refinement:** Grouped infrequent job titles into an `Other` category to reduce noise and improve model generalization.
* **Location Mapping:** Categorized company locations into `US` vs `Other`.
* **Feature Encoding:** Applied One-Hot Encoding to categorical variables for compatibility with Scikit-Learn.

## 💻 Technical Stack
* **Language:** [Python](https://www.python.org/)
* **Libraries:** [Pandas](https://pandas.pydata.org/), [NumPy](https://numpy.org/), [Scikit-Learn](https://scikit-learn.org/)
* **Environment:** VS Code / Jupyter Notebooks
