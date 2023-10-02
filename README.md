# Object Detection and Tracking on Live Webcam:
<div>
  In this project I have implemented the following:
  <p>
    # Live Webcam Feed: I have implemented a Flask application that can capture and display a live webcam feed in a web browser. Users can access the feed through a web interface. <br>
    # Object Detection: I have integrated object detection into the application using YOLOv5. The application is capable of identifying objects in the live webcam feed in real-time.  <br>
    # Object Tracking: I have also successfully implemented object tracking into the application using DeepSORT to monitor the movement and location of detected objects as they move within the webcam frame.  <br>
  </p>
</div>

# Project Implementation:
<div>
  following are the steps to implement the project in your device. <br>
  <p>
    1.	Create a new project into pycharm and crate new virtual environment. <br>
    2.	Clone the complete project from github repository.  <br>
    3.	Download all the required libraries for the project into new virtual environment using command:  <br>
    >> pip install -r requirements.txt  <br>
    4.	Downloaded and place the weights file ‘yolov5s.pt’ in your project directory from “https://github.com/ultralytics/yolov5/releases”.  <br>
    5.	In the “app.py” file, change the path of the ‘weights’ parameter of run() function to your file path of “yolov5s.pt” file.  <br>
    6.	In the “detection_tracker.py” file on line 106, change the path of “mars-small128.pb” file to your file path from the “model_data” folder.  <br>
    7.	Run the app using command:  <br>
    >> python app.py   <br>
    8.	Open the link http://localhost:5000 in your google chrome or any browser.  <br>
  </p>
</div>
