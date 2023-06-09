
# Hand Sign Recognition
<img src="/Tensorflow/workspace/images/hu.jpg" width="600" height="400">

![GitHub language count](https://img.shields.io/github/languages/count/Vikrant00/HandSignRecognition)
![GitHub repo size](https://img.shields.io/github/repo-size/Vikrant00/HandSignRecognition)
![Watchers](https://img.shields.io/github/watchers/Vikrant00/HandSignRecognition?style=social)

 Hand Sign Recognition is a sign language detector that detects hand signs in real time and labels the movement.
 
 How it works:
```
- First, all the input images were labeled with bounding boxes using Label Image.
- Then trained object detector on the labeled images with transfer learning on existing Tensorflow object detector.
- At last, doing real-time object detection using OpenCV and python with a webcam.
```
<br>

## How to run the webapp on local machine:
- install python
- git clone the project and run the cells in tutorial.ipynb
- the last cell will launch the openCV cam to do real time hand sign detections

## Output:
<img src="/Tensorflow/workspace/images/1.png" width="300" height="300">
<img src="/Tensorflow/workspace/images/2.png" width="300" height="300">
<img src="/Tensorflow/workspace/images/3.png" width="300" height="300">
<img src="/Tensorflow/workspace/images/4.png" width="300" height="300">

