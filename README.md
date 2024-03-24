#### Voting-Data-Analysis-For-UK-2018-ESS
##### find data on website of the European Social Survey (ESS).

##### library(tidyverse)
##### library(haven)
##### library(nnet)
##### library(broom)
##### library(modelr)
##### library(modelsummary)
##### library(kableExtra)
##### library(ggplot2)
##### library(scales)
[Assignment_3_by_Yiqiu_Wang.pdf](https://github.com/Yiqiu-W/Voting-Data-Analysis-For-UK-2018-ESS/files/14735817/Assignment_3_by_Yiqiu_Wang.pdf)

##### study party vote choice in the 2017 UK parliamentary election. 
##### Change the party vote variable into a factor and recode it so that it has the values Conservative, Labour, Liberal Democrats, and others. Next analyze the relationship between party choice and whether respondents viewed immigration as good or bad for the country’s economy. Use two multinomial models: One where you include sex, age and educational attainment as the regressors, and a second where you add respondents’ views on immigration as an additional independent variable. Dichotomize the education variable so that those with lower or higher tertiary education are coded 1 and all others are coded 0. In both models, party vote should be the dependent variable, with Conservative treated as the reference category.
