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
