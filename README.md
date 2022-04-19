# Pawpularity_project
In this project, I've made a machine learning model that can predict if a photo of a homeless animal is attractive or not attractive enough to find a new owner.
I used a public [dataset](https://www.kaggle.com/competitions/petfinder-pawpularity-score/data) from Kaggle
First, I used a modified VGG-16 classifier to extract features from images. Then, using the extracted features from the images (1000 numerical values) and the statistics provided from the [website](petfinder.my), I trained a SVM classifier.
Also using 13 human-labelled features of each images that the website also provided, I trained another SVM classifier and compared the results.

View the Pawpularity.pdf to see my poster for this project.

Work after the presentation--

I tried using a modified CLIP to extract 512 features from the images (just like what I did with VGG-16) and tried using SVM with it (work in the Pawpularity_SVM.ipynb).

Next goal for this project: Once I get a GPU, I'm going to try training my own neural network (architecture based on ResNet or EfficientNet) to make a regressor predicting the pawpularity score.
