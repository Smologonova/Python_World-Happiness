# World-Happiness

An open-source data project using Python and Tableau to explore trends in happiness and determine which factors contribute the most to a country’s happiness score as a part of Data Analytics course at CareerFoundry.

## Scenario
To find an open-sourced data set and analyze, with the goal of conducting an exploratory visual analysis in Python and finding connections between variables that seem worth exploring. After developing hypotheses, various advanced analytical approaches should be used to help testing the hypotheses.

The World Happiness Report is a landmark survey that measures and ranks the happiness of individuals in 158 countries around the globe. Happiness is increasingly considered an important and useful way to guide public policy and measure its effectiveness. 
The World Happiness Report 2015 was launched by the Sustainable Development Solutions Network (SDSN). The World Happiness Report 2017 was released at the United Nations at an event celebrating International Day of Happiness on March 20th.

## Objective
To explore trends in happiness and determine which factors contribute the most to a country's happiness score.

## Data 
Open source data: the World Happiness Report, which is a survey that ranks participating countries based off of their overall happiness available [here](https://www.kaggle.com/datasets/mathurinache/world-happiness-report)


## Data Collecting
The World Happiness Report uses data from the Gallup World Poll survey based on answers to the main life evaluation question asked in the poll. The typical annual sample for each country is 1,000 people. However, many countries have not had annual surveys. If a typical country had surveys each year, the sample size would be 3,000. It is used responses from the three most recent years to provide an up-to-date and robust estimate of life evaluations.

## Data Contents

The data is categorized by country for 2015-2022 and contains six variables:
1.	GDP per capita, i.e. purchasing power
2.	Social support (having someone to count on in troubled times)
3.	Healthy life expectancy
4.	Freedom to make life decisions,
5.	Generosity (donations to charity)
6.	Perceptions of corruption

The happiness ranking of countries was determined by asking individuals to evaluate their lives as a whole, according to the variables. The Happiness Score is a national average of the responses to the main life evaluation question asked in the Gallup World Poll (GWP). Respondents scored them on a scale of 0 to 10.
Dystopia is an imaginary country that has the world’s least-happy people. The purpose in establishing Dystopia is to have a benchmark against which all countries can be favorably compared in terms of each of the six key variables, thus allowing each sub-bar to be of positive width. The lowest scores observed for the six key variables, therefore, characterize Dystopia. Since life would be very unpleasant in a country with the world’s lowest incomes, lowest life expectancy, lowest generosity, most corruption, least freedom and least social support, it is referred to as “Dystopia”. The Dystopia Residual metric actually is the Dystopia Happiness Score(1.85) + the Residual value or the unexplained value for each country as stated in the previous answer.

## Data Limitations & Ethics
The data is collected via survey based on random sample of respondents. Therefore, it might lead to sample errors.
It was the damaging effects of social media use on the happiness and self-image of adolescents, mainly based on data from the United States in the World Happiness Report 2019. This runs parallel to evidence from earlier Reports showing that in-person friendships support happiness, while online connections do not. But COVID-19 and its limitations on in-person meetings offered a chance for electronic connections to develop their potential for creating and maintaining the social bonds that support happiness.
There is no PII in the dataset and therefore it is considered as low-risk in terms of ethics. The measurement was conducted based on a country level; thus, group of people and small communities can’t be identified.

## Data Relevance
The data is relevant because we can identify happiness rank by country and by time period 2015-2019, measurements of six key variables by countries and we can conduct spatial and time series analysis to make a prediction of happiness level.

## Tools
- Python – to perform exploratory analysis, regression and cluster analysis, find insights and prepare data for visualization. [Python scripts](https://github.com/Smologonova/Python_World-Happiness/tree/main/03%20Scripts).
- Tableau - to turn data and insights into interactive storytelling, available [here](https://public.tableau.com/app/profile/iryna.smologonova/viz/WorldHappiness_16650922495530/WorldHappiness?publish=yes).

