# CNN Skin Cancer
> To build a CNN based model which can accurately detect melanoma.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Multiclass classification model using a custom convolutional neural network in TensorFlow
- To build a CNN based model which can accurately detect melanoma. 
- Melanoma is a type of cancer that can be deadly if not detected early.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- First model without augmentation and with class imbalance train accuracy is around 0.90 but validation accuracy is 0.4832. The model is overfit.
- Scond model after handling augmentation but with class imbalance looks to be underfit [Train Accuracy: 0.6027, Validation Accuracy: 0.5503].
- Third model after handling augmentation and class imbalance. The model improves the prformance[Train Accuracy: 0.8444, Validation Accuracy: 0.7468].

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Tensorflow
- numpy - version 1.23.2
- pandas - version - 2.2.2
- matplotlib - version - 3.9.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- UpGrad.


## Contact
Created by [@AshishTondon] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->