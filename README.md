# academic_project_squat_classification
**A Computer Vision based solution in fitness domain.**

Fitness is a field where computer vision can solve real world concerns. It has immense potential to impact the fitness industry.
One way the field can be revolutionised is by using Compuer Vision to give feedbacks to the exercise doers.

This project is a squat classifier which works on real time video data. It classifies the squat performed by user into one of the seven classes to generate relevant feedback to the user. 
The solution uses bodily keypoints, extracted by a pose estimator model which is Blaise Pose of Mediapipe framework. These primary features are processed to extract more robust, independent features in form of temporal distance matrices. 
Classifier is a Resnet-34 model which has been modified to use 1 dimensional convolutions.
Note that you can find relevant ipython notebooks.
The deployment is still under process and will be uploaded once completed.
I have attached a detailed write up about this academic project in which I corroborations related to the performance and solutions to some inherent issues related to the 
problem at hand, are mentioned.
**This academic project is part of my PG Diploma under University of Hyderabad in AI and ML.**
