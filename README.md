# NLP

Performed sentiment Analysis on Amazon Data Science Book Reviews.
This dataset contains 20647 amazon reviews for 836 data-science related books. Every review consists of review text and score (number of stars from 1 to 5).
Used pre-processing techniques like Word NetLemmatizer, Porter Stemmer to pre-processed the reviews.
Handled class imbalance in data using SMOTE technique.
Text vectorization is done using TF-IDF and Word 2Vec techniques.
Model training is performed using Guassian Naive Bayes, Decision Tree, Random Forest Classifiers, XG-Boost Classifiers and Logistice Regression.
Hyperparameter tuning is done for each technique using Grid Search CV.
Analysed the performance of each model using Confusion Matrix and ROC Curve.
Later compared the performance of all the models using AUC and F1 Score.
Key Observations:
Logistic Regression and XG-Boost performed well on training and testing data. Both these models generated more number of true positives as well as true negatives as compared to other models.
Decision Tree and Random Forest models were able to classify true positives but could not perform well while classifying true negatives.

