# NYC-MTA-Subway-Crowd-and-Delay-Analysis

Getting Started 

Link to the dataset - https://data.ny.gov/Transportation/MTA-Subway-Turnstile-Usage-Data-2022/k7j9-jnct/about_data
The other two datasets are in the github repo

# MTA Subway Analysis and Prediction

# MTA Subway Analysis and Crowd Prediction

This repository contains two Jupyter Notebooks, `MTA_subway.ipynb` and `CrowdPredict.ipynb`, that collectively focus on analyzing subway data, modeling patterns, and predicting crowd sizes using machine learning.

---

## Project Structure

### 1. **`MTA_subway.ipynb`**
   - Focuses on **subway data preprocessing**, **feature engineering**, and **model training**.
   - **Machine Learning Models**:
     - Implements various regression and classification models, including:
       - Logistic Regression
       - Random Forest Regressor and Classifier
       - Decision Tree
       - K-Nearest Neighbors
   - **Evaluation Metrics**:
     - Mean Squared Error (MSE)
     - Mean Absolute Error (MAE)
     - R-squared score (R²)
   - **Visualization**:
     - Provides insights using scatter plots and other graphical tools.

### 2. **`CrowdPredict.ipynb`**
   - Focuses on predicting subway crowd sizes.
   - **Key Features**:
     - Data preprocessing and feature selection.
     - Regression modeling to predict crowd sizes.
   - **Insights**:
     - Provides visualizations comparing actual versus predicted crowd sizes.
     - Highlights the model's performance, particularly its effectiveness for smaller crowds.
   - **Hyperparameter Tuning**:
     - Despite expectations, no evidence of `GridSearchCV` or explicit hyperparameter tuning was found in this notebook.

### 3. **Tableau Integration**
   - After generating predictions and processing data in the notebooks, **upload the processed data into Tableau** to create interactive visualizations and dashboards.
   - Tableau will be used to:
     - Visualize trends and patterns in subway crowd data.
     - Generate detailed, user-friendly graphs for further analysis.

---

## Dependencies

- Python 3.x
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
- Tableau (for visualization)

---

## How to Use

1. Clone the repository:
   ```bash
   git clone <repository-url>

##Install dependency 
pip install -r requirements.txt

Run the Jupyter Notebook:
jupyter notebook NYC_MTA_delay.ipynb
jupyter notebook CrowdPredict.ipynb

Project Structure
	•	Code Cells: Contain the logic for preprocessing, modeling, and evaluation.
	•	Markdown Cells: Explain the purpose and approach for each section.

Future Improvements
	•	Integration of additional models for better prediction accuracy.
	•	Visualization enhancements for more intuitive insights.

## AUTHORS
 JASMITHA, PRAAGNA, YASHAS
