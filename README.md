# Emotion-Recognition
This project particularly aims on the classification of a person's face into one of seven categories, using deep convolution neural networks. 

#### Features
 - Facial emotion recognition is the process of detecting human emotions from facial expressions.
 - The human brain recognizes emotions automatically, and software has now been developed that can recognize emotions as well
 - The idea here is to build a deep learning model which is able to predict emotions of people at real time. We can classify our data into 7 different emotions(Angry,Disgust,Fear,Happy,Sad,Surprise,Neutral)

#### Under the hood
 - Pandas library is used for reading the dataset stored in csv file.
 - Numpy library is used for converting data into image format.
 - Opencv library is used for reading image data and passing that data into our custom deep learning model.
 - Tensorflow and Keras library were used to build and train the model.
 - Matplotlib library is used to visualize the data and training curves.

#### Data Preparation

- The original FER2013 dataset in Kaggle is available as a single csv file. I had converted into a dataset of images for training/testing. The dataset can be downloaded from https://www.kaggle.com/deadskull7/fer2013
#### Working

- Clone the repository using git clone 
```bash
git clone https://github.com/rnag5076/Emotion-Recognition.git
cd Emotion-Recognition
```
- Run the real_time.py file which will load my customized model and will predict the emotions in real time through webcam.
```bash
python real_time.py
```
- If you want to generate the model you can use emotion_analysis.py and run it to see the results as well.
```bash
python emotion_analysis.py
```
