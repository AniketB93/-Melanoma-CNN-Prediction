# Melanoma-CNN-Prediction
> A CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant. The data set contains the following diseases:

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
The data set contains the following diseases:
1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion

NOTE: You don't have to use any pre-trained model using Transfer learning. All the model building process should be based on a custom model.


## Technologies Used
Python
Tensorflow
keras
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Conclusions
* Model 1 Initially we tried without any data augmentation , dropouts and we saw oferfitted model clearly.
* Model 2 We used data augmentation and dropouts which removed overfitting completely
* Model 3 At last we tried Batch Normalization and Augumentation which really helped in carry forward and handled overfitting , improved accuracy by more than 93 % and validation accuracy upto 77 %

## Contact
Created by [@Aniket Badekar] - feel free to contact me!

