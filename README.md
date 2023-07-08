# white-blood-cell-image-classification-
Data Summary

This task aims to classify images of White Blood Cells into 9 subtypes. The specific types of WBCs to be classified are as follows: bands, basophils, blasts, eosinophils, lymphocytes, metamyelocytes, monocytes, myelocytes, and neutrophils.

The data has been provided to me and it contains two folders: WBC and classify-images. Images in the WBC folder have been used for training and testing the model. While the classify-images folder has been used to classify images into the 9 subtypes mentioned above.

1 WBC: This folder has 9 sub-folders, each containing labelled images of the sub-types of WBC. The images in these 9 sub-folders are to be used for training and testing the model.

2 classify-images: This folder has unlabelled images. It is to be used for classifying the images after the model has been trained and tested.

Training Environment: Colab Notebook (free version)

Create train and test folders in the base directory:
There are two folders in the base directory:

wbc: it has 9 sub-folders, each containing labelled images of the sub-types of wbc.

classify-images: it has unlabelled images. It is to be used for testing.

Two more folders using the labelled images of the folder wbc in the base directory are created. One folder is named as train and the other as test.

train: 80% of the labelled images of folder wbc are copied into the train folder.

test: the remaining labelled images are copied into the test folder.

The train folder will be used for model training.

The test folder will be used for model testing and evaluation. This is because the folder classify-images has unlabelled images and it is difficult to create confusion matrix using it.
