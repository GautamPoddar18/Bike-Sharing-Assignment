# Bike Sharing Case Study
> Required to model the demand for shared bikes with the available independent variables


## Table of Contents
* [Problem Statement] 
* [Business Goal]
* [Conclusions]
* [Contact] 

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Business Goal
We  required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Conclusions

### We can see that the equation for best fitted line is:
cnt = 0.2462 x yr + 0.0541 x workingday + 0.0436 x summer + 0.0862 x winter + 0.0587 Saturday + 0.0097 x August + 0.116 x September - 0.2370 x windspeed - 0.3149 x Light snow - 0.0951 x Mist cloudy - 0.1696 x December - 0.2075 x Feburary - 0.2782 x January - 0.1170 x November
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

For Numberical Value: Demand decreses if increase in windspeed

Demands increases in workingday, summer, winter, Saturday, August, September

Demand decreases in Light snow, Mist cloudy, December, Feburary, January, November

r2 scorce 0.728

#### top features explaining cnt are:
- weather situation(Light snow) -0.3149
- year (0: 2018, 1:2019) 0.2462
- windspeed -0.2370

## Contact
Created by [@GautamPoddar18] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
