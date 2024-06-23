United States of America Health Insurance Price Predictions

Version 1.0

------------------------------------------------------------------------------

README CONTENTS
0.1 Contact Information

1.0 Release Contents
1.1 Introduction
1.2 Acknowledgements
1.3 Rights Information
1.4 Requirements for Running the Project
1.5 Data Tables
1.6 Contributing
1.7 Revision History

------------------------------------------------------------------------------
0.1 Contact Information

Name:                Email
Precious Orekha	     poo27@drexel.edu
Nana Afua Martinson  nsm86@drexel.edu
Nakol Bennam	     nb3286@drexel.edu
------------------------------------------------------------------------------
1.0  Release Contents

The contents of this project is listed below 
   readme.txt
   insurance2.csv

Additionally, Python Notebooks associated with the analysis are  
included.

------------------------------------------------------------------------------
1.1 Introduction
This project focuses on developing and evaluating a machine learning model that uses data collected from Kaggle to predict health insurance cost across regions in the United States based on attributes such as Age, Sex, BMI, Number of Children, and Smoking History. 

Subsequently, we used metrics such as mean squared error, root mean squared error and R^2 score to evaluate the performance of our models.
------------------------------------------------------------------------------
1.2 Acknowledgements

This project is a collaborative effort of Precious Orekha, Nana Afua Martinson and Nakol Bennam. This was done to satisfy their class project requirement for DSCI 631  at Drexel University in the Spring 2024 class. 

Each member was responsible for contributing to various sections of the project. 

The work was divided according to individual strengths and interests. Precious was responsible for combining all models in the Python Notebook, Nana was responsible for the Read me document, Nakol was responsible for the final presentation. We each worked on all models individually and chose the best models among us.
------------------------------------------------------------------------------
1.3 Rights Information

Site: https://www.kaggle.com/datasets/teertha/ushealthinsurancedataset/data

This dataset contains 1338 rows of insured data, where the Insurance charges are given against the following attributes of the insured: Age, Sex, BMI, Number of Children, Smoker and Region. There are no missing or undefined values in the dataset.

------------------------------------------------------------------------------
1.4 Requirements for Running the Project

This analysis was done in a Python 3 environment. Specifically, the
Anaconda and Jupyter Notebook environment using the following packages:

pandas
numpy
sci-kit learn
matplotlib
seaborn

It is recommended to import the data into your environment from the
provided data file and begin analysis from there. For Python 3 we recommend
importing the CSV as a pandas dataframe. 

To run the notebook, execute the cells in sequence. The main steps include:

- Data Loading and Preprocessing: Ensure your dataset is correctly formatted and loaded.
- Exploratory Data Analysis and Data Wrangling: This is done to ensure high quality of the dataset and also get an understanding of the data.
- Model Definition: Define the models intended for use
- Training the Model: Train the model and tweak the hyper parameters to obtain the best results.
- Evaluating the Model: Use the provided metrics to measure the model’s performance on unseen test data.

------------------------------------------------------------------------------
1.5 Data Tables

This dataset contains 1338 rows of insured data, where the Insurance charges are given against the following attributes of the insured: Age, Sex, BMI, Number of Children, Smoker and Region. The attributes are a mix of numeric and categorical variables.
There are no missing or undefined values in the dataset.

This remainder of this section describes each attribute of the dataset in detail and the fields that each contains

age: Age of primary beneficiary
sex: Insurance contractor gender, female / male
BMI: Body mass index, providing an understanding of body, weights that are relatively high or low
children: Number of children covered by health insurance / Number of dependents
smoker: Smoker / Non - smoker 
region: The beneficiary's residential area in the US, northeast, southeast, southwest, northwest
charges: Individual medical costs billed by health insurance

------------------------------------------------------------------------------
1.6 Contributing

If you wish to contribute to this project, please fork the repository and create a pull request with your changes. Ensure your code adheres to the existing style and include appropriate tests.

------------------------------------------------------------------------------
1.7 Revision History

     Version      Date            Comments
       1.0      June 2024     Initial release for DSCI 631 class project   

------------------------------------------------------------------------------

<end of file>
	