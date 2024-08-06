# Gender Prediction Using Dental Metrics

## Overview
This project aims to predict the gender of individuals using various dental metrics. The dataset includes measurements of different dental features, which are used to train and evaluate machine learning models. This application is particularly useful in forensic dentistry where identifying the gender of deceased individuals is important.

## Project Structure
- `Dentistry_Project.ipynb`: Jupyter Notebook containing the entire analysis, model building, and evaluation process.
- `Cleaned_Dentistry_Dataset.csv`: The cleaned dataset used for the analysis.
- `Dentistry Dataset.csv`: The original dataset.

## Steps
1. **Data Loading and Initial Inspection**:
   - Load the dataset and display the first few rows to understand its structure.
   
2. **Data Cleaning and Preprocessing**:
   - Handle missing values and remove unnecessary columns.
   - Encode categorical variables.

3. **Exploratory Data Analysis (EDA)**:
   - Visualize the data using histograms, scatter plots, and correlation heatmaps.

4. **Data Preprocessing**:
   - Split the data into independent (features) and dependent (target) variables.
   - Normalize the data and split it into training and test sets.

5. **Model Building and Training**:
   - Train different machine learning models (Logistic Regression, Decision Tree, Random Forest, XGBoost).
   - Evaluate the models using accuracy, confusion matrix, and ROC curve.

6. **Conclusion**:
   - Summarize the findings and performance of different models.

## Usage
To use this project, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name






### Additional Steps

1. **Create a `requirements.txt` File**:
   - List all the Python packages used in your project.
   - Example content for `requirements.txt`:
     ```
     pandas
     numpy
     scikit-learn
     matplotlib
     seaborn
     xgboost
     ```

2. **Push the Changes to GitHub**:
   - Ensure all your files (`Dentistry_Project.ipynb`, `Cleaned_Dentistry_Dataset.csv`, `Dentistry Dataset.csv`, `README.md`, and `requirements.txt`) are in the project folder.
   - Push the changes to your GitHub repository:
     ```bash
     git add .
     git commit -m "Add project files and README"
     git push origin master
     ```

By following this guide, you'll have a comprehensive README file that provides an overview of your project, instructions for use, and additional information that users or collaborators might find helpful. If you need any further customization or details, feel free to ask!
