## Diabetes Prediction Project
Description
This project predicts whether a patient has diabetes using medical data from the Pima Indians Diabetes Dataset. It includes all steps of a typical machine learning workflow, from data preprocessing to model evaluation and visualization.
## Dataset
The dataset contains 768 entries and includes features such as number of pregnancies, glucose level, blood pressure, skin thickness, insulin level, BMI, diabetes pedigree function, age, and the outcome indicating diabetes presence.
## Data Preprocessing
The data was checked for missing values and duplicates. Since the dataset was imbalanced, Random Over Sampling was used to balance the classes. The data was then split into training and testing sets.
## Models Used
Four machine learning models were trained and evaluated:
Logistic Regression
Support Vector Classifier (SVC)
Random Forest Classifier
Gradient Boosting Classifier
## Evaluation Metrics
The models were evaluated using accuracy, recall, and F1-score. These metrics help assess the overall performance, the ability to detect diabetic patients, and the balance between precision and recall.
## Results
The Random Forest Classifier achieved the best performance with the highest accuracy, recall, and F1-score among all models. Gradient Boosting also performed well, while Logistic Regression and SVC had lower scores.
## Visualizations
The project includes visualizations such as a heatmap of feature correlations, count plots of the target variable, boxplots of age distribution, confusion matrices for each model, and a line plot comparing the performance of all models.
How to Run
Clone the repository, install the required Python packages, and run the Jupyter notebook or Python script to reproduce the results.
## Saving the Model
The trained best model can be saved using pickle to use it later for predictions without retraining.
