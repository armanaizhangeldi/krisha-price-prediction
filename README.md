# Krisha.kz Real Estate Price Prediction

This project implements a machine learning pipeline to predict property prices in Kazakhstan using data from Krisha.kz. It encompasses data preprocessing, housing feature engineering, exploratory data analysis, and regression modeling to estimate property values.

## Core Workflow

1. Data Cleaning: Handling missing structural values, parsing text attributes, and removing duplicate entries.
2. Feature Engineering: Processing key housing variables including location metrics, total area, room counts, and building materials.
3. Exploratory Data Analysis: Visualizing price distributions across regions and computing correlation matrices for housing attributes.
4. Model Training and Evaluation: Splitting data into training and validation sets, scaling numerical features, and training regression models.

## Deployment and Execution

1. Clone the repository to your local environment.
2. Install the necessary packages:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```
3. Launch the Jupyter Notebook environment:
   ```bash
   jupyter notebook
   ```
4. Execute the cells sequentially to reproduce the data pipeline and model outputs.
