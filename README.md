Object Detection on Images Using YOLO

YOLO (You Only Look Once) is a powerful and fast algorithm for object detection. Before diving into the code, it's crucial to develop a strong understanding of the algorithm.

Important Papers to Study
You Only Look Once: Unified, Real-Time Object Detection
YOLO9000: Better, Faster, Stronger
YOLOv3: An Incremental Improvement
These papers may be challenging to grasp initially, but they are highly recommended for a thorough understanding.

Getting Started with YOLOv3
For this repository, we will be using YOLOv3.

Required Files

You need to download the following YOLO files:

coco.names
yolov3.cfg
yolov3.weights
Save these files inside a folder. You can name the folder anything you like; however, in this repository, it is referred to as yolo-coco, as we are using the COCO dataset objects.

Setting Up the Environment

Create a folder named images and place some pictures inside it to test object detection.
Install the required dependencies using pip:
bash

!pip install numpy
!pip install opencv-python
(Note: This code uses numpy version 1.17.4 and opencv version 3.4.2.)
Running the Object Detection Script

Execute the script by running the following command in your command prompt:
bash

"python yolo.py --image images/ipl.jpeg"

Replace images/ipl.jpeg with the path to any image you wish to use. Ensure you provide the correct file path.
Press q to quit the window displaying the image with detected objects.
