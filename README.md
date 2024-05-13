# Biometric Identification based on eye Movements using Machine learning and Deep Learning : README

Security is paramount for safeguarding valuable information from unauthorized access. In today's technologically driven world, maintaining robust security measures is crucial to prevent unauthorized individuals from gaining access to sensitive data. Biometric systems play a significant role in ensuring security by identifying individuals based on their unique physical or behavioral traits.

## Introduction
This repository focuses on exploring eye movement biometrics as a reliable and secure identification method. Eye movements offer strong protection against fraud and counterfeiting due to their uniqueness and difficulty to replicate accurately. However, research in this area is still in its early stages, presenting opportunities for further investigation and innovation.

## Objectives
The primary objectives of this project are as follows:

1. **Dataset Utilization**: Utilize a large binocular dataset to train classifiers effectively for eye movement biometrics.
   
2. **Model Implementation**: Implement various machine learning (ML) models to classify individuals based on their eye movements.
   
3. **Performance Evaluation**: Evaluate the performance of ML models and enhance transparency using SHAP (SHapley Additive exPlanations).

## Methodology
### Data Preprocessing
The dataset undergoes thorough preprocessing to ensure data integrity and comparability across features. This includes:

- **Null Value Handling**: Elimination of null values to maintain data integrity.
   
- **Normalization**: Standard normalization techniques are applied to ensure uniformity and comparability across features.
   
- **Feature Selection**: Irrelevant features are discarded to enhance the quality of subsequent analysis.

### Feature Transformation
Principal Component Analysis (PCA) is employed to simplify the dataset while retaining essential information. This involves:

- **Correlation Analysis**: A correlation matrix heatmap is generated to identify relationships between variables, facilitating the selection of valuable features for model training.
   
- **Dimensionality Reduction**: PCA selects the most valuable features, reducing the dataset size while maintaining most of its essential aspects.

### ML/DL Modelling
Various ML and deep learning (DL) classification algorithms are utilized to train models using the simplified feature set derived from PCA. These include:

- **Random Forest**
- **Gradient Boost**
- **Decision Tree**
- **XGBoost**
- **KNN**
- **Multi-Layer Perceptron**
- **Convolutional Neural Network**

### Model Selection
Models are evaluated based on a range of performance metrics, including accuracy, F1 score, recall, precision, and specificity. The top-performing models are selected for further analysis, ensuring effective classification for eye movement biometrics.

## Usage
To replicate the experiment or apply the models to new data, follow the steps outlined in the project's documentation. The provided codebase includes scripts for data preprocessing, feature transformation, model training, and evaluation.

## Conclusion
This project contributes to the advancement of eye movement biometrics research by leveraging machine learning techniques and explainable AI. By enhancing transparency and performance metrics, the proposed methodology offers insights to improve security and reliability in identification systems.

## Future Directions
Potential research directions include expanding the dataset, exploring advanced machine learning algorithms, and investigating real-world applications of eye movement biometrics beyond traditional security contexts.

For detailed documentation and code implementation, refer to the project repository.
