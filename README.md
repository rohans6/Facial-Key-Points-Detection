# Facial-Key-Points-Detection
The objective of this task is to predict keypoint positions on face images. This can be used as a building block in several applications, such as:
* tracking faces in images and video
* analysing facial expressions
* detecting dysmorphic facial signs for medical diagnosis
* biometrics / face recognition
* Detecing facial keypoints is a very challenging problem.  Facial features vary greatly from one individual to another, and even for a single individual, there is a large amount of variation due to 3D pose, size, position, viewing angle, and illumination conditions. Computer vision research has come a long way in addressing these difficulties, but there remain many opportunities for improvement.

# Augmentations:-
Used different augmentation techniques. The Critical part was to compute facial keypoints when image is augmented. 
1. Rotation:-

[d](Rotation.png)


# Root Mean Squared Error (RMSE)
Submissions are scored on the root mean squared error. RMSE is very common and is a suitable general-purpose error metric. Compared to the Mean Absolute Error, RMSE punishes large errors:


where y hat is the predicted value and y is the original value.

# Link of Competition
https://www.kaggle.com/c/facial-keypoints-detection/overview/evaluation
