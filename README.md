We predict students' final grade from their gender, weekly commitment, attendance rate, previous exam scores, parental education level, internet access, presence of extracurricular activities using a Linear Regression model. You can find the dataset here:

https://www.kaggle.com/datasets/amrmaree/student-performance-prediction

Our model is decent (MAE and RMSE are about 3 or 4 while predicting grades in the interval 50-70). However, it badly predicts 50. The reason may be the fact that the grade system was not properly presented by the author of the dataset (50 is probably the minimal possible grade, but our model can predict as low as 45). The dataset had no missing values and no outliers which is a good sign.
