# Vehicle Counting and Speed Estimation using YOLOv8 and OpenCV

This project involves implementing vehicle detection, counting, and speed estimation using YOLOv8 for object detection and OpenCV for subsequent analysis. The system identifies vehicles in videos, counts them, and estimates their speeds based on their movement.

## Project Overview

- **Vehicle Detection with YOLOv8:**
  - Utilized YOLOv8 for accurate vehicle detection in video streams or recorded videos.
  - Employed pre-trained YOLOv8 weights for object detection of vehicles.

- **Vehicle Counting:**
  - Implemented vehicle counting algorithms based on detected bounding boxes to count the number of vehicles passing through defined regions or frames.

- **Speed Estimation:**
  - Utilized frame timestamps and vehicle tracking information to estimate vehicle speeds based on distance covered and time elapsed.

## Requirements

- Python 3.x
- YOLOv8 framework
- OpenCV library for video processing and analysis
- Input videos for vehicle detection and speed estimation


<H1 align="center">
YOLOv8 Object Tracking and Speed Estimation

## Google Colab File Link (A Single Click Solution)
The google colab file link for yolov8 object tracking, blurring and  counting is provided below, you can check the implementation in Google Colab, and its a single click implementation
,you just need to select the Run Time as GPU, and click on Run All.

[`Google Colab File`](https://colab.research.google.com/drive/1haDui8z7OvITbOpGL1d0NFf6M4BxcI-y?usp=sharing)


## Steps to run Code

- Clone the repository
```
git clone https://github.com/tosifAN/Vehicle_Counting_And_Speed_estimation
```
- Goto the cloned folder.
```
cd Vehicle_Counting_And_Speed_estimation
```
- Install the dependecies
```
pip install -e '.[dev]'

```

- Setting the Directory.
```
cd ultralytics/yolo/v8/detect

```
- Downloading the DeepSORT Files From The Google Drive 
```

https://drive.google.com/drive/folders/1kna8eWGrSfzaR6DtNJ8_GchGgPMv3VC8?usp=sharing
```
- After downloading the DeepSORT Zip file from the drive, unzip it go into the subfolders and place the deep_sort_pytorch folder into the yolo/v8/detect folder

- Downloading a Sample Video from the Google Drive
```
gdown https://drive.google.com/uc?id=1_kt1alzcLRVxet-Drx0mt_KFSd3vrtHU
```

- Run the code with mentioned command below.

- For yolov8 object detection, Tracking,  blurring and object counting
```
python predict.py model=yolov8l.pt source=test_video_path show=True
```

