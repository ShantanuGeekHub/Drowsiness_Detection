# Drowsiness_Detection_Using_YOLOv5

In this project I trained a model that detects whether the person is drowsy or awake using YOLOv5.

I used dataset consisting about 20 images of both awake as well as drowsy class. Further I trained it with yolov5s.pt for 500 epochs on google colab and it achieved mAP_0.5 = 0.995.

I haven't expected those results from such a small amount of dataset, but it did very well.

In order to run this notebook on your local machine, refer to the instruction given below.

1. firstly download zip or clone this repository, 
2. then run first cell from the notebook(.ipynb file) that you'll find in this repository folder and it'll clone actual yolov5 repository. 
3. After that move best.pt file from this repository folder to Yolov5 repository folder.
4. Now specify the path of yolov5 folder as first parameter of torch.hub.load() method as shown below.

   torch.hub.load(r"Enter_yolov5_folder_path_from_your_pc_over_here", 'custom', path="best.pt", force_reload=True, source='local')

5. That's it, now run all the cells. It'll work for sure. 
