# Google-Landmark-Recognition-2020 Kaggle Competition
 ## Table Of Content
   1.[Description](#1) <br>
   2.[Data Preprocessing and EDA](#2)<br>
   3.[Baseline Model](#3)<br>
   4.[Resources](#4)<br>
 ## Description <a id='1'></a> 
   
   Welcome to the third Landmark Recognition competition! This year, we have worked to set this up as a code competition and collected a new set of test images.

Have you ever gone through your vacation photos and asked yourself: What was the name of that temple I visited in China? or Who created this monument I saw in France? Landmark recognition can help! This technology can predict landmark labels directly from image pixels, to help people better understand and organize their photo collections. This competition challenges Kagglers to build models that recognize the correct landmark (if any) in a dataset of challenging test images.

Many Kagglers are familiar with image classification challenges like the ImageNet Large Scale Visual Recognition Challenge (ILSVRC), which aims to recognize 1K general object categories. Landmark recognition is a little different from that: it contains a much larger number of classes (there are more than 81K classes in this challenge), and the number of training examples per class may not be very large. Landmark recognition is challenging in its own way.

In the previous editions of this challenge (2018 and 2019), submissions were handled by uploading prediction files to the system. This year's competition is structured in a synchronous rerun format, where participants need to submit their Kaggle notebooks for scoring.

This challenge is organized in conjunction with the Landmark Retrieval Challenge 2020, which was launched June 30, 2020. Both challenges are affiliated with the Instance-Level Recognition workshop in ECCV’20.
 
 ## Data Preprocessing and EDA (#2) <a id='2'></a>
 Biggest Challenge in this Competition is <b>"contains a much larger number of classes (there are more than 81K classes in this challenge), and the number of training examples per class may not be very large."</b>
 Another challenge Here <b>For quite a lot of classes, there are only 2 images provided in the training set and for most of the classes training samples are less than 100 for that particular class, This means training dataset is highly imbalanced.</b>
 To know more about Image preprocessing and EDA [Click Here](https://github.com/Surekha-honey/Google-Landmark-Recognition-2020-115th-Place-Solution/blob/main/google-landmark-prediction-eda.ipynb)
 ## Baseline Model (#3) <a id='3'></a>
  
"""Baseline kernel for "Google Landmarks Recognition Challenge 2020". 
Please visit [here](https://github.com/Surekha-honey/Google-Landmark-Recognition-2020-115th-Place-Solution/blob/main/google-landmark-recognition.ipynb)

## Resources (#4) <a id='4'></a>
   ### Some of the resources for RANSAC
To knoW more about RANSAC Just go through this [Discussion ](https://www.kaggle.com/c/landmark-recognition-2020/discussion/179472)You will get idea about RANSAC
[The world of RANSAC ](https://www.kaggle.com/c/landmark-recognition-2020/discussion/180921)
