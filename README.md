# AUTOMATIC LICENSE PLATE DETECTION

This project proposes a method for the detection and identification of vehicle number plate that will help in the detection of number plates of authorized and unauthorized vehicles. This project presents an approach based on simple but efficient morphological operation and an edge detection method. This approach is simplified to segment all the letters and numbers used in the number plate by using bounding box method. 

## Dataset used:
OpenCV provides many training method (Cascade Classifier Training) or pretrained models. The dataset used here is an .xml file from harr cascade model which is cascade of classifiers and can detect license plates. Each file in the dataset contains trained machine learning models for detecting Russian license plates in images. This information includes the size of the detection window, the number of stages in the cascade, and the features used to detect the license plate.

The project script is tested on various pictures and was successful with certain pictures that were available under certain dimension frames. The project extracts the number plate from the car image and displays it separately and saves it in a folder 'Scanned'

