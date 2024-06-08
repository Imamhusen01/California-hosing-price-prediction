# California-hosing-price-prediction
Data Preprocessing

In the notebooks/Data_Preprocessing.ipynb notebook and src/preprocess.py script, we preprocess the California housing dataset using Pandas. The preprocessing steps include handling missing values, feature scaling, and splitting the data into training and testing sets.
Data Visualization

In the notebooks/Data_Visualization.ipynb notebook and src/visualize.py script, we visualize the California housing dataset using Seaborn and Matplotlib. We create various plots such as histograms, scatter plots, and correlation matrices to explore the relationships between different features and the target variable.
Model Training

In the notebooks/Model_Training.ipynb notebook and src/train_model.py script, we train a machine learning model using Scikit-learn. We use linear regression to build a predictive model for housing prices based on the preprocessed dataset.
Serialized Model

The trained regression model is serialized and saved as models/regression_model.pkl using the pickle module in Python.
Plots

The generated plots, including the correlation matrix plot, scatter plot of housing prices, and residual plot of predictions, are saved in the plots/ directory.
