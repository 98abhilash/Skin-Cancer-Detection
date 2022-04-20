# Melanoma Skin Cancer Detection
> Outline a brief description of your project.


## Table of Contents
- [Melanoma Skin Cancer Detection](#melanoma-skin-cancer-detection)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
    - [Problem Statement](#problem-statement)
  - [Conclusions](#conclusions)
  - [Technologies Used](#technologies-used)
  - [Contact](#contact)


## General Information
### Problem Statement
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

* Actinic keratosis
* Basal cell carcinoma
* Dermatofibroma
* Melanoma
* Nevus
* Pigmented benign keratosis
* Seborrheic keratosis
* Squamous cell carcinoma
* Vascular lesion


## Conclusions
- The first model seems to be overfitted
- The second model with data augmentation layer seems to be underfitting because of class imbalance
- The third model with external image augmentation adding 500 samples in each class seems to be overfitting

## Technologies Used
    Pandas - version 1.3.3
    Numpy - version 1.20.3
    Matplotlib - version 3.4.3
    keras - version 2.6.0
    tensorflow - version 2.6.0



## Contact
Created by [@98abhilash] - feel free to contact me!
