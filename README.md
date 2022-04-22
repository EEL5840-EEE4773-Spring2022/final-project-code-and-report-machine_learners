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

## About The Project
1. train.ipynb - Jupyter notebook with code including all preprocessing, GridSearch CV, and then training on final model and saving the model as "Final_CNN".

For preprocessing we tried many cv2 functions such as MORPH_OPEN, CLOSE, GRADIENT, Blurs but finally we used only medianblur and Morph_Open.

2. Final_CNN - This is our saved CNN model after training on all data_train.npy images with best parameters achieved through GridSearch CV.

After saving the model we can use it in easy_test and hard_test files to test on new data.

3. easy_test.ipynb - Jupyter notebook used to classify the images and test the accuracy of Easy Test Dataset.
4. Final_Report.docx - Report of our project
5. new_labels_train.npy - Corrected labels file of traing data
6. data.npy - temporary data of 400 images to test our data, just to check if the code is working fine, any data with proper dimensions mentioned below can be used.
7. labels.npy - labels for above data.npy

## Getting Started
In this section you should provide instructions on how to use this repository to recreate your project locally.
1. You can use 'git clone' to clone this repository (Project link is given below)
2. Just change the np.load() and load your own data with dimension(90000,N)
3. For training use can use data from the links given above.


## Dependencies
1. Tensorflow 2.6
   pip install tensorflow==2.6
2. OpenCV 4.5.2
   pip install opencv-python
3. Seaborn
   pip install seaborn
4. Sklearn
   pip install sklearn
5. sckit-learn
   pip install -U scikit-learn
6. keras
   pip install keras
7. numpy
   pip install numpy
8. matplotlib
   pip install matplotlib
9. pandas
   pip install pandas


## Usage

1. All packages mentioned above should be installed before runnning any code file.
2. You just have to change np.load() in the first cell and load your own data
3. Dimension of data.npy file should be (90000,N), where N is number of images or samples and Labels.npy dimensions should be (N)
4. Now, run all the cells in Easy_Test and Hard_Test and you will see that Confusion Matrix and Accuracy in the last 3 cells.
For more examples, please refer to the Documentation


## Authors

Rajat Bishnoi - rajatbishnoi@ufl.edu
James Overmeyer - jovermeyer@ufl.edu
Cody Hutcheson - c.hutcheson@ufl.edu

### Project Link: https://github.com/EEL5840-EEE4773-Spring2022/final-project-code-and-report-machine_learners

## Acknowledgements

1. Catia Silva
3. GitHub
4. Stackoverflow
5. Medium.com
6. towardsdatascience.com
7. tensorflow.org

### Thank you