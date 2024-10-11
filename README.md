# Laptop Price Prediction

This project predicts laptop prices based on various technical specifications such as RAM, CPU, screen size, and more. The focus of the project is on thorough data preprocessing, feature engineering, and building machine learning models to accurately predict laptop prices.
Project Overview

This project covers:

    Data Preprocessing:
        Applied outlier removal to the target feature (Price in Euros) as well as the features with the highest correlation to the target feature.
        Adjusted the distribution of the target feature and all other right- or left-skewed features to make them normally distributed.
        Standardized all features for optimal model performance.

    Exploratory Data Analysis (EDA): Performed data visualization to uncover patterns and relationships between features.

    Feature Engineering: Created new features, including screen area, price per inch, etc.

    Modeling: Built and evaluated multiple machine learning models, including Linear Regression, Decision Trees, Random Forest, SVR, Bagging, Boosting, and Neural Networks.

    Model Evaluation: Linear Regression achieved the highest R² score among all models.

Key Steps
1. Data Preprocessing

    Outlier Removal: Removed outliers from the target feature and the features with the highest correlation to the target.
    Distribution Adjustment: Log transformations and other adjustments were applied to ensure that the target feature and skewed features were normally distributed.
    Standardization: Standardized all features to improve model training.

2. Exploratory Data Analysis (EDA)

    Used data visualization techniques such as histograms, scatter plots, and box plots to understand feature distributions and relationships.

3. Feature Engineering

    Extracted new features like Screen_Area, Price_per_Inch, and Price_per_RAM.
    Converted categorical variables into meaningful numerical representations.

4. Model Building and Evaluation

    Trained and evaluated multiple machine learning models including Linear Regression, Support Vector Regression (SVR), Decision Tree, Random Forest, Bagging, Boosting, and Neural Networks.
    Linear Regression performed the best, achieving the highest R² score.

5. Cross-Validation and Hyperparameter Tuning

    Used cross-validation to evaluate model performance and applied hyperparameter tuning to models like SVR to further optimize their performance.

Results

    Highest R² Score: Achieved with Linear Regression.
    Cross-Validation: Ensured robust model performance across different data splits.
