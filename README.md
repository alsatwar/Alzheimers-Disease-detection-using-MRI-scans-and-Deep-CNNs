# Alzheimers-Disease-detection-using-MRI-scans-and-Deep-CNNs
![Images of Dataset](https://github.com/alsatwar/Alzheimers-Disease-detection-using-MRI-scans-and-Deep-CNNs/blob/master/images/Data.png)

Alzheimer's Detection based on Demented and Mild Demented scans using Transfer Learning algorithms: VGG19, NasNetLarge, Inception_V3, and Xception. The models are trained for 500 epochs on around 200 Demented and 200 Non Demented  images on Google Colab CPU.

Accuracies of the models after training are shown below:

Model  | Inception_V3 | Xception | VGG19 | NasNetLarge
--------|--------------|----------|-------|------------
Accuracy| 90% | 88% | 93% | 90%

## Dataset

The resources for this project was collected from kaggle website posted by Sarvesh Dubey. We used this dataset to perform binary classification between Non Demented and Mild Demented images. Albeit resource consisted of around 2000 images each, but study used only 200 images from each category. Sequentially, images were preprocessed to resize into (229,229) and 80% images are used as training_data and 20% images as test_data.

Alzheimer's Dataset link :  https://www.kaggle.com/tourist55/alzheimers-dataset-4-class-of-images 

# Results

### _**Predicted samples from trained models:**_

![Sample outputs](https://github.com/alsatwar/Alzheimers-Disease-detection-using-MRI-scans-and-Deep-CNNs/blob/master/images/cent_non_dem.png)
![Sample outputs](https://github.com/alsatwar/Alzheimers-Disease-detection-using-MRI-scans-and-Deep-CNNs/blob/master/images/cent_dem.png)

## _**Classification reports of Inception_V3, Xception, VGG19, NasNetLarge**_

![repo](https://github.com/alsatwar/Alzheimers-Disease-detection-using-MRI-scans-and-Deep-CNNs/blob/master/images/F1_score.png)

## _**Confusion matrices of Inception_V3, Xception, VGG19, NasNetLarge**_

![repo](https://github.com/alsatwar/Alzheimers-Disease-detection-using-MRI-scans-and-Deep-CNNs/blob/master/images/CM.png)

# Theory & Review

**ImageNet** is formally a project aimed at (manually) labeling and categorizing images into almost 22,000 separate object categories for the purpose of computer vision research.

**Inception_V3** is a convolutional neural network that is 48 layers deep. You can load a pretrained version of the network trained on more than a million images from the ImageNet database. The pretrained network can classify images into 1000 object categories, such as keyboard, mouse, pencil, and many animals. As a result, the network has learned rich feature representations for a wide range of images. The network has an image input size of 299-by-299.

**Xception** is a convolutional neural network that is 71 layers deep. You can load a pretrained version of the network trained on more than a million images from the ImageNet database. The pretrained network can classify images into 1000 object categories, such as keyboard, mouse, pencil, and many animals. As a result, the network has learned rich feature representations for a wide range of images. The network has an image input size of 299-by-299.

**VGG_19** is a convolutional neural network that is 19 layers deep. You can load a pretrained version of the network trained on more than a million images from the ImageNet database [1]. The pretrained network can classify images into 1000 object categories, such as keyboard, mouse, pencil, and many animals. As a result, the network has learned rich feature representations for a wide range of images. The network has an image input size of 224-by-224.

**NasNetLarge** is a convolutional neural network that is trained on more than a million images from the ImageNet database [1]. The network can classify images into 1000 object categories, such as keyboard, mouse, pencil, and many animals. As a result, the network has learned rich feature representations for a wide range of images. The network has an image input size of 331-by-331.
