# Venture Funding with Deep Learning
This model that predicts whether applicants will be successful if funded by Alphabet Soup.

Read the applicants_data.csv file into a Pandas DataFrame. Review the DataFrame, create a DataFrame with categorical variables and encoded, as well as columns that could eventually define your features and target variables.

Drop the columns from the DataFrame, which are  not relevant to the binary classification model.

Encode the dataset’s categorical variables using OneHotEncoder, and then place the encoded variables into a new DataFrame.

Add the original DataFrame’s numerical variables to the DataFrame containing the encoded variables.

using Pandas concat() function that inner join the DataFrame.

Using the preprocessed data, create the features (X) and target (y) datasets. The target dataset should be defined by the preprocessed DataFrame column “IS_SUCCESSFUL”. The remaining columns should define the features dataset.

Split the features and target sets into training and testing datasets.

Use scikit-learn's StandardScaler to scale the features data.

# Compile and evaluate a binary classification model using a neural network.

Create a deep neural network by  number of input features, the number of layers, and the number of neurons on each layer using Tensorflow’s Keras.

Compile and fit the model using the binary_crossentropy loss function, the adam optimizer, and the accuracy evaluation metric.


# Evaluate the model using the test data to determine the model’s loss and accuracy.

