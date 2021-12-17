# AMLS_21-22 _SN21183138

## Overview

This README is for assignment implementation of Applied machine learning system ELEC0134 21/22. This README will enable you to install and run the code successfully. All the code is based on python and debugging and output display are done through jupyter notebook.

The following two folders are used for two tasks of assignment:

* Task A: Binary classification for MRI images
* Task B: Multiple classification for MRI images

&nbsp;      


## Install of Packages

To run the code successfully in your own computer, following packages are needed to be installed and configured.

* NumPy
* pandas
* OpenCV
* glob
* scikit-learn
* pickle
* Keras (TensorFlow)


##  Organization of the files and its role



###  Task A
The following files and folders are in folder Task A, used for implementation of binary classification task A.


#### DataAfterProcess
* This folder saves preprocessed data. 
* Detailed information can be found in Section 4.2.1 of report.

#### dataset
* This folder saves the original data used for training and validation (both images and labels). 
* Detailed information can be found in Section 4.1 of report.

#### Model
* This folder saves the trained model. 
* Detailed information can be found in Section 4.2 of report.

#### test
* This folder saves the original data used for test (both images and labels).  
* Detailed information can be found in Section 4.1 of report.

####  DataPreProcess.ipynb
* This file saves the code for pre-process of data used for training and validation.  
* Detailed information can be found in Section 4.2.1 of report.

####  DataPreProcess_Test.ipynb
* This file saves the code for pre-process of data used for test.  
* Detailed information can be found in Section 5.1 of report.

####  LogisticRegression.ipynb.ipynb
* This file saves the code for traning, validation, test of logistic regression.  
* Detailed information can be found in Section 4.2.2 and 5.1 of report.

####  NN.ipynb.ipynb
* This file saves the code for traning, validation, test of neural network.  
* Detailed information can be found in Section 4.2.4 and 5.1 of report.

####  SVM.ipynb.ipynb
* This file saves the code for traning, validation, test of support vector machine.  
* Detailed information can be found in Section 4.2.3 and 5.1 of report.

&nbsp;    
&nbsp;    

###  Task B
The following files and folders are in folder Task B, used for implementation of mutilple classification task B.


#### DataAfterProcess
* This folder saves preprocessed data. 
* Detailed information can be found in Section 4.3.1 of report.

#### dataset
* This folder saves the original data used for training and validation (both images and labels). 
* Detailed information can be found in Section 4.1 of report.

#### Model
* This folder saves the trained model. 
* Detailed information can be found in Section 4.3 of report.

#### test
* This folder saves the original data used for test (both images and labels).  
* Detailed information can be found in Section 4.1 of report.

####  DataPreProcess_Image.ipynb
* This file saves the code for pre-process of image data used for training and validation.  
* Detailed information can be found in Section 4.3.1 of report.

####  DataPreProcess_Lable.ipynb
* This file saves the code for pre-process of label data used for training and validation.  
* Detailed information can be found in Section 4.3.1 of report.

####  DataPreProcess_TestImage.ipynb
* This file saves the code for pre-process of image data used for test.  
* Detailed information can be found in Section 5.2 of report.

####  DataPreProcess_TestLable.ipynb
* This file saves the code for pre-process of label data used for test.  
* Detailed information can be found in Section 5.2 of report.

####  DataPreProcess_VGG16.ipynb
* This file saves the code for pre-process of data used for transfer learning with VGG16.  
* Detailed information can be found in Section 4.3.4 of report.

####  NN_hog.ipynb.ipynb
* This file saves the code for traning, validation, test of neural network with HOG.  
* Detailed information can be found in Section 4.3.3 and 5.2 of report.

####  SVM.ipynb.ipynb
* This file saves the code for experiment in data pre-process.  
* Detailed information can be found in Section 4.3.1 of report.

####  SVM_hog.ipynb
* This file saves the code for traning, validation, test of support vector machine with HOG.  
* Detailed information can be found in Section 4.2.2 and 5.2 of report.

#### VGG16.ipynb
* This file saves the code for traning, validation, test of transfer learning with VGG16.  
* Detailed information can be found in Section 4.2.2 and 5.2 of report.




## Run the code

For each .ipynb file, simply click Cell-->Run all, and you are good to go. (Note that this will overwrite the previous results). 
In addition, all codes have been detailed commented and also explained in detail based on the markdown cells in jupyter notebook.