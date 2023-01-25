# Deep-Learning-Neural-Network-Model
In this code, a machine learning model is created to predict the success of startups applying for funding from Alphabet Soup, a venture capital firm. The model is a binary classifier, which uses a dataset of over 34,000 organizations that have received funding from Alphabet Soup in the past. The dataset contains various information about the businesses, including whether or not they were successful.

## Technologies
Pandas, scikit-learn, TensorFlow, and Keras are used in this code.

## Installations
pip install pandas
pip install scikit-learn
pip install tensorflow
pip install keras

## Usage
The code is divided into three main sections: preparing the data, compiling and evaluating the model, and optimizing the model.

In the first section, the dataset is read into a Pandas DataFrame, categorical variables are encoded using OneHotEncoder, and numerical variables are added to the encoded DataFrame. The features and target datasets are then created and split into training and testing sets.

In the second section, a binary classification deep neural network model is created using TensorFlow and Keras. The model is compiled and fit using the binary_crossentropy loss function, the adam optimizer, and the accuracy evaluation metric. The model's loss and accuracy are then evaluated using the test data.

In the third section, the model is optimized to improve its accuracy. The code includes suggestions for ways to optimize the model such as adjusting the number of layers and neurons, and experimenting with different activation functions and optimizers.

The final model is saved and exported to an HDF5 file named AlphabetSoup.h5.

## Contributors
I am the main contributor for this code!
