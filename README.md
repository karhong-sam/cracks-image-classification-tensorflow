# Project Title: A Deep Learning Study For Wall Cracking Image Classification


## Abstract: 
There are many significant defects in a building that may affect by many factors either interior or exterior. Concrete cracks in civil  engineering is a common problem where it requires a lot of workforce and expertise to validate the causes. To classify the cracks detection and its accuracy, an approach of Deep Convolutional Neural Network (DCNN) is introduced to learn the features from cracks image. However, DCNN will time consuming for a massive dataset; hence, a transfer learning method, which is a pre-trained model from a stable DCNN, will help us to simplify the tasks. The **InceptionV3** network model and **MobileNetV2** network model are used to train the dataset and compared. A performance measure method, such as confusion matrix is used to validate the results from training based on the prediction outcome. The MobileNetv2 network found to be superior to InceptionV3 model in classification accuracy on model training but opposite on confusion matrix.


## Some modification to use this model training script:
Changed directory to suit your use case like: `data_dir` and `test_path`


## Remarks:

The training script for transfer learning (**Inception & MobileNet**) are currently outdated. Please modify it accordingly to latest version of tensorflow 2.0. If you want to try the application, please use `model.h5` model saved from **SimpleNN** script.
