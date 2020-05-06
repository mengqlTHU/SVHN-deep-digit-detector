# SVHN-deep-cnn-digit-detector for Python 3

This is an adaption of the [original code](https://github.com/penny4860/SVHN-deep-digit-detector) to python 3 and opencv 4.x. Note that the training code has been removed, so it is only valuable for people who wants to run detection and recognition.

This project implements deep-cnn-detector (and recognizer) in natural scene. I used keras framework and opencv library to build the detector.
This detector determine digit or not with CNN classifier for the region proposed by the MSER algorithm.

## Prerequisites

* python 3
* opencv_python 4.x
* Etc

A list of all the packages needed to run this project can be found in [requirements.txt](https://github.com/mengqlTHU/SVHN-deep-digit-detector/blob/master/requirements.txt). 

#### Virtual Env

You can create a virtualenv and install the requirements with pip.

## Usage

### 1-2. Training(Skipped)

### 3. Run the detector (3_detect.py)

In the running time, the detector operates in the 2-steps.

1) The detector finds candidate region proposed by the MSER algorithm.

<img src="examples/mser.png">

2) The classifier determines whether or not it is a number in the proposed region.

<img src="examples/classifier.png">


### 4. Evaluate the detector (Skipped)
    
## Related Projects

* [Yolo-digit-detector](https://github.com/penny4860/Yolo-digit-detector)
* [Weakly-Supervised-Text-Detection](https://github.com/penny4860/Weakly-Supervised-Text-Detection)

