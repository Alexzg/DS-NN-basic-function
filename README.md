# DS NN basic function
A shallow Neural Network (from now 'NN') for the Classification of Data, acquired by a medical device prototype.

# The Medical Device (DermaSense)
The DermaSense prototype is an experimental dermatological diagnostic tool that measures skin alterations by electric current use. For each measurement the values of current are exported as a 8x10 matrix in a .csv file.

# Imported Data
For the reason that the device is experimental, any conclusion for the performance of the NN is doubtful. As a result, the matrices that are used for the NN training are not real and have been created using Microsoft Excel random number generators with specific distribution range.
The evaluation of the classifier will be ready soon.

# Process
The matrices from the files are imported and merged in one Dataframe.

For the quick assess of the code, a Binary Classifier is trained.

Many variables for the Classifier's training are easily changable, in order to provide quick development iteration.
