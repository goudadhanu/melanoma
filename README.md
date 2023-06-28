# Project Name
> Melanoma Detection : A multiclass classification model using a custom convolutional neural network in TensorFlow.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
#### Problem Statement
- To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 

#### Business problem to be solved
- A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

#### Dataset
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the [International Skin Imaging Collaboration (ISIC)](https://www.kaggle.com/datasets/nodoubttome/skin-cancer9-classesisic). All images were sorted according to the classification taken with ISIC , and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

## Conclusions
- We tried to run differend models, the first one utilising the raw data set. It was observed that the model was overfitting and the accuracy was also low.
- The model was improved by using manual agmentation using RandomFlip and RandomRotation. It was observed that the problem of overfitting was resolved. However, the overall accuracy of thr model was still very low.
- Then we came up with the final model, that uses augmentor library to rebalance the classes. It was observed that the overall accuracy significantly improved without any overfitting/ underfitting.


## Technologies Used
- Augmentor 
- Keras 
- TensorFlow 
- Matplotlib
- Numpy
- Pandas

# Contributors
Dhanush Kumar B s

## Contact
Created by [@goudadhanu] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
