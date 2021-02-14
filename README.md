# Yolov4
## Training on YOLOv4
1. Training file is [Yolov4](https://github.com/sourabhx003/Yolov4/blob/main/Yolov4.ipynb)
1. Training using the pretrained weights on COCO dataset.
2. Used pre annotated data since it was easily available.
3. Last loss war 2.5 avg loss it can be reduced to lower.
4. Model weigths are [link.](https://drive.google.com/drive/folders/1L87zOMDeVRTnKUc1FCudaJBGVXb4gNAv?usp=sharing)
5. Inference file is [YoloDetection](https://github.com/sourabhx003/Yolov4/blob/main/YoloDetection.ipynb)
6. Used a solo image not a video just because cv2 crashes colab. trying with video with pathces, you can do it.
7. There are four classes 
  * F -------> Face
  * H & M---> Helmet and Mask
  * M -------> Mask
  * H -------> Helmet
### All the requirements are given but be sure while inference use OpenCV > 4.4.0
