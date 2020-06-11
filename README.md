## **Dataset**

This dataset was adapted from the paper: "House price estimation from visual and textual features"
https://arxiv.org/pdf/1609.08399.pdf

H. Ahmed E. and Moustafa M. (2016). House Price Estimation from Visual and Textual Features.In Proceedings of the 8th International Joint Conference on Computational Intelligence (IJCCI 2016)ISBN 978-989-758-201-1, pages 62-68. DOI: 10.5220/0006040700620068

## **Details**

Houses Dataset

Description:  This is a benchmark dataset for houses prices that contains both visual and textual information. Each house is represented by four images for bedroom, bathroom, kitchen and a frontal image of the house. The dataset folder contains 2140 images, 4 images for each house. Also, it contains a text file that contains the textual metadata of the dataset. Each row in the file respesents the number of house in order. The numbers represent number of bedrooms, number of bathrooms, area of the house, zipcode and the price. Feature extraction was performed on the zipcode feature to include additional demographic variables from the American Community Survey from 2016.

## **Analysis**

This analysis focused on using convolution neural networks to predict house prices from the images assembled in the dataset. In addition, dense networks were constructed to examine the textual features present and evaluate their ability to predict house price as well. These networks were then combined in multiple ways to evaluate the ability of image and textual features in predicting house prices. For comparison purposes, traditional machine learning methods, inclduing decision trees, random forest, boosting, and SVMs, were used to predict house prices based on the textual features. A further step with this dataset could include using image feature extraction techniques such as SIFT and SURF.

## **Files**

The full dataset with extracted features can be found as described above. 
House_Deep_Learning_Analysis.ipynb is the iPython notebook contains the neural network analysis 
Trad_ML_Analysis.py is the script for traditional ML methods including multiple feature selection types
