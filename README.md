# General Pneumonia Classification and Localization with Object Detection + Heroku

## Demo
http://amicii.herokuapp.com/
__________________________________________________________________________________________________________________________________________

This project exploits the Single Shot Detector (SSD) V1 pretrained transfer weights for Pneumonia localization and classification. By combining Heroku web application deployment and a lightweight SSD architecture, rapid patient-doctor recognition of Pneumonia presence can be executed in under 5-8 seconds. The SSD model is primarily preconfigured for real-time object detection on, for example, the Android object detection library instances. However, the graph.pbtxt and model configuration file can be packaged into a live web application for active feature extraction and final bounding box adjustment. The Single Shot Detector accomplishes this through nonmaximum suppression, which initiates thousands of potential Regions of Interests (ROIs) and uses its convolutions to slowly break them down.

![enter image description here](https://miro.medium.com/max/2000/1*up-gIJ9rPkHXUGRoqWuULQ.jpeg)

![enter image description here](https://i.imgur.com/YKF25Kj.png)

