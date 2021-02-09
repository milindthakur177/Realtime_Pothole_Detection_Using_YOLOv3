# Realtime_Pothole_Detection_Using_YOLO
them 
The Dataset is from kaggle : https://www.kaggle.com/chitholian/annotated-potholes-dataset .

For the project the dataset annotations are converted for YoloV3_Darknet format using Roboflow

Steps After converting the annotations :
1. Make Zip file of all the dataset and save it in pothole_detection folder
2. Run Training_model.py program for training weights.
3. After 2000 iterations, 3 files will be obtained : classes.txt, yolov3_testing.cfg, yolov3_training_last.weights. Put them in same folder as Object_Detection.py program.
4. Run Object_detection.py program.
