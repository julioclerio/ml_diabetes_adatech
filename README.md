# Diabetes Detection Prediction

## Dataset Description

This dataset originates from the National Institute of Diabetes and Digestive and Kidney Diseases. The study and analysis of this data hold paramount importance, given the rising prevalence of diabetes as one of the most common chronic diseases globally. Early diagnosis of diabetes can lead to more effective treatments and better outcomes for patients.

The purpose of this dataset is to provide a means to predictively diagnose diabetes in patients based on specific diagnostic measurements. A unique aspect of this dataset is its focus on female patients over the age of 21 with Pima Indian heritage.

Contained within are:

A detailed dataset, originally sourced from Kaggle, with specific diagnostic measurements that serve as potential predictors for diabetes.
Notebooks that encompass data exploration, visualization, and modeling, guiding users through the entire data science pipeline.
Multiple machine learning models, ranging from decision trees to logistic regression, each offering unique insights and predictions on the data.
This repository not only serves as a platform for predictive modeling but also underscores the importance of early diabetes detection and the value of data-driven decision-making in healthcare.

**Link to the dataset on Kaggle:** [Predict Diabetes Dataset](https://www.kaggle.com/datasets/whenamancodes/predict-diabities)

### Data Dictionary and Insights

| Column                      | Description                                        | Insights |
|-----------------------------|----------------------------------------------------|----------|
| Pregnancies                 | Number of times pregnant                           | The number of pregnancies can influence diabetes risk. |
| Glucose                     | Plasma glucose concentration                       | Elevated glucose levels are a direct indicator of diabetes. |
| BloodPressure               | Diastolic blood pressure                           | Blood pressure can hint at circulatory issues common in diabetics. |
| SkinThickness               | Triceps skin fold thickness                        | Changes in skin thickness can be an indication of metabolic issues. |
| Insulin                     | 2-Hour serum insulin                               | Insulin is crucial in glucose metabolism. Abnormal levels can hint at diabetes. |
| BMI                         | Body mass index                                    | A high BMI is a risk factor for type 2 diabetes. |
| DiabetesPedigreeFunction    | Diabetes pedigree function                          | A function that provides a probability based on family history. |
| Age                         | Age in years                                       | Age is a risk factor, with type 2 diabetes becoming more common as people get older. |
| Outcome                     | Class variable (1 indicates "Yes" and 0 indicates "No") | The final classification based on the other variables. |

## Repository Structure

- `dataset/`: Folder containing the dataset in CSV format. Intended for those keen on working directly with the raw data or conducting their own analysis.
- `notebooks/`: Folder housing a detailed notebook for data treatment, visualization, and the entire machine learning modeling process. A step-by-step guide to understanding the project flow.

## Project Steps

1. **Introduction/Context:** An overview of the problem, emphasizing the significance of early diagnosis and this project's contribution in that context.
2. **Exploratory Data Analysis:** A deep dive into the data, understanding each variable, their inter-relationships, and preparing them for modeling.
3. **Modeling:** A detailed breakdown of the entire model-building process, from training to validation and optimization.

### Machine Learning Models Employed

Each model offers unique characteristics and insights into the data:

- **RandomForestClassifier:** A combination of decision trees aiming to enhance accuracy and prevent overfitting.
- **Decision Tree:** A graphical representation of potential solutions to a decision-based problem.
- **LogisticRegression:** Suited for binary classification, it attempts to predict the probability of an instance belonging to a particular category.
- **KNN (K-Nearest Neighbors):** Classifies based on the majority class of its 'k' nearest neighbors, useful for spotting non-linear patterns.

## Contributions

Diabetes is a global challenge, and research in this area is vital. This project is a collaborative endeavor, and the community is encouraged to contribute. Whether it's by cloning, modifying, or submitting pull requests, your input is highly valued!


## Conclusion:

When addressing the intricate task of predictively diagnosing diabetes, a variety of Machine Learning models were put to the test. Each of these models, with their unique characteristics, tried to capture the underlying patterns in the data sourced from the National Institute of Diabetes and Digestive and Kidney Diseases.

- **Random Forest:** This model stood out as the top performer, boasting an impressive ROC score of 0.92 and an accuracy of 0.85. Random Forest, which constructs multiple decision trees and combines their predictions, showcased robustness and high discriminative capacity on the given data.

- **Logistic Regression:** With an ROC score of 0.90 and accuracy of 0.82, Logistic Regression, which estimates the probability of an instance belonging to a particular class, also displayed solid performance, albeit slightly trailing behind Random Forest.

- **KNN:** This instance-based method, predicting based on the proximity of new points to training points, achieved an ROC score of 0.86 and accuracy of 0.79. While still commendable, its performance was outpaced by the preceding models.

- **Decision Tree:** The decision tree, predicting based on a series of decisions about the data's features, had the most modest performance, with an ROC score of 0.82 and accuracy of 0.71. This suggests that for this specific dataset, the decision tree might not be the ideal model.

In summary, the Random Forest model emerged as the most promising for the predictive diagnosis of diabetes in this particular context, with Logistic Regression not far behind. Choosing the ideal model, however, should also take into account other factors such as interpretability, training speed, tunability, and integration with other systems. Regardless of the chosen model, it is crucial that predictions are used in conjunction with clinical expertise to ensure accurate diagnoses and quality care for patients.



## Meet the Team Behind This Project

Cláudio Gomes
Clerio Fernandes
Iris Pires
Victor Alexander



