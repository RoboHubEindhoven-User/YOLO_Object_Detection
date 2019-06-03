# YOLO Object detection RoboHub Eindhoven

This is a repository for the YOLO object detection for the Robocup@work competition that @RoboHubEindhoven participates in. This repository consists of the [ultralytics python yolov3](https://github.com/ultralytics/yolov3) with some custom adjustments.

If you want to learn more of how the vision systems work, please check out our wiki.

## Getting started

For this project ubuntu 16.04 is used.

### Prerequisites

This package runs on python3.7 or later with the following packages:

* `numpy`
* `torch >= 1.1.0`
* `opencv-python`
* `tqdm`
* `Cuda toolkit`

For cloning ultralytics python yolov3 use git clone into your own custom workspace:

```bash
git clone https://github.com/ultralytics/yolov3.git
```

For cloning this custom version based on the [ultralytics](https://github.com/ultralytics/yolov3) version use:

```bash
git clone https://github.com/RoboHubEindhoven/YOLO_Object_Detection.git
```

## Usage

To run the program execute the following command in a terminal:

```bash
python3 test.py
```


