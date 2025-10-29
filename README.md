# ML_Time_Series

# Time series analysis

1. Define the problem: Is it a classification or regression problem? What are the inputs and outputs? What are the steps involved in solving the problem?
2. Data Exploration: This step involves visualizing the data to understand the trends and patterns. This helps in developing the intuition for building the machine learning model.
3. Preprocess the data: This step involves cleaning the data, dealing with missing values, and transforming the data so that it can be used by the machine learning algorithm. This step is crucial and includes feature engineering, scaling, normalization.
4. Decompose the time series: This step is useful in understanding the trend, seasonality, and noise in the data. This step is necessary for certain kinds of methods, but not with others.
5. Build models: Once the data is preprocessed, you can build models using traditional machine learning algorithms or time series specific algorithms.
6. Evaluate the models: This step includes comparing the performance of different models and choosing the best one. It involves assessing the performance of the machine learning model on unseen data. This helps in fine-tuning the model and making it ready for deployment.
7. Make predictions: This step involves using the final model to make predictions on new data.

* Use the header option to tell read_csv() which row is the header  ``` df = read_csv("data.csv", header=0) ```
* use the index_col option to tell read_csv() which column to use as the index. The index is a special column that contains the labels for the rows
``` df = read_csv("data.csv", index_col="date")
df.head(4) ```

