# What were the predictors of voter behavior in the 2016 Presedential Election in Virginia?
A collaborative project for Linear Programming at Georgetown University

Statistical analyses can identify insights into the voter behaviors from the 2016 Presidential election results in Virginia.
Some of the questions we sought to answer were
- Is the average median income different for counties who voted for Donald Trump than for counties who voted for Hillary Clinton?
- Are educational attainment and racial makeup statistically significant predictor variables for which candidate the county voted for?
- What, if any, are the correlations among the predictor variables?
- Is the percent of unemployment among the counties statistically significant in determining which candidate they voted for?
- Is the average median age in years per county different in the counties that voted for Trump than in the counties that voted for Clinton?

To answer these questions, we took information from Politico (for election results), from the American Community Survey (for voter information) and from manually created data.

To model the success of Trump in a county, we used the following model: Percent.Trump ~ Percent Third + Median.Income + Median.Age + Percent.White + Unemployment.Rate + Graduate

Some counties were clear outliers:
![va_outliers](https://github.com/mathyjokes/VA-2016-Election-Results---Math651/blob/master/va_outliers.png)

For other results check the PPT presentation!
