# MIE1517-Project-Nutrition-Predictor
Final Project for the course MIE1517H: Introduction to Deep Learning, Winter 2026

## Files:
- ### MIE1517H_Project
  - The main project file, submitted as both an ipynb and html file 
- ### feature_extraction.ipynb
  - Uses a ResNet152 model pre-trained on the [Food-2K](http://123.57.42.89/FoodProject.html) dataset (provided [here](https://github.com/Liuyuxinict/prenet)) with the last layer removed and computes 2048-dimensional features from the [Food-100K](https://huggingface.co/datasets/Codatta/MM-Food-100K) dataset.   
- ### Feature_Augmented_Test.ipynb
  - File for performing testing on augmented image set
