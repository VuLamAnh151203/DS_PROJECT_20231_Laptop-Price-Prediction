# DS_PROJECT_20231
Our teams members:
  - Trịnh Hoàng Giang 20214893
  - Hồ Ngọc Ánh 20214877
  - Hoàng Thành Đạt 20214899
  - Lăng Văn Quý 20214928
  - Vũ Lâm Anh 20214876

In this project, we aim to build a laptop price prediction model from a reliable data set. From there, people who want to buy a laptop can make good decision.

General step in this project:
  1. We crawl data in Amazon Website by using scrapy library - folder laptopscraper
  2. We preprocess and detect outlier in the data - Data_Preprocessing and Detect Outlier.ipynb
  3. We make some EDA on data to see characteristic of data and do feature engineering(one-hot encoding) - EDA.ipynb
  4. We build various ML regression model to predict the price of laptop based on the characteristic of laptop (RAM, ROM, CPU,....) - ML model.ipynb
  5. We make a small GUI like a demo, you can input the the characteristic of laptop and it will the prediction price for that laptop - demo.ipynb

Here is our final results for each ML model on this datasets:
| Metrics        | R2 Score          | MAE  | MSE| RMSE|
| ------------- |:-------------:| -----:|-----:|-----:|
Ridge Regression | 0.816| 0.098 |0.018| 0.132
KNN |0.943 |0.023| 0.006 |0.044
Decision Tree |0.944 |0.024 |0.005 |0.04
Random Forest| 0.954 |0.041| 0.004| 0.06
MLP | 0.89 |0.07 |0.011| 0.102
Ensemble| 0.945 |0.048 |0.005| 0.069


   
