#### Introduction
In this project ,we will be using dataset from UCI machine learning repository/ for classification of bank note as fake or genuine.

The dataset contain 1372 rows with 5 columns.

#### Machine Learning models used: 
* Logistic Regression * Support Vector machine 
* Random Forest Classifier * Knearest Neighbors Classifier

#### Data set Information
Data were extracted from images that were taken from genuine and forged banknote-like specimens.
For digitization, an industrial camera usually used for print inspection was used. The final images have 400x 400 pixels.
Due to the object lens and distance to the investigated object, gray-scale pictures with a resolution of about 660 dpi
were gained. Wavelet Transform tool were used to extract features from images.

#### Data set columns/attributes
variance of Wavelet Transformed image (continuous)
skewness of Wavelet Transformed image (continuous)
curtosis of Wavelet Transformed image (continuous)
entropy of image (continuous)
class (integer)
Class : 1 => Genuine
Class : 0 => Fake
