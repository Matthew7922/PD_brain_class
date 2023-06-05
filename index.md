# Classify PD brain with structural MRI image
a brainhack 2023 project

**A short description of your idea**
Parkinson's disease as the second most neurodegenerative disease worldwide 
is still lack of good neuroimage biomarker. The diagnosis is still mostly based on clinical features. Although we would performed basic structural MRI image with T1 sequence clinically, there's still lack of obvious feature to assist the identification of Parkinson's disease. Not to mention further predict or pick-up the prodromal subjects.
My project aims to extract the features from the Parkinson's disease T1 sequence via principal component analysis and independent component analysis. After extraction of the features, the features would further put into machine learning model to train a classification model. I would test the performance between supported vector classifier and Random Forest Classifier. 

**Hub of the project**
Taiwan hub

**Goals of your project**
* Explore the structural features of PD brains
* Established a classification models by machine learning method

**Data and Tools to use**
* Data from Parkinson Progression Marker Initiatives (PPMI)
* Preprocessing: SPM12 (CAT12) for normalization and segmentation
* Feature extraction & Machine Learning: python sklearn, numpy package