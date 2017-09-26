# Vehicle-Detection

In this project, the goal is to write a software pipeline to identify the vehicles in a video from a front-facing camera on a car. This can be achieved by the following steps:
1. Load data of vehicle images and non-vehicle images and train a classifier which would later be used to identify vehicles in a video. Split the available image set into a 0.8:0.2 ratio of training and test data.
2. As part of extracting the desired set of features from a set of labeled data, perform a HOG (Histogram of Oriented Gradients) extraction and train a Linear SVM (Support Vector Machine) classifier.
3. Perform a sliding window technique and identify vehicles in images.
4. Build a heat-map from the detections in order to combine overlapping detections and remove false positives.
5. Run the pipeline on a video and check whether the vehicles are being identified by rectangles.

See write-up for complete report.
