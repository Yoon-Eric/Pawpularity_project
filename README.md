# Pawpularity_project
In this project, I've made a machine learning model that can predict if a photo of a homeless animal is attractive or not attractive enough to find a new owner.
I used a public [dataset](https://www.kaggle.com/competitions/petfinder-pawpularity-score/data) from Kaggle
First, I used a modified VGG-16 classifier to extract features from images. Then, using the extracted features from the images (1000 numerical values) and the statistics provided from the [website](petfinder.my), I trained a SVM classifier.
Also using 13 human-labelled features of each images that the website also provided, I trained another SVM classifier and compared the results

View the Pawpularity.pdf to see my poster for this project
