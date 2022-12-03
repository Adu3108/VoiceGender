# Voice Gender Recognition
---
This repository contains the project done as a part of CS337: Artificial Intelligence and Machine Learning at IIT Bombay in Autumn 2022.

## Team Members
1. Advait Padhye
2. Kartik Gokhale
2. Harshvardhan Ahirwar
3. Nikhil Manjrekar


## Problem Statement

Gender identification is one of the major problems in speech analysis today. Tracing the gender from acoustic data i.e., pitch, median, frequency etc and being able to do this with reasonable accuracy. Machine learning gives promising results for classification problem in all the research domains. There are several performance metrics to evaluate algorithms of an area. Here, we explore several models and learning methods to be able to predict gender based on voice. We analyse techniques involving feature engineering as well as those which operate on an already existing feature vectors. 

## Resources

[Voice Gender Dataset](https://www.kaggle.com/datasets/primaryobjects/voicegender)

[VoxCeleb Dataset](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/)

## References

https://medium.com/@jameschen_78678/predict-gender-with-voice-and-speech-data-347f437fc4da

## Instructions to Run the Code

### 0) Setting up Virtual Environment and installing necessary packages
```bash
python3 -m venv project
source project/bin/activate
pip install -r requirements.txt
```

### 1) VoiceGender
```bash
python3 LinearClassifier.py
```

### 2) VoxCeleb
```bash
python3 download.py
python3 preprocess.py
python3 main.py
```
