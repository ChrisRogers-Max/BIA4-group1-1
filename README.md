## CNN Chest X-ray Disease Classifier (CCXrDC)
### Overview
CNN Chest X-ray Disease Classifier (CCXrDC) is a pure Python3-based software, aiming to classify users’ input chest X-ray images into four categories: Normal (healthy lungs), Tuberculosis (TB), COVID-19 infection and Bacterial/Viral Pneumonia (TB and COVID-19 infections are excluded) using convolutional neuron network (CNN) and VERY DEEP CONVOLUTIONAL NETWORK (VGG-11). Here is the link of the video tutorial: `link of video`. 
### Software Requirement
Download the software package from `the link of Github`, which requires more than 1GB memory. This software runs in Python3 environment. 
### Environment Preparation 
Virtual environments should be prepared in Python. We recommend to install the package manager [Anaconda] and then install an appropriate [PyTorch] version that supports your device. To see how this can be done, view the following page: 

[Anaconda]: <https://www.anaconda.com/>

[PyTorch]: <https://pytorch.org/>

#### Install packages 
Before using this software, you should make sure that your personal computer installs all following necessary python packages. 
List of necessary packages and corresponding install script using pip install:
```
pip install numpy
```
```
pip install pillow
```
```
pip install scikit-image
```
If you have further problems installing packages, we recommend you to refer to this [website]

[website]: https://packaging.python.org/en/latest/tutorials/installing-packages/
### Execution
This software has a Graphical User Interface (GUI). There are two ways to launch the GUI. 
1. Run the programme by directly clicking the python running button 
2. In the python terminal: python GUI.py

<img src="https://github.com/ljq1902/BIA4-group1/blob/main/picture/images/image1.png" width=80% height=80%>

#### Classify X-ray Images
In the GUI, click the Input Image and upload the chest X-ray image. CCXrDC supports input files of .jpg, .png and .jpeg. 
Choose the preferred model (VGG11 or CNN model) to classify pneumonia types.

<img src="https://github.com/ljq1902/BIA4-group1/blob/main/picture/images/image2.png" width=80% height=80%>

Click the Determine button, GUI will return a classification message and corresponding suggestions. If the result is COVID-19, a link to WHO guidance for self-management after COVID-19-related illness will appear on the right.

<img src="https://github.com/ljq1902/BIA4-group1/blob/main/picture/images/image3.png" width=80% height=80%>

#### Sharpen X-ray Images
Click the Sharpen button and a processed image will spontaneously appear. Click the Save the image button and you can save the processed image in your selected path.

<img src="https://github.com/ljq1902/BIA4-group1/blob/main/picture/images/image4.png" width=80% height=80%>

#### Segment X-ray Images
Click the Segment button and a processed image will spontaneously appear. Click the Save the image button and you can save the processed image in your selected path.

<img src="https://github.com/ljq1902/BIA4-group1/blob/main/picture/images/image5.png" width=80% height=80%>

#### Video Tutorial (Help)
In the GUI, click the HELP button to watch a video tutorial.

<img src="https://github.com/ljq1902/BIA4-group1/blob/main/picture/images/image6.png" width=80% height=80%>

#### About us
Right-click the GUI to know us.

<img src="https://github.com/ljq1902/BIA4-group1/blob/main/picture/images/image7.png" width=80% height=80%>
<img src="https://github.com/ljq1902/BIA4-group1/blob/main/picture/images/image8.png" width=80% height=80%>

#### Quit
Click QUIT to close the program.
#### Warning/Conformation message
If no image is loaded or no model is chosen, a warning message will appear. 
A confirmation message will also appear before quitting the software by clicking the "x" button at the upper corner of the interface.

<img src="https://github.com/ljq1902/BIA4-group1/blob/main/picture/images/image9.png" width=80% height=80%>
<img src="https://github.com/ljq1902/BIA4-group1/blob/main/picture/images/image10.png" width=80% height=80%>

#### Acknowledgements
CCXrDC thanks all used third-party libraries and previous works of Convolutional network construction.
