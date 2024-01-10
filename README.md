# Project Name
> Bike Sharing Assignment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The equation for target variable - cnt=0.146943 + 0.511635atemp -0.144919windspeed + 0.092692season_summer + 0.117796season_winter + 0.235150yr_2019 + 0.065359month_Aug -0.047622month_Jan + 0.11461month_Sep + 0.021636weekday_Sat -0.274668weathersit_Light Rain -0.079622* weathersit_Mist

- Comparision between Training and Testing dataset:
  
  Train dataset R^2 : 0.828
  
  Test dataset R^2 : 0.79


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas - version 2.0.3
- NumPy - version 1.24.3
- Seaborn - version 0.12.2
- MatplotLib - version 3.7.2
- Jupyter Notebook 6.5.4

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->
