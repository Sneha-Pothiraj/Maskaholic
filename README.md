# Face-Mask-Detection
Face mask detector built using OpenCV, TensorFlow/ Keras using Deep Learning and Computer vision concepts to detect face masks in real-time video streams.

# About
We train our project into two distinct phases:
1) TRAINING: We load our dataset, which was collected from various sources such as Kaggle, Google images, etc and train a model using(Keras/ Tensorflow) on this it.
2) DEPLOYMENT: Once the face mask detector, we load it, perform face detection and then classify each face as with_mask or without_mask.

# Contents
1) **Dataset**: A directory which contains the dataset.
2) **face_detector**: Contains files needed for face detection.
3) **detect_mask.model**: Model that we trained using the dataset.
4) **Detection.py**: Accepts our input dataset and fine-tunes MobileNetV2 upon it to create our detect_mask.model.
5) **requirements.txt**: Contains the list of all dependencies needed for the program.
6) **Training.py**: Using your webcam, this script applies face mask detection to every frame in the stream.

# Installation
1. Clone the repository
```
$ git clone https://github.com/Sneha-Pothiraj/Face-Mask-Detection.git
```

2. Change your directory to the cloned repo 
```
$ cd Face-Mask-Detection
```

3. Now, run the following command in your Terminal/Command Prompt to install the libraries required
```
$ pip3 install -r requirements.txt
```
# Working
1. Open terminal. Go into the cloned project directory and type the following command:
```
$ python3 Training.py
```

2. To detect face masks in real-time video streams type the following command:
```
$ python3 Detection.py 
```

    

