---
title: "How Safe is Safe Enough"
Date: 2021-10-05
categories:
  - Blog
tags:
  - Injury Biomechanics
  - Safety Engineering
  - HIC Score
---

There are many different organisations which evaluate vehicle safety, such as the New Car Assesment Programme <a href="https://www.globalncap.org/ncaps" target="_blank">(NCAP)</a> which opperates internationally, The Insurance Institute for Highway Safety <a href="https://www.iihs.org/ratings" target="_blank">(IIHS)</a>  which is a US non profit organisation or The National Highway Traffic Safety Administration <a href="https://www.nhtsa.gov/ratings" target="_blank">(NHTSA)</a> which is a department of the US government.

These organisations score and rank vehicles on their safety preformance across many different areas. These areas include both occupant safety and pedestrian safety. The results of these tests all point towards the same thing, <a href="https://www.nhtsa.gov/newer-cars-are-safer-cars" target="_blank">cars are getting safer</a>.
In this post I will be looking at what it takes to get these high safety scores in terms of head impacts and to answer the question of *how safe is safe enough*.

<p align="center">
  <img src="/assets/images/Dummy_Crash1_Gif.gif" width="700">
</p>


## Head Injury ##
An Abriviated Injury Scale (AIS) was developed by emergency room physicians to quantify the severity of injuries to specific body parts such as the head. These range from AIS1 which is a minor head injury to an AIS5 which is a critical head injury.

|    AIS   |   Severity |
|----------|:----------:|
|    1     |  Minor     |
|    2     |  Moderate  |
|    3     |  Serious   |
|    4     |  Severe    |
|    5     |  Critical  |

A common metric which can be used in determining the risk of such injuries is called the Head Injury Criterion or HIC. The Hic score is a measure of the likelihood of a head injury due to an impact. It is derived from the maximum acceleration in g's experienced by the head during a very small time window. This is usually calculated during a test by using accelerometers placed inside the crash dummies head. The standard time window t2-t1 is 15ms and can reach a maximum of 32ms. The higher the HIC score the higher the likelihood you will experience a head injury. As shown in this graph from <ahref="https://www.annualreviews.org/doi/abs/10.1146/annurev.bioeng.9.060906.151946" target="_blank">Foresnic Injury Biomechanics</a>, a HIC score of 1000 equates to roughly a 60% risk of an AIS3+ (serious) head injury or just under 20% chance of a critical head injury. 

<p align="center">
  <img src="/assets/images/HIC_Equation.PNG" width="700">
</p>

<p align="center">
  <img src="/assets/images/HIC_Risk_Graph.jpg" width="700">
</p>


## Vehicle Safety Assessment ##
There will always be some amount of risk to head injury in a collision with a car. It would be unreasonable to think that we can a human head colliding with a moving car with a 0% risk of head injury. However now that we know how HIC scores are related to injury risk lets take a look at the maximum HIC scores needed to achieve a high safety rating. In other words how much risk is considered an acceptable amount by vehicle safety organisations. 

**EUNCAP Head Impactor**
<p align="center">
  <img src="/assets/images/EUNCAP_Head_Impactor.png" width="700">
</p>

The above graphic from the European New Car Assesment Programme's  <a href="https://www.euroncap.com/en/vehicle-safety/the-ratings-explained/vulnerable-road-user-vru-protection/head-impact/" target="_blank">website</a> shows a head impactor test. This is when a dummy head strikes the surface of the vehicle and a HIC score is calculated from internal accelerometers. For EUNCAPS's car assesments, the surface of the vehicle is divided into grid squares. The car manufacturer provides EUNCAP with a prediction of the HIC scores that would be experienced from a head impact in each of the grid squares. EUNCAP then preforms these head impactor tests on a random sample of squares and compares their test results to the predicted HIC scores. A tolerance of 10% is given to account for modelling or prediction errors. From this information a correction factor is calculated and applied to the untestested grid squares. Each square is then given a score between 0-1 depending on the HIC score at that location. The sum of all of these grid squares is then used to give a final score. 

This is far from a simple proceedure but in summary, the manufacturer estimates the HIC score a human head would experience impacting different points along the cars surface. EUNCAP then tests a random sample of these impact locations to validate the prediction and calculate a correction factor if needed. A HIC score is determined at every location. A score of between 0-1 depending on the HIC is given to each location. These scores are all added together to give a total score for the car. 

The range of allowable HIC scores is shown below. 

|    Colour   |      HIC Range     |  Score  | Risk of Severe (AIS4+ Injury) |
|-------------|:------------------:|:-------:|:-----------------------------:|
|    Green    |        HIC < 650   |    1    |              5%               |
|   Yellow    |  650 < HIC < 1000  |   0.75  |              20%              |
|   Orange    |  1000 < HIC < 1350 |   0.5   |              40%              |
|   Brown     |  1350 < HIC < 1700 |   0.25  |              85%              |
|     Red     |  1700 < HIC        |    0    |             >85%              |
