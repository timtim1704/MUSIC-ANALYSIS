# MUSIC-ANALYSIS
# ABSTRACT: 
Song recommendations have existed for a long time, but in majority of the scenarios the recommendation is determined after learning the user preferences over a period of time, like looking at his past song preferences, time he listens to the music etc.
In this paper we propose a new approach to song recommendation, where in the mood of a person is determined from his picture and based on the mood predicted song recommendations are made that best suit the mood predicted.

# DESCRIPTION:
We first process the image of the user taken as an input with the help of a python library for Computer Vision called 'OpenCV'. This captured image is then made available for the CNN in combination with DNN to make a prediction whether the current mood of the user is 'Happy' or 'Sad'.
The second part is the usage of Unsupervised Machine Learning techniques for clustering songs.The songs are clustered as either of the two classes-'VERY ENTERTAINING'(class 0) and 'RELAXED'(class 1) using the popular K-means algorithm. Then the recommendation is made in order of the current popularity of the respective songs.
We have an unique story in the way we recommend the songs for each mood, for example when other sites recommend sad songs when a person is sad or feeling bad, we recommend users with songs which will cheer them up('VERY ENTERTAINING') and 'RELAXING' songs when they are 'HAPPY'.

# LIBRARIES USED:
OpenCV.
Tensorflow and Keras.
Sklearn.
LightGBM.
Spotipy.
Tkinter.
Pillow.
