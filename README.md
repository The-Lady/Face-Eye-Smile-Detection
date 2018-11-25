# Face Eye and Smile Detection

### Introduction
A CLI application for detecting faces, eyes and smiles while capturing and streaming live video from webcam.
In case another camera is to be used instead of webcam, change the index from ***0*** to the index of the camera being used in file ***faceDetection.py*** at line
```python
cap = cv2.VideoCapture(0)
```


### Steps for running the project
1. Clone the repo via [URL](https://github.com/The-Lady/Face-Eye-Smile-Detection.git)
2. Set up virtual environment:
    - Create virtual environment using command `virtualenv venv`
    - Activate the virtual environment *venv* environment
    - Install requirements using command `pip install -r requirements.txt`
3. Run the project using command `python faceDetection.py`
