
# Hand Sign Recognition
![Alt text](HandSignRecognition/../Tensorflow/workspace/images/hu.png)

![GitHub language count](https://img.shields.io/github/languages/count/Vikrant00/Campgrounds)
![top language](https://img.shields.io/github/languages/top/Vikrant00/Campgrounds)
![GitHub repo size](https://img.shields.io/github/repo-size/Vikrant00/Campgrounds)
![Watchers](https://img.shields.io/github/watchers/Vikrant00/Campgrounds?style=social)

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
![Alt text](HandSignRecognition/../Tensorflow/workspace/images/1.png)
![Alt text](HandSignRecognition/../Tensorflow/workspace/images/2.png)
![Alt text](HandSignRecognition/../Tensorflow/workspace/images/3.png)
![Alt text](HandSignRecognition/../Tensorflow/workspace/images/4.png)