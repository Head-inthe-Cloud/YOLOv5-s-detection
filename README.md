# YOLOv5-s-cone-detection


### This repo contains the model for YOLOv5 cone detection and the training data set


**The pretrained model is trained by using the following code:**

```
cd yolov5

python train.py --img 640 --batch 16 --epochs 5 --data cone.yaml --weights best.pt

```

**best.pt** can be replaced by **last.pt** or **best.pt** from different runs in the **runs** folder.

Data for each run can be found in **runs** folder.

Most Recent result:

**Labeled data**
![labeled_data](images/labeled.jpeg)


**Predicted data**
![predicted_data](images/predicted.jpeg)


The source of data is this repo:
	https://github.com/MarkDana/RealtimeConeDetection

Where the author labelled this dataset: 
	https://www.dropbox.com/s/fag8b45ijv14noy/cone_dataset.tar.gz?dl=0

The labelled dataset (In PASCAL VOC format, and YOLOv3 format):
	https://jbox.sjtu.edu.cn/v/link/view/5b75acf81cbd4e3298aa118c1b1cceea

Which I later converted to darknet format for Yolov5

