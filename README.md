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

1. Final_CNN - This is our saved CNN model after training on all data_train.npy images with best parameters achieved through GridSearch CV.
2. train.ipynb - Jupyter notebook with code including all preprocessing , GridSearch CV, and then training on final model steps.
3. easy_test.ipynb - Jupyter notebook used to classify the images and test the accuracy of Easy Test Dataset.
4. Final_Report.docx - Report of our project
5. new_labels_train.npy - Corrected labels file of traing data

Dependencies:-
  1. Tensorflow 2.6, 
  2. OpenCV,
  3. Seasborn, 
  4. sklearn, 
  5. sckit-learn, 
  6. keras, 
  7. numpy, 
  8. matplotlib, 
  9. argparse, 
  10. skimage, 
  11. pandas.

HOW TO RUN:-

1. All packages mentioned above should be installed before runnning any code file.
2. You just have to change np.load() in the first cell and load your own data
3. Dimension of data.npy file should be (90000,N), where N is number of images or samples and Labels.npy dimensions should be (N)
4. Now, run all the cells in Easy_Test and Hard_Test and you will see that Confusion Matrix and Accuracy in the last 3 cells.
