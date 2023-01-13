# Determinants of GDP

## Project Description

This projct aims to analyze the impact of socail and economic factors, using econometric and machine learning models, on GDP growth rate per capita. We used the World Bank Open Data to obtain data on various scoail and economic metrics on the Latin America and Carribean region.  We studied the impact of these factors on economic growth (GDP growth rate per capita) from 1993 to 2019. Additionally, we used the econometric and machine learning models to forecast future gdp growth rate per capita.  

## Background

Social factors like increased access to electricity, literacy rate or primary school enrollment can have a significant impact on the economic development of a country or region; however, it can prove challenging to quantify the specific economic impact of these socail factors. Our study aims to quantify the impact of these social factors on the economic development in the Latin America and Carribean regions, measured using the proxy variable of GDP growth rate per capita. We hypothesize that growth in these factors will have a positive impact on the economic development of the Latin America region. Other studies and literature on this topic support a similar opinion. For example,  Gerry Gatawa, in his paper *The Effect of Social Factors to Economic Growth*<sup>1</sup>, said that "Social factors are great drivers of economic growth and it could result to tangible benefits that can trigger sustainable development". Gatawa's "study calls for a paradigm shift among economists, public administrators, and finance managers to view social expenditures as investments that could guarantee sustainable economic growth and development"<sup>1</sup>.     

## Notebooks

Multi-Variable Linear Regression Analysis

Neural Networks Regression Analysis

Data Visualization 

## Data

### Dependent Variable:

* **GDP per Capita Growth (Annual %):**
Annual percentage growth rate of GDP per capita based on constant local currency. GDP per capita is the gross domestic product divided by the midyear population. We are using GDP at purchaser's prices, which is the sum of the gross value added by all resident producers in the economy, plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets, or for depletion and degradation of natural resources.

### Independent Variables:

* **Access to Electricity (% of Population):**
This variable is measured as the percentage of the population with access to electricity. Electrification data are collected from industry, national surveys and international sources.

* **Labor Force Participation Rate(% of Population - National Estimate):**
Labor force participation rate is the proportion of the population that is economically active: all people who supply labor for the production of goods and services during a specified period. For our dataset, we will be including males/females (15-24 years old). Each variation will have its own data, meaning that we have two different independent variables for Labor Force Participation Rate.

* **Literacy Rate (% of Population):**
Literacy rate is the percentage of people within our measured population who can both read and write, while understanding a short simple statement about their everyday life. For our dataset, we will be including youth males/females (15-24 years old), and adult males/females (15 years and older). Each variation will have its own data, meaning that we have four different independent variables for Literacy Rate.

* **People Using at Least Basic Drinking Water Services (% of population):**
This variable encompasses both people using basic water services, as well as those using safely managed water services.  Basic drinking water services is defined as drinking water from an improved source, provided collection time is not more than 30 minutes for a round trip.  Improved water sources include piped water, boreholes or tubewells, protected dug wells, protected springs, and packaged or delivered water.

* **Life Expectancy at Birth (Years):**
Life expectancy at birth indicates the number of years a newborn infant would live, if prevailing patterns of mortality at the time of its birth were to stay the same throughout its life. For our dataset, we will be including males and females. Each variation will have its own data, meaning that we have two different independent variables for Life Expectancy at Birth.

* **Net Migration (Persons):**
This variable is the measure of the net total of migrants during the period; The number of immigrants minus the number of emigrants, including both citizens and noncitizens.

* **School Enrollment, Primary (% Net):**
Net enrollment rate is the ratio of children of official school age who are enrolled in school to the population of the corresponding official school age. Primary education provides children with basic reading, writing, and mathematics skills along with an elementary understanding of such subjects as history, geography, natural science, social science, art, and music.

## Models

**Multi-Variable Linear Regression:**

GDP Growth Rate Per Capita(%) = 
                                𝛽0 + 𝛽1 [Access to Electricity] + 𝛽2 [Literacy Rate(Adult Female)] + 𝛽3 [Literacy Rate(Youth Female)] + 
                                𝛽4 [Literacy Rate(Adult Male)] + 𝛽5 [Literacy Rate(Youth Male)] + 𝛽6 [Life expectancy at Birth(Female)] + 
                                𝛽7 [Life expectancy at Birth(Male)] + 𝛽8 [Primary School Enrollment] + 𝛽9 [Labor Force Participation (Female)] + 
                                𝛽10 [Labor Force Participation (Male)] + 𝛽11 [Net Migration] + 𝜎t + g + 𝜖j,t,g                      

**Neural Networks (Supervised Learning)**


## Results 





## Libraries

* Python
* Pandas
* Numpy
* Scikit Learn
* Conda
* Hvplot
* Matplotlib
* DateTime


## *Authors*:
- **Brandon Latherow** - [LinkedIn](https://www.linkedin.com/in/brandon-latherow-4703a9214/) | [Github](https://github.com/brandonlatherow)
- **Samuel Farrell** - [LinkedIn](https://www.linkedin.com/in/samuelcfarrell/) | [Github](https://github.com/SamCFarrell)
- **Sami Naeem** - [LinkedIn](https://www.linkedin.com/in/sami-naeem/) | [Github](https://github.com/SZun)


## References 

1) GATAWA, GERRY (2022): The Effect of Social Factors to Economic Growth. Advance. Preprint. https://doi.org/10.31124/advance.19397081.v1 




