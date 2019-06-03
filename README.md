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

For cloning [ultralytics python yolov3](https://github.com/ultralytics/yolov3) use git clone into your own custom workspace:

```bash
git clone https://github.com/ultralytics/yolov3.git
```

For cloning this custom version based on the [ultralytics](https://github.com/ultralytics/yolov3) version use:

```bash
git clone https://github.com/RoboHubEindhoven/YOLO_Object_Detection.git
```

## Usage

### Execute

To run the program execute the following command in a terminal:

```bash
python3 test.py
```

To change the Config file which is used change the filepath in `defaults_dicts` to the `.cfg` file that you want to use.


### Pretrained Weights
Below are the links to the pretrained weights:

* Darknet `*.weights` format: https://pjreddie.com/media/files/yolov3.weights
* PyTorch `*.pt` format: https://drive.google.com/drive/folders/1uxgUBemJVw9wZsdpboYbzUN4bcRhsuAI


# Authors

**Mike van Lieshout** - in name of RoboHub Eindhoven - [RoboHub Eindhoven website](https://www.robohub-eindhoven.nl)



