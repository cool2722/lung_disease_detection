# Lung Disease Detection with YOLO

This notebook is inspired by [VinBigData-CXR-AD YOLOv5 14 Class train](https://www.kaggle.com/code/awsaf49/vinbigdata-cxr-ad-yolov5-14-class-train?kernelSessionId=52422980) and attempts to perform training on the whole dataset, with more disease types than the one in the competition.

The aim was to develop a model that can detect multiple different types of diseases in the lungs. The task is not only classification but also detection using bounding boxes (x and y coordinates). The work serves as a starting point for more powerful and promising future models.

Different strategies were used to deal with the dataset to arrive at a "ground truth" as 3 different radiologists had annotated each image. Only the most successful version is mentioned here in which the annotations from 2 of the 3 radiologists had to agree with averaged out bounding boxes.

---
## References

- **Kaggle Notebook**: [VinBigData-CXR-AD YOLOv5 14 Class train](https://www.kaggle.com/code/awsaf49/vinbigdata-cxr-ad-yolov5-14-class-train?kernelSessionId=52422980)  
- **Original Dataset**: [VinDr-CXR on PhysioNet](https://physionet.org/content/vindr-cxr/1.0.0/)  
- **Smaller Test Dataset (resized 256x256 PNG)**: [VinBigData Chest X-ray Resized on Kaggle](https://www.kaggle.com/datasets/xhlulu/vinbigdata-chest-xray-resized-png-256x256)  

---