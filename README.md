# BoomBikes Sharing - Linear-Regression-Assignment


## Table of Contents
* [General Info](#general-information)
* [Analysis Steps](#analysis-steps)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Analysis Steps
* Data Understanding
  * Reading Data
  * Data Visualization - Numerical and Categorical Features
* Data Preparation
  * Derived Features
  * Handling Categorical Features
  * Dummy Variables
  * Data Split - Train & Test
  * Min/Max Scaling
  * Feature Correlation
  * Drop non-sigbificant features
* Model Creation
  * Recursive Feature Selection
    * Check Feature Significance
    * Check VIF 
    * Clean Features
  * Repeat previous Iteration till Stable Model
* Residual / Error Term Analysis
* Prediction and Model Evaluation  

## Conclusions
a. Temp is the most significant feature with positive impact on Bike business.
b. Year shall be showing the business linearity for YoY growth.
c. Weather conditions / Season (Spring, Mist, Snow) has negative impact on Bike business.
d. Company shall identify ways to tackle weather conditions to mimimize the seasonal business impact.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Sklearn
- StatsModel

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- Live session on Linear Regression conducted by IIITB.
- Live Handson Linear Regression session conducted by upGrad.
- Resposnes provided in Daily Doubt Resolution sessions conducted by upGrad.
- Course content in upGrad Linear Regression.


## Contact
Created by [@umeshg1981](https://github.com/umeshg1981) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->