# Boom Bikes Case Study
> This is a case study to build a model which can be used to predict the demand for shared bikes in the American Market for BoomBikes a bike rental company. They want to understand the factors affecting the demand for these shared bikes. We will making use of past data to create the model.

    
## Table of Contents
* [General Info](#general-information) 
* [Technologies Used](#technologies-used) 
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Solving business problem using Linear Regression.
- This is part of our course work at Upgrad ML & AI course.
- The business problem is determining which factors are significant in predicting the demand for shared bikes, and how well do those variables describe the demand.
- The data that is used is the past data for 2 years, 2018 & 2019.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
The equation for the final model is

    cnt = 0.268 + 0.375temp + 0.235yr - 0.160Spring - 0.074(Mist + Clouds) - 0.287*(Light Rain/Snow) - 0.084*holiday

It indicates that the demand, represented by variable cnt, is directly related (goes up as the value of these variables increase) to the temprature and the year (i.e. it was more in 2019 compared to 2018). It is negatively related (goes down as the value for these variables increase) to Spring, holiday, Light Rain/Snow and Mist + Clouds.

The r2_score for this model using the code provided below came to 0.798.

This was the code provided to check the r2_score :

from sklearn.metrics import r2_score
r2_score(y_test, y_pred_m6)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.12.7
- Jupyter notebook 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Resources who worked on this project : Saurabh Gupta 2602.saurabh@gmail.com 


## Contact
Created by [@2602saurabh] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->