# Project Title: A Deep Learning Study For Wall Cracking Image Classification


## Abstract: 
There are many significant defects in a building that may affect by many factors either interior or exterior. Concrete cracks in civil  engineering is a common problem where it requires a lot of workforce and expertise to validate the causes. To classify the cracks detection and its accuracy, an approach of Deep Convolutional Neural Network (DCNN) is introduced to learn the features from cracks image. However, DCNN will time consuming for a massive dataset; hence, a transfer learning method, which is a pre-trained model from a stable DCNN, will help us to simplify the tasks. The **InceptionV3** network model and **MobileNetV2** network model are used to train the dataset and compared. A performance measure method, such as confusion matrix is used to validate the results from training based on the prediction outcome. The MobileNetv2 network found to be superior to InceptionV3 model in classification accuracy on model training but opposite on confusion matrix.


## Some modification to use this model training script:
1. Please download the dataset from here https://bit.ly/3xlz1oc
2. Change directory to suit your use case like `data_dir` and `test_path`


## How To Use It:
1. Run `app.py`, a GUI will popup.
  - <img src="https://github.com/karhong-sam/cracks-image-classification-tensorflow/blob/master/GUI_images/1.png" width="250" height="250">
2. Select `model.h5` or any saved model on your end and load it.
  - <img src="https://github.com/karhong-sam/cracks-image-classification-tensorflow/blob/master/GUI_images/2.png" width="250" height="250">
3. Now select any cracks image from your directory to test it, dont forget to load it before run.
  - <img src="https://github.com/karhong-sam/cracks-image-classification-tensorflow/blob/master/GUI_images/3.png" width="250" height="250">
4. Classification for that image will be shown on the GUI.
  - <img src="https://github.com/karhong-sam/cracks-image-classification-tensorflow/blob/master/GUI_images/4.png" width="250" height="250">


## Remarks:

The training script for transfer learning (**Inception & MobileNet**) are currently **outdated**. Please modify it accordingly to latest version of tensorflow 2.0. If you wish to try the application `tkinter-gui` without training new model, please use `model.h5` model saved from **SimpleNN** script.
