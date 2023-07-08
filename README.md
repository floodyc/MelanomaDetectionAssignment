# Melanoma Detection Assignment

In this assignment, I have built a multiclass classification model using a custom convolutional neural network in TensorFlow. 

 
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


## General Information

### The following describes the major steps in performing the analysis:

### Step 1:   Import all the necessary libraries
### Step 2:   Define the paths to the training and testing data sets
### Step 4:   Load the images using Keras
### Step 5:   Create the training and validation data sets
### Step 6:   Visualize a sample of each of the skin cancer types 
### Step 7:   Create the first CNN model
### Step 8:   Visualize and compile the model
### Step 9:   Train the model
### Step 10:  Visualize the training results
### Step 11:  Analyze the training results for over/underfitting
### Step 12: Repeat stpes 7-11 in an attempt to improve the model
### Step 13: Use augmentation to address class imbalance
### Step 14: Determine has class imbalance improved the CNN model
### Step 15: Conclusionsservations and Conclusion
```



## Conclusions
Three models were explored. The first model represented a typical CNN model. The second model dropped the 25% dropout layer and the third model included augmented data where the class imbalances were rectified.¶
The first model showed good performance. The second model showed better performance with one less dropout layer. The third model performance was trending in a very poor direction. The third model was interrupted.
In conclusion, the second model showed the best performance with training accuracy equal to 93% and validation accuracy equal to 90%


## Technologies Used

- Python 3
- Numpy
- Pandas
- OS
- Matplotlib
- Seaborn
- pathlib
- tensorflow
- PIL
- Keras


## Contact

Created by [@floodyc] - feel free to contact me!


