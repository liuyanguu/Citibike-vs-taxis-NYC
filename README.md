# BigDataTaxisNYC
Final Project for Big Data - ds 1004 with Dr. Juliana Freire.

## Team members

* Michelle Ho - mmh555
* Jiheng Huang - jh5138
* Sara Arango Franco - saf537


## Description

Map-reduce implementations in hadoop to calculate the difference in average travel times in taxi and Citi Bike between zip codes where the comparisons make sense (i.e. zip codes where there are Citi Bike stations). We wanted to test the hypothesis that there is a threshold below which it is faster to ride a Citi Bike in New York City than to take a taxi. This threshold may vary (or not exist) depending on conditions such as day of the week and time of the day. We compared three categories:
* Total trips.
* Weekdays in rush hour versus non rush hour.
* Saturday mornings versus Saturday nights.

Our main finding is that in average, the longer the distance of the travel, the faster it is to take a Citi Bike. This is biased by to factors: the fact that most trips are done in rush hours, and the fact that the longest Citi Bike trips involve the crossing of a bridge (Manhattan, Brooklyn or Williamsburg). 

## Data sources:

* Citi Bike system data: January, May and September of 2015.
* TLC yellow cab data for the same periods described above.

![HW1_1](https://github.com/sarangof/BigDataTaxisNYC/blob/master/plots/Total.png) 

Total time difference.

![2](https://github.com/sarangof/Citibike-vs-taxis-NYC/blob/master/plots/nonRush_difference_detail.png)

Non rush hour

![3](https://github.com/sarangof/Citibike-vs-taxis-NYC/blob/master/plots/Rush_difference_detail.png)

Rush hour


For more information regarding methods and results, please refer to: https://docs.google.com/document/d/1rCXrWBu7yBdaN905Gg6dNiYEn9mB1As-vGPwrrS726k/edit?usp=sharing

