# Age, Gender and Ethnicity prediction from face detection using Convolutional Neural Network
## Project description
This project present and automatic approach for face detection and face classification. By using the UTKFace dataset, a CNN is trained in a multi-label classification task in order to predict the age, gender and ethnicity of a given face in input. After training the network we perform the face detection task by using OpenCV on images external to the dataset and taken from the web. The detected faces are then used as input for the pre-trained network which performs the age regression task and gender, ethnicity classifications (main). By contrast, the same experiment is repeated by substituting the age regression task with an age classification task considering age ranges as classes (main2). At the end we show the differences of both the approaches in terms of predictions on external samples as well in order to profile unknown subjects in the best way possible.

## Dataset
The [dataset](https://drive.google.com/file/d/1-8toExAWx3LFXydBG-XaMc9jiQ9QunH2/view?usp=sharing) is freely available on my personal drive. 

The Dataset chosen was the [UTKFace](https://susanqq.github.io/UTKFace/) one. The latter is rewritten .csv file. To do so,  a file python has been used with wich each 200×200×3 image, representing a cropped face, is opened and resized to a 64×64×3 image by using the PIL library. At this point the multidimensional array is flattened and transformed into a list of strings.


