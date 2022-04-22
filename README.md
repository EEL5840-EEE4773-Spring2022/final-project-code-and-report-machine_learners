# Final Project

This is a **group assignment**.

## Milestone 2 - Code Implementation & Technical Report

This milestone is to be delivered at the end of the semester, Friday April 22 @ 11:59 PM. Find the complete [rubric](https://ufl.instructure.com/courses/447948/assignments/5138679) in the Canvas assignemtn.

## Training Data

The training data set is the same for every team in this course.

You can download the data in our Canvas page:
* ["data_train.npy"](https://ufl.instructure.com/courses/447948/files/folder/Final%20Project?preview=67069006)
* ["labels_train.npy"](https://ufl.instructure.com/courses/447948/files/folder/Final%20Project?preview=67068769)

## Edit this READ-ME

Please edit this read-me file with information about your project. You can find a [READ-ME template here](https://github.com/catiaspsilva/README-template).

Final_CNN - This is our saved CNN model after training on all data_train.npy images with best parameters achieved through GridSearch CV.

train.ipynb - Jupyter notebook with code including all preprocessing , GridSearch CV, and then training on final model steps.

easy_test.ipynb - Jupyter notebook used to classify the images and test the accuracy of Easy Test Dataset.

Dependencies:-

Tensorflow 2.6, Opencv, Seasborn, sklearn, sckit-learn, keras, numpy, matplotlib, argparse, skimage, pandas.

HOW TO RUN:-

For training file (train.ipynb), load the data and labels file (.npy) in the first cell by changing the directory in np.load('') and just run all the cells.

Dimensions of data should be 90000xN, where, N is number of samples.

Similarly, change the np.load() directory to load the data for easy_test.ipynb and hard_test.ipynb and dimension should be again 90000xN.
