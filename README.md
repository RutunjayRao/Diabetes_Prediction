# Diabetes_Prediction

Diabetes, a chronic health condition, affects the body's ability to process food into energy. The process involves breaking down food into sugar and releasing it into the bloodstream, regulated by insulin. In diabetes, the body either lacks sufficient insulin production or becomes resistant to its effects, leading to elevated blood sugar levels and potential health complications. The three main types of diabetes are type 1, type 2, and gestational diabetes, each with distinct characteristics.

What is Pima Indian Diabetes?
Pima Indian diabetes, prevalent among the Pima Native American population in Arizona, is characterized by a remarkably high incidence of type 2 diabetes. Its study offers unique insights into genetic and environmental factors contributing to the disease, with broader implications for diabetes research and healthcare. Understanding this condition can aid in developing effective healthcare practices and prevention strategies, making it a critical focus of medical investigation.

Pima Indians Diabetes Dataset aims to predict diabetes onset using diagnostic measures. The dataset, sourced from the National Institute of Diabetes and Digestive and Kidney Diseases, focuses on female patients aged 21 or older with Pima Indian heritage. Its objective is to diagnostically predict diabetes presence based on specific diagnostic measurements carefully selected from a larger database.

Attribute Information:

  1. Number of times pregnant
  2. Plasma glucose concentration
  3. Diastolic blood pressure (mm Hg)
  4. Triceps skin fold thickness (mm)
  5. 2-Hour serum insulin (mu U/ml)
  6. BMI (weight in kg/(height in m)^2)
  7. Diabetes pedigree function
  8. Age (years)
  9. Class variable (0 means non-diabetic or 1 means diabetic)

We will first clean up and process outliers using the IQR method. Then, we will do EDA on the dataset and find correlations between different attributes. Finally, we will apply different classifier models and see which suits best according to our ROC curve's AUC(area under curve). Then, we will do hyperparameter tuning on four basic classification models (LogR, KNN, SVC, Decision Tree) and see if it gives better results than previously used complex models.

The dataset csv is added here as well.
