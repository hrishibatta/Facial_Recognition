[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

# Face_Detection

<img src="example.png" height="509" width="643">

This Python program uses OpenAI's Haarcascades to detect faces and used OpenAI's LBPH Face Recognizer to train a model to recognize faces. 

The original data set is not included in this repository. 


## Running

Open the directory using a terminal:
```bash
$ cd "path to folder"
```

Train the program: 
```bash
$ python faces-train.py
```

Run the Facial Recognition
```bash
$ python faces.py
```



## Building
This program requires the following Python modules: cv2, os, pickle, pillow, numpy.

Installing the packages: 
```bash
$ pip install "packageName" --upgrade
```

Make sure to link Image folder in faces-train.py to the image dataset. 
