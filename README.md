# Q1.2-CDS
Write up for Q1.b : Traffic Sign recognization

## Phuong phap 1: Su dung model tensorflow : object_detection 

Em lam theo huong dan trong bai viet nay : [MacnCheese detector](https://pythonprogramming.net/introduction-use-tensorflow-object-detection-api-tutorial/)

Su dung [labelImage](https://github.com/tzutalin/labelImg) danh dau lai vi tri cua 1 bien No-entry

Do kha nang xu ly cua laptop co han nen em thu train model chi voi 1 class la No-entry sign
sua batch size tu 32-8 , sau 8000 steps total loss khong kha quan lam 
![training loss](https://github.com/Luvata/Q1.2-CDS/blob/master/loss.jpg)

30/10 em co muon laptop de train, nhung tensorflow update moi co conflict [issue#2652](https://github.com/tensorflow/models/issues/2652)

## Phuong phap 2: Su dung [YOLO](https://pjreddie.com/darknet/yolo/)

Em lam theo huong dan tu folk darknet cua [AlexeyAB/darknet](https://github.com/AlexeyAB/darknet#how-to-train-to-detect-your-custom-objects)

