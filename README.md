# VTCA Visual Understanding 
## KerasYoloV3 TrafficTracking (Thuong Huynh)
### Prepare data
#### 1/Install labelme
Follow step-by-step of this Git to install
https://github.com/wkentaro/labelme

#### 2/Begin to label
Create label with exact name [car] [motorbike] and Save .json annotation and image file in respective folder [labels] [images]

[![Labelme Sample](https://github.com/tsuneakihmt/VTCA-VisualUnderstanding-Thuong/blob/master/labelme_sample.png "Labelme Sample")](https://github.com/tsuneakihmt/VTCA-VisualUnderstanding-Thuong/blob/master/labelme_sample.png)

### 3/Convert from labelme JSON to Pascal VOC
Because Keras YOLO V3 required Pasal VOC annotation so we have to convert it.
Please use labelme2voc.py script included in this git to convert labelme JASON to Pasal VOC for Keras YOLO V3.

### Train Data
#### Further instruction is inside the Colab Notebook.
Please download Processed Pascal VOC Dataset here: https://drive.google.com/file/d/1MbeTDfv1lAviFmHz-IxXfskZc6YV1ER6/view?usp=sharing
