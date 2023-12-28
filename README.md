# HandsOnML
A series of Jupyter Notebooks containing my code and solutions to the exercises in the third edition of the O'Reilly book Hands-on Machine Learning with Scikit-Learn, Keras and TensorFlow (3rd edition):

### Chapter 2 - End to end machine learning project
House prices prediction using California housing dataset. \
Implementation: `matplotlib` for data inspection and visualisation; **Stratified sampling** based on income category; **Combine attributes** to make more useful features; Fill in missing values using `SimpleImputer`; Encode categorical variables using `OneHotEncoder`; Scale the attributes using `StandardScaler`; Build a custom transformer to cluster houses based on location using **K-means**; Create a **pipeline** to chain together preprocessing and model training; Perform **cross-validation** to obtain the accuracy results; Utilised **hyperparameter tuning** using `GridSearchCV`; Save and load my model using `joblib`. 

### Chapter 3 - MNIST Digit Classification
Multiclass classification of digits 0-9 using the MNIST dataset, which contains 70000 images. Implemented K-Nearest-Neighbors algorithm with data augmentation. Used Obtained a 97.1% accuracy on the Kaggle knowledge contest. 

### Chapter 4 - Training Linear Models
Topics:
1. The Normal Equation used to find the optimal parameter vector that minimizes the MSE cost function
2. Batch, Stochastic and Mini-batch Gradient Descent
3. $l_1$ and $l_2$ regularization, such as Ridge, Lasso and ElasticNetRegression.
4. As an end of chapter exercise, I wrote a softmax regression model utilising batch gradient descent with early stopping and l2 regularization, **without using Scikit-Learn, only NumPy**. I proceeded to use the model on a multiclass classification task on the iris dataset. 
