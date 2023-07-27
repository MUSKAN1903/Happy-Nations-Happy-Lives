# Happy-Nations-Happy-Lives
A Deep Dive into the World Happiness Report.Embark on an insightful journey through the renowned "World Happiness Report," where we delve into the happiness scores and factors influencing well-being during the pivotal years 2015, 2016, 2017, 2020, and 2021, spanning both pre-COVID and mid-COVID eras.

- We commence with a meticulous analysis of the World Happiness Reports for the years 2015, 2016, and 2017, laying the foundation for understanding global happiness trends before the emergence of the unprecedented COVID-19 pandemic.
- The project then transitions to the more recent years of 2020 and 2021, encompassing the mid-COVID period when the world faced significant challenges and uncertainties. Through the lens of data science, we will decipher how the pandemic might have impacted global happiness scores and the underlying factors influencing people's well-being.
- Drawing from the historical data and mid-COVID trends, we will undertake predictive modeling to forecast happiness scores for the future.
- By embracing the interplay of pre-COVID and mid-COVID data, this project aims to contribute significantly to the understanding of happiness dynamics and the effects of global challenges on well-being.

# Background Study
- The happiness scores and rankings use data from the Gallup World Poll. The scores are based on answers to the main life evaluation question asked in the poll. This question, known as the Cantril ladder, asks respondents to think of a ladder with the best possible life for them being a 10 and the worst possible life being a 0 and to rate their own current lives on that scale.
 Location -: 155 countries

- Features -:
Economy, social support, life expectancy, freedom, absence of corruption, generosity and dystopia residual.
- Label -:
Happiness Score

## TECHNOLOGY USED 

-	We used tableau software (tableau desktop) to extract useful information and effectively present our findings it in form of graphs and other techniques.

-	Knime analytics Platform was used to pre-process the data using cleaning and normalization methods. 

-	The data was visualized and integrated to Tableau using the nodes provided by the node repository. Three machine learning models were used namely Linear Regression, Decision tree Learner and Polynomial Regression.

-	Knime Nodes -: CSV Readers, Column filters, Column Rename, Row Id, Normalizer, Missing Value Filter, Concatenate, Tableau Writer, Group By Node, Components and Metanodes, Sorter, Top K Selector, Bar Chart, Pie Chart, scatter Plot, Accuracy scorer, Tree Learner and Predictors, Linear Regression Learner and Predictor, Polynomial Regression Learner and Predictor, Partitioning Node. 

-	Tableau Graphs -: Line Graph, Flag Bar Charts, Bar Charts, Map
-	Concepts Used -: Hierarchy, Calculated Fields, Animations, Parameters.

## RESEARCH METHODOLOGY -:
- In this analysis, we used secondary data from the world’s largest data science community Kaggle. We took the data for years 2015, 2016, 2017 and 2020, 2021. We classified them into two different eras, pre covid and mid covid namely. At first all the 5 different csv files were combined using Knime analytics platform and data cleaning was performed to make the data ready for Predictions using Regression Machine Learning models. All the clean data was then integrated with tableau to make interactive and meaningful visualizations.

## GLIMPES
![image](https://github.com/MUSKAN1903/Happy-Nations-Happy-Lives/assets/70433658/191a1336-b214-458e-a918-9df562103a62) 
- ![image](https://github.com/MUSKAN1903/Happy-Nations-Happy-Lives/assets/70433658/3c6de490-ad8f-41ad-a13f-a9ca1dae256f)![image](https://github.com/MUSKAN1903/Happy-Nations-Happy-Lives/assets/70433658/9fbb3e1a-1685-4f66-8500-d2ee37760454)


### Dashboard Using Tableau
![image](https://github.com/MUSKAN1903/Happy-Nations-Happy-Lives/assets/70433658/e4a08011-4b27-44df-993f-fdbd38b04583)
### Which Model Works the Best?
Polynomial Regression Model works the best, as it has the highest Accuracy Score and the least  mean absolute error and mean square error.
![image](https://github.com/MUSKAN1903/Happy-Nations-Happy-Lives/assets/70433658/f4f1a4ea-4fb3-48cf-950c-07fde2b53726)

## CONCLUSION -:
-	The Top 10 happiest countries are Finland, Denmark, Switzerland, Iceland, Norway, Netherlands, Sweden, New Zealand, Canada, Australia.
-	The features Economic production, social support, life expectancy, freedom, absence of corruption, generosity and dystopia residual accumulate the Happiness Score.
-	There was no significant change in Happiness Score in the pre covid and mid covid era overall for all countries but for some countries change can be noticed.
-	Afghanistan had an happiness score of 0 in the year 2021.
-	Polynomial Regression Model works the best, as it has the highest Accuracy Score and the least mean absolute error and mean square error.

## FUTURE SCOPE -:
This research will be helpful for the policymakers, program implementers, social advocacy groups to put their efforts to increase the happiness scores amongst the 155 countries taken in the data by improving the factors affecting the target over the coming years. 








