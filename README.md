# MeterReading

## This problem is solved in two ways
* [YOLO Darknet](https://github.com/codingnest/MeterReading/blob/hrishi/detection_example.ipynb)
* [YOLO Darkflow](https://github.com/codingnest/MeterReading/blob/hrishi/YOLO_retrain.ipynb)

both having some minor problems as of now

## Darknet Approach-
This is an inference from pretrained weights trained on SVHN dataset
![alt text](https://github.com/codingnest/MeterReading/blob/hrishi/img/darknet.PNG)
problem- Cannot classify the 1st digit (maybe because of glare)
  
## Darkflow Approach-
This is an inference from our custom built model trained on given dataset
![alt text](https://github.com/codingnest/MeterReading/blob/hrishi/img/darkflow.PNG)
problem- Miss classifying some numbers, here miss classifying 9 as 6 (maybe because of small dataset)
