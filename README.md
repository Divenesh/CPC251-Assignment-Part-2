# Machine-Learning Model

<p align="center"><i>We wanted to find the best feature selection method and create model for best prediction.</i></p>


## Introduction

<p> Feature selection is the process of reducing the number of input variables when developing a predictive model. It is desirable to reduce the number of input variables to both reduce the computational cost of modeling and, in some cases, to improve the performance of the model. Statistical-based feature selection methods involve evaluating the relationship between each input variable and the target variable using statistics and selecting those input variables that have the strongest relationship with the target variable. These methods can be fast and effective, although the choice of statistical measures depends on the data type of both the input and output variables. As such, it can be challenging for a machine learning practitioner to select an appropriate statistical measure for a dataset when performing filter-based feature selection.  </p>


## Aim

<p> In this Assignment, some data of the cars are given which are mpg, cylinders, displacement, horsepower, weight, acceleration, model_year, origin and car_name. Our goal is to find the best feature selection method and to create the model for the best prediction. </p>


## Feature Selection
In this experiment there are total of 9 features and 398 records. It is computationally expensive to build, train and test models with 9 features. Hence, to reduce the feature space we have performed feature selection to select relevant features in building the machine learning model. However, there are some data cleanings has been carried out before selecting the features.
<ol> 
  <li>Data Cleaning</li>
    <ul>
      <li> Firstly, we check for the basic information about the dataset provided. We managed to sort all the information in correct manner and analyze the info such as number of columns and rows (features and records) </li>
         <img src=" "/>
      <li>Secondly, we have checked for the any of the missing values. We found there is no any missing values in the data. </li>
         <img src=" " />
    </ul>
 </ol>
