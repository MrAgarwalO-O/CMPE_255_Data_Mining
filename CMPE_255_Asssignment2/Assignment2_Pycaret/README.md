
In this part of the assignment, I have used Pycaret library, which is an open-source, low-code machine learning library in Python. Also I have recorded 2 videos which demonstrate tasks using gradio (videos can be found under Pycaret_with_gradio folder)
Using this, I have performed various types of tasks including:
* Binary Classification
* Multiclass Classification
* Regression
* Clustering
* Anomaly Detection
* Time Series Forecasting Univariate without Exogenous Variables
* Time Series Forecasting Univariate with Exogenous Variables

### Datasets Used:
**Binary Classification:** spam.csv<br>
**Multiclass Classification:** car_evaluation.csv<br>
**Regression:** Diamonds Prices2022.csv<br>
**Clustering:** movies.csv<br>
**Time Series Forecasting (Univariate without Exogenous Variables):** synthetic_stock_price_data.csv<br>
**Time Series Forecasting (Univariate with Exogenous Variables):** simulated_sales_data.csv

### Analysis Conducted:
#### Data Preprocessing
- Date columns were prepared and set as the index where applicable, and data columns were renamed as needed.
- PyCaret's setup method handled any further preprocessing tasks automatically.

#### Modeling and Evaluation
* The compare_models function in PyCaret was used to compare various algorithms.
* The best models were found and fine-tuned using functions such as tune_model and create_model.
* Models were evaluated with PyCaret's evaluate_model function, which takes into account measures like accuracy, precision, recall, MAE, MSE etc.

#### Prediction
- Different models including auto ARIMA were utilized for time series forecasting.

All the code can be found in the notebooks uploaded, you can refer that. Additionally I have uploaded all the datasets as well.

### References
https://pycaret.gitbook.io/docs/learn-pycaret/videos<br>
https://pycaret.gitbook.io/docs/get-started/tutorials<br>
https://pycaret.gitbook.io/docs/get-started/tutorials<br>
https://github.com/pycaret/examples<br>
https://www.youtube.com/watch?v=4JyYhbW6eCA<br>
https://github.com/pycaret/pycaret<br>
https://github.com/pycaret/pycaret/tree/master/examples<br>
https://pycaret.gitbook.io/docs/learn-pycaret/official-blog<br>

