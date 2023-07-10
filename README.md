# Person-identification-based-on-smartwatch-data-during-every-day-activities
WISDM Smartphone and Smartwatch Activity and Biometrics Dataset

This provides an overview of the WISDM Smartphone and Smartwatch Activity and Biometrics Dataset, focusing on the possibility of identifying a person by analyzing their smartwatch measurements during everyday activities. The dataset includes accelerometer and gyroscope sensor data collected from an LG G watch as 51 individuals performed 18 different daily activities.

To address the research question, supervised models were developed using the transformed accelerometer data. The data was divided into 10-second segments, and high-level features were extracted. The resulting dataset contained 18,211 observations with 94 features.

Different classification models were trained and evaluated using cross-validation techniques. The logistic regression model achieved an accuracy of 76.6% in the 80/20 cross-validation approach and 82% in the 10-fold cross-validation approach. Linear Discriminant Analysis (LDA) achieved an accuracy of 81.3%, while Quadratic Discriminant Analysis (QDA) performed even better with an accuracy of 88.3% in the 80/20 cross-validation approach and 91.7% in the 10-fold cross-validation approach. Naïve Bayes achieved lower accuracy at 73.4% and 77.5% in the two approaches, respectively. The K-Nearest Neighbors (KNN) algorithm performed the best, achieving an accuracy of 93% in the 80/20 cross-validation approach and 92.7% in the 10-fold cross-validation approach.

Regularization techniques, such as forward stepwise selection, Ridge regression, and Lasso regression, were implemented to improve model performance and feature selection. The results showed that Ridge and Lasso regression successfully reduced the number of features, providing more interpretable models.

The performance of the best model, QDA, was further evaluated using the ROC curve, achieving an Area Under the ROC Curve (AUC) of 0.95, indicating excellent performance. The model's accuracy was validated through cross-validation, with an accuracy of 92.86% in the 80/20 cross-validation approach and an average accuracy of 90.48% using K-fold cross-validation.

In conclusion, the study demonstrates that it is possible to identify a person by analyzing their smartwatch measurements during everyday activities with an accuracy of 92.86%. This has potential applications in various industries, allowing companies and organizations to recognize individuals based on their activity patterns and improve services tailored to their customers' needs.
