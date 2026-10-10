# Phishing URL Detection Using Machine Learning

A university machine learning project that explores the classification of URLs as phishing or legitimate. Several machine learning algorithms were evaluated, and the Random Forest model was selected as the best-performing model in this project.

## Project Overview

Phishing websites often use deceptive URLs to trick users into revealing sensitive information. This project applies machine learning techniques to URL-related data to classify URLs into phishing and legitimate categories.

## Models Evaluated

The notebook evaluates multiple classification approaches, including:

- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Logistic Regression
- Decision Tree

The Random Forest model was selected based on the evaluation carried out in the project. See the notebook for the experiments and results.

## Repository Contents

- `group_pipeline.ipynb` — notebook containing the project workflow, model training, and evaluation.
- `best_random_forest_model.pkl` — saved Random Forest model.

1. Clone the repository:

   ```bash
   git clone https://github.com/Kalsara25/AI-ML-Model-Training-Y2S1-.git
   cd AI-ML-Model-Training-Y2S1-
   
2. Install the packages required by the notebook. For example:
    
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter

3. Start Jupyter Notebook:

   ```bash
   jupyter notebook group\_pipeline.ipynb

4. If the dataset is not included, obtain it from the source permitted for this project and update the dataset path in the notebook.

## Limitations

This is an academic project. Its results depend on the dataset, features, preprocessing, and evaluation method used. It should not be treated as a guaranteed phishing protection system.   

