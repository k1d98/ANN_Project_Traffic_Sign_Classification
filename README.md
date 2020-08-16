# ANN_Project_Traffic_Sign_Classification
DATASET
The dataset we will work on is called  German Traffic Sign Recognition Benchmark. 
It’s multiclass, single image classification where we want to classify images to the 
corresponding traffic sign class. For example some of those classes are stop signs, 
different speed limits and others in a total of 43 classes (labeled with numbers from 0 to 42).

LOADING THE DATA
We have loaded the data with the pickle module. Pickle uses binary protocols for serializing
and de-serializing a Python object structure.These images are already split into 3 sets
(train, test and validate) and they are all in the same shape (32, 32, 3).

PREPROCESSING
Without any preprocessing, our scores for accuracy are very similar while we saw a difference in the loss. 
We have applied: grayscaling, histogram equalization and normalization - in that order. 

