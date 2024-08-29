# Drug Side Effects Prediction Using Machine Learning and NLP
### This repository is a complete end to predicting drug side effects based on patient reviews using advanced Natural language Processing (NLP) and machine learning models. We intend to share insights that may help healthcare providers know what their patients might choose, while also helping patients and pharmaceutical companies make more informed decisions.
## Table of Contents
### 1.	Overview
### 2.	Features
### 3.	Dataset
### 4.	Installation
### 5.	Usage
### 6.	Models Implemented
### 7.	Results
### 8.	Future Enhancements
### 9.	Contributing
### 10.	License
## Overview
### Recent developments in information technology such as patient-generated content such as drug reviews provide insights into the actual effectiveness and adverse effects of medications that have been used on real-world patients. This project uses machine learning and NLP methods to predict drug side effects from unstructured reviews by patients in an attempt to improve risk-benefit monitoring of drugs.
## Features
### •	NLP-Based Preprocessing: Includes text normalization, tokenization, stopword removal, and TF-IDF vectorization.
### •	Sentiment Analysis: Extracts sentiment scores from reviews to identify the underlying tone (positive, negative, neutral).
### •	Machine Learning Models: Implements and compares Random Forest, XGBoost, and Support Vector Machine (SVM) for classification tasks.
### •	Comprehensive Evaluation: Provides detailed metrics and visualizations to assess model performance.
### •	Scalable Codebase: Modular and well-documented code to facilitate further development and integration.
## Dataset
### Data for this study was extracted from Druglib.com, containing 4143 patient-reported outcomes of drugs. They're packed with details on the name of the drug, condition treated, benefits experienced by patients, side effects they encountered, and their overall rating.
## Dataset Fields:
### •	reviewID: Unique identifier for each review.
### •	urlDrugName: The drug being reviewed.
### •	Condition: The medical condition the drug is intended to treat.
### •	BenefitsReview: Patient's description of the benefits experienced.
### •	SideEffectsReview: Patient's description of side effects encountered.
### •	CommentsReview: General comments about the drug.
### •	rating: Patient's overall satisfaction rating (1 to 10).
### •	sideEffects: Categorical rating of side effects severity.
### •	effectiveness: Categorical rating of the drug's effectiveness.
## Installation
### To begin with this project, use the following steps:
### 1.	Clone the repository from GitHub to your local machine,
### 2.	It will install some requirements from the provided requirements file.
### 3.	Download the dataset files and place them in the appropriate directory within your project structure.
## Usage
### 1.	Start by preprocessing the data. This involves cleaning and normalizing the text data, ensuring it is ready for analysis.
### 2.	Once the data is preprocessed, proceed to train the machine learning models using the cleaned data.
### 3.	Evaluate the trained models on the test dataset to generate performance metrics and insights.
### 4.	Utilize the provided visualizations to better understand the distribution of side effects and the effectiveness of each model.
## Models Implemented
### •	Random Forest Classifier: An ensemble learning method that improves prediction accuracy by combining multiple decision trees.
### •	XGBoost Classifier: An optimized gradient boosting framework that is highly efficient and flexible.
### •	Support Vector Machine (SVM): A powerful classifier that works well in high-dimensional spaces.
### Each model has been tuned for optimal performance using hyperparameter tuning techniques to achieve the best results.
## Results
### The models were evaluated based on their accuracy and ability to classify drug side effects:
### •	Random Forest:
### o	Achieved moderate accuracy in multi-class classification and performed well in binary classification.
## •	XGBoost:
### o	Outperformed the other models, particularly in binary classification, showing robustness and effectiveness.
## •	SVM:
### o	Struggled with multi-class classification but showed reasonable performance in binary scenarios.
### Key insights from the project include the superior performance of XGBoost in both multi-class and binary classification tasks, while Random Forest showed imbalances, and SVM faced challenges with the complexity of the data.
## Future Enhancements
### •	Contextual Embeddings: Implement more advanced text embeddings like BERT or GPT to capture richer context.
### •	Aspect-Based Sentiment Analysis: Analyze sentiments related to specific drug aspects such as side effects and benefits.
### •	Synthetic Data Generation: Generate artificial data to improve model training, especially for underrepresented classes.
### •	Integration with Additional Data Sources: Enrich the dataset by combining reviews from multiple platforms.
## Contributing
### Contributions are welcome! Whether you want to report issues, suggest improvements, or submit new features, your input is valuable. Please follow the standard GitHub workflow for contributions.
## License
### This project is licensed under the MIT License. Please refer to the LICENSE file for more information.


