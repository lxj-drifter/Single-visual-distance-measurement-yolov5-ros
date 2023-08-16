# Single-visual-distance-measurement-yolov5-ros
Simple monocular distance measurement using yolov5_ros

This project is modified based on yolov5_ros, which you can find in https://github.com/qq44642754a/Yolov5_ros.git

In this project, the ranging function is added

The range was measured using a usb monocular camera

You need to download and install ros and the usb_camera package that comes with ros

First, you need to be able to boot the usb camera properly (ros will publish the camera topic, you need to change it in the launch file to match it）

Then run the yolo_v5.launch file

In this project, only chairs and people are shown in distance

You can modify the code on your own to make distance measurements on more identifiable objects

The principle of monocular distance measurement is referred to the following connection : https://blog.csdn.net/qq_43010752/article/details/122320949
