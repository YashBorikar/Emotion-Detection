# Music Recommendation System based on Emotional Detection and User Facial Expression 

Model Analysis the facial expression of user emotion and lead to
understanding the current emotional or mental state of user and recommends a playlist based on detected mood.

Music recommendation system, will assist user to
make a decision regarding which music one should listen to help reducing anxiety level.

## Feature of Emotional Detection Model

Emotional Detection Model use Deep Neural Network with CNN architecture model for Image Classification.

Tensorflow-Keras Convolutional Neural Network with multiple layers is used to train and test model for seven classes - Happy, Angry, Neutral, Sad, Surprise, Fear and Disgust.

Emotional Detection Model integrated with OpenCV to capture user facial expression. 

Engaging UI is developed using Flask Web Application

## Preview


# Installations
Follow steps to use this project:

1. Clone repository
```
git clone https://github.com/YashBorikar/Emotion-Detection.git
```
2. Change directory to clone repository

```
cd Emotion-Detection
```
3. Create a Python virtual environment and activate it
```
$ virtualenv venv
```
```
$ source venv/bin/activate      # For Linux
$ venv\Scripts\activate         # For Windows
```
4. Install required libraries
```
pip install -r requirements.txt
```
# Getting Started

Change directory and Run File
```
cd Flask
python emotion_detection.py
```

# Results

<a href="https://colab.research.google.com/drive/1tyhZi_FwOYV9DC_tXjzxemP4edAevMdF?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

 Training Accuracy: 96.08%, 
 Validation Accuracy: 82.39%
 
<p>
  <img src="Git Assets/Accuracy.png" width="200" alt="Accuracy">
</p>

Model gave 96.08% accuracy for Emotion Detection model after training with 40 epochs.


# Connect me
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555)](https://www.linkedin.com/in/yashborikar/)