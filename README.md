# DS NN basic function
A shallow Neural Network (from now 'NN') for the Classification of Data, acquired by a medical device prototype.

# The Medical Device (DermaSense)
The DermaSense prototype is an experimental dermatological diagnostic tool that measures skin alterations by the use of electric current. For each measurement, the values of current are exported as a 8x10 matrix in a .csv file.

# Imported Data
For the reason that the device is experimental, any conclusion for the performance of the NN while using real data is doubtful. As a result, the matrices that are used for the NN training are not real and have been created using random number generators with specific distribution range.

# Process
The matrices from the files are imported and merged in one Dataframe.

Many variables for the Classifier's training are easily changable, in order to provide quick development iteration.

# Prediction
In order to measure the accuracy of the Classifier's predicted values, the already known values of the "Test Set" have been used.
