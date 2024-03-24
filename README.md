# Machine Learning Projects Repository
## Overview
Welcome to the Machine Learning Projects Repository! This repository houses diverse machine learning projects, each addressing unique challenges and utilizing various techniques. From entity recognition in audio scripts to facial recognition using eigen spaces, fake news detection, and weed detection using multispectral images—explore the power of machine learning in different domains.

## Project Details
### 1. Entity Recognition from Audio Scripts
Description: A Python script for extracting information from audio scripts, including name, requested service, location, and gender recognition.
Features:
Utilizes natural language processing (NLP) techniques for entity recognition.
Gender recognition based on voice characteristics.

### 2. Face Recognition with Eigen Spaces
Description: Face recognition project implementing eigen spaces for facial feature representation.
Features:
Eigenface algorithm for dimensionality reduction in facial feature space.
Face recognition based on eigenfaces.

### 3. Fake News Detection
Description: Analysis of a Kaggle dataset for fake news detection using eight machine learning models.
Models Applied:
Logistic Regression
Random Forest
Passive Aggressive Classifier
Support Vector Machine (SVM)
Naive Bayes
Features:
Comparative analysis of model performance.

### 4. Weed Detection using Multispectral Images
Description: Implementation of weed detection using multispectral images with TensorFlow and Keras.
Features:
Utilizes deep learning techniques for image classification.
Multispectral image analysis for accurate weed detection.

### 5. Yolo v3 Object Detection in Tensorflow
Yolo v3 is an algorithm that uses deep convolutional neural networks to detect objects. <br> <br>

## Getting started

### Prerequisites
This project is written in Python 3.6.6 using Tensorflow (deep learning), NumPy (numerical computing), Pillow (image processing), OpenCV (computer vision) and seaborn (visualization) packages.

```
pip install -r requirements.txt
```

### Downloading official pretrained weights
Let's download official weights pretrained on COCO dataset. 

```
wget -P weights https://pjreddie.com/media/files/yolov3.weights
```

### Save the weights in Tensorflow format
Save the weights using `load_weights.py` script.

```
python load_weights.py
```

## Running the model
Now you can run the model using `detect.py` script. Don't forget to set the IoU (Intersection over Union) and confidence thresholds.
### Usage
```
python detect.py <images/video> <iou threshold> <confidence threshold> <filenames>
```
### Images example
Let's run an example using sample images.
```
python detect.py images 0.5 0.5 data/images/dog.jpg data/images/office.jpg
```
Then you can find the detections in the `detections` folder.
<br>
You should see something like this.
```
detection_1.jpg
```
![alt text](https://github.com/heartkilla/yolo-v3/blob/master/data/detection_examples/detection_1.jpg)
```
detection_2.jpg
```
![alt text](https://github.com/heartkilla/yolo-v3/blob/master/data/detection_examples/detection_2.jpg)
### Video example
You can also run the script with video files.
```
python detect.py video 0.5 0.5 data/video/shinjuku.mp4
```
The detections will be saved as `detections.mp4` file.
![alt text](https://github.com/heartkilla/yolo-v3/blob/master/data/detection_examples/detections.gif)


### Usage
### Clone the Repository:
git clone https://github.com/Javeria-Hassan-SE/Machine-Learning-Projects.git

### Contribute:

Contribute by submitting bug reports, feature requests, or your own machine learning projects.
Follow standard GitHub practices for forking the repository and creating pull requests.

Feel free to reach out with any questions or feedback. Happy exploring in the world of machine learning!
