# HandsOnML
A series of Jupyter Notebooks containing my code and solutions to the exercises in the third edition of the O'Reilly book Hands-on Machine Learning with Scikit-Learn, Keras and TensorFlow (3rd edition):

### Chapter 2 - End to end machine learning project
House prices prediction using California housing dataset. Firstly , I inspected and visualised data using matplotlib, then did stratified sampling based on income category. Secondly, I combined attributes to make more useful features, imputed missing values using SimpleImputer, and encoded categorical variables using OneHotEncoder. Thirdly, I scaled the attributes using StandardScaler, and built a custom transformer to cluster houses based on location using K-means. Fourthly, I created a pipeline to chain together preprocessing and model training, then performed cross-validation to obtain the accuracy results. Fifthly, I implemented hyperparameter tuning using GridSearchCV. Last but not least, I used joblib to save and load my model. 

### Chapter 3 - MNIST Digit Classification
Multiclass classification of digits 0-9 using the MNIST dataset, which contains 70000 images. Implemented K-Nearest-Neighbors algorithm with data augmentation. Used Obtained a 97.1% accuracy on the Kaggle knowledge contest. 

### Chapter 4 - Training Linear Models
Learnt about the Normal Equation used to find the optimal parameter vector that minimizes the MSE cost function. Also learnt about Batch, Stochastic and Mini-batch Gradient Descent. Then, moved on to l1 and l2 regularization, such as Ridge, Lasso and ElasticNetRegression. As an end of chapter exercise, I wrote a softmax regression model utilising batch gradient descent with early stopping and l2 regularization, **without using Scikit-Learn, only NumPy**. I proceeded to use the model on a multiclass classification task on the iris dataset. 
