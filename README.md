Exploratory data analysis of Oxford's Parkinson Disease dataset. The steps involved are: <br>
1. Data preprocessing - removing unwanted columns, removing null and duplicate values
2. Data split for model training
3. Training the data on the following model variants using cross validation for better robustness:
   - Linear Regression with cross validation
   - Regression tree model with cross validation
   - Neural network model with cross validation
4. Performance comparison and determination of best model
5. Optimization of models using GridSearch CV
