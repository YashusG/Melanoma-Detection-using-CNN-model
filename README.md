# Melanoma Detection using CNN Model
> The project aims to build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## General Information
- The dataset that is being used? The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
The dataset can be downloaded at: https://drive.google.com/file/d/1xLfSQUGDl8ezNNbUkpuHOYvSpTyxVhCs/view?usp=sharing

## Conclusions
By addressing the class imbalance, the CNN model was able to better generalise the predictions. This can be seen from the fact that both the training dataset accuracy and validation dataset accuracy are well in acceptable ranges and there in not as much of a deviation as was seen earlier.

By using epochs of 30 we see a validation score of around 80%

Thus the current version of the CCN model is better as compared to the earlier models after it was trained on the augmented data.


## Acknowledgements
- Kaggle, ChatGPT

## Contact
Created by [https://github.com/YashusG] - feel free to contact me!
