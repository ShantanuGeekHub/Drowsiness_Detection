# Drowsiness_Detection_Using_YOLOv5

In this project I trained a model that detects whether the person is drowsy or awake using YOLOv5.

I used dataset consisting about 20 images of both awake as well as drowsy class. Further I trained it with yolov5s.pt for 500 epochs on google colab and it achieved mAP_0.5 = 0.995.

I haven't expected those results from such a small amount of dataset, but it did very well.

In order to run this notebook on your local machine, refer to the instruction given below.

firstly download zip or clone this repository, then run first cell from the notebook(.ipynb file) that you'll find in this repository folder and it'll clone actual yolov5 repository. After that copy and paste best.pt from this repository folder to Yolov5 repository folder and run all the cells. It'll work for sure. 
