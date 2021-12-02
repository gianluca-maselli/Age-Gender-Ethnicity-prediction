# Age, Gender and Ethnicity prediction from face detection using Convolutional Neural Network

This project present and automatic approach for face detection and face classification. By using the UTKFace dataset, a CNN is trained in a multi-label classification task in order to predict the age, gender and ethnicity of a given face in input. After training the network we perform the face detection task by using OpenCV on images external to the dataset and taken from the web. The detected faces are then used as input for the pre-trained network which performs the age regression task and gender, ethnicity classifications. By contrast, the same experiment is repeated by substituting the age regression task with an age classification task considering age ranges as classes. At the end we show the differences of both the approaches in terms of predictions on external samples as well in order to profile unknown subjects in the best way possible.


