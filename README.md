# Real-time-gun-detection
google colab notebook for training gun dataset on yolov4 and detecting gun from image, video and webcam

# Sources
The data is trained with yolov4 of "https://github.com/quangnhat185/darknet_for_colab" which is speacially developed for google colab. for testing images and videos, functions from this repo has been used. however, for gun detection in real time using webcam, functions from this repo "https://github.com/AlexeyAB/darknet" has been used. 

# Link of dataset
https://drive.google.com/drive/folders/1cJ5VoS7NNqRNUwtB8RDwRrKNbbCaUwEq?usp=sharing
structure:
examples- contains some images and videos for testing purposes. 
images- images of guns
labels- labels containing class and bounding boxes. example: 0 0.272917 0.355172 0.537500 0.696552. note: more than one object can be found in one image.
val.txt
train.txt

# Link of yolov4 weights and cfg files for testing
https://drive.google.com/drive/folders/1uiT5Y3xA7xtgXR_j8Hx_xkUAzVxltBAn?usp=sharing
