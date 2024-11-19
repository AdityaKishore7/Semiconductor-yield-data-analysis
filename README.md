# Predictive Modeling for Semiconductor Yield Enhancement

## Overview

This project aims to develop a machine learning model that can predict the pass/fail yield of a semiconductor manufacturing process. By analyzing sensor data collected during the manufacturing process, the model identifies key features (sensors) contributing to yield excursions. This information enables process engineers to take corrective actions to improve the yield and reduce production costs.

## Methodology

1. **Data Acquisition and Preprocessing:**
   - Utilized the UCI-SEMCOM dataset from Kaggle.
   - Handled missing values and removed highly collinear features.
   - Standardized the data using StandardScaler.
2. **Model Selection and Training:**
   - Evaluated various classification algorithms: Logistic Regression, Random Forest, and XGBoost.
   - Implemented sampling techniques (SMOTE and undersampling) to address imbalanced classes.
   - Applied Grid Search to optimize model hyperparameters.
3. **Evaluation and Feature Importance:**
   - Assessed model performance using accuracy and recall metrics.
   - Identified key sensor features contributing significantly to yield excursions.
4. **Dimensionality Reduction (Optional):**
   - Applied PCA to reduce the dataset's dimensionality.
   - Evaluated model performance with the reduced dataset.
5. **Outlier Detection (Optional):**
   - Explored outlier detection techniques: Elliptic Envelope, Isolation Forest, and Local Outlier Factor.
   - Assessed their effectiveness in identifying defective semiconductors.

## Results

- Achieved a recall rate of 88% using Local Outlier Factor algorithm.
- Identified key sensor features that provide insights for process improvement.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- XGBoost
- Imbalanced-learn

## Conclusion

This project demonstrates the potential of machine learning in enhancing semiconductor yield prediction. The insights gained from the model can be used by process engineers to optimize manufacturing processes and reduce production costs.

## Future Work

- Explore more advanced machine learning algorithms.
- Investigate alternative sampling and dimensionality reduction techniques.
- Develop a user-friendly interface for process engineers to interact with the model.
