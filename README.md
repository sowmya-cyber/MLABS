# IDENTIFYING MAPPING VARIATION USING RBF BASED LINEAR SQUARE METHOD

This repository contains the code that finds the variations in ground surface using RBF based linear square method

Execution environment - Google Colab.

Dataset- Upload the ex_dataset (1) file in Google Drive and paste the path for the execution.

The main code is uploaded in MLABsios.ipynb.The comment is included in the document named COMMENTS.docx

For evaluation purposes, the regression algorithms are considered. The project aims to find the MSE rate 

 Preprocess the dataset- Handle the missing values by means of mean imputation and minmax normalization is used

Least square regression is performed and the error rate is computed. Then it compared with RBF based least square method.Here by increasing the basis functions we are actually mapping the data from lower dimension to higher dimension which helps to find the best fit plane 

The final outcome is to compute the error rate

