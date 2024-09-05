# Forecasting Gold Prices with Machine Learning

## 🌐 About
In a personal project focused on time series and forecasting, I researched and applied various quantitative methods to predict gold prices.

## 🎯 Goal
The goal of this project was to forecast future gold prices using historical data. I applied various quantitative methods, including moving averages and machine learning models, to predict gold prices based on the dataset. 

## 🚀 Objectives
1. **Exploring and Preprocessing Data**: Analyze and prepare the data for the training and testing phases. The data is split 80% for training and 20% for testing.
2. **Model Building**: Use regression models like Lasso, Random Forest, and XGBoost. The best accuracy will be selected.
3. **Prediction and Analysis**: The model is used to predict gold prices on the test data (2017-2018). The predicted results are then compared with the actual data to evaluate the model's performance.

## 📊 Dataset
The dataset on Kaggle [here](https://www.kaggle.com/datasets/sahilmandavkar/gold-price-data/data).

## 🛠️ Tools and Libraries Used
1. Python
2. Google Collaboratory
3. Numpy
4. Pandas
5. Seaborn
6. Matplotlib
7. Scikit-learn
8. XGBoost
9. Warning
10. ELI5
11. Pickle

## 📈 Results
The results of the three models were compared based on their R-squared scores. The XGBoost model performed the best with an accuracy of 99,85% on the training data and 97,51% on the test data. 
<table>
  <thead>
    <tr>
      <th>Regression Model</th>
      <th>Train Accuracy</th>
      <th>Predict Accuracy</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Lasso</td>
      <td>86%</td>
      <td>86,17%</td>
     </tr>   
    </tbody>
   <tbody>
    <tr>
      <td>Random Forest</td>
      <td>95,38%</td>
      <td>95,68%</td>
     </tr>   
    </tbody>
  <tbody>
    <tr>
      <td>XGBoost</td>
      <td>99,85%</td>
      <td>97,51%</td>
     </tr>   
    </tbody>
</table> 


