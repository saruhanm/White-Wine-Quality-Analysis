## Introduction 

 This project is part of Udacity Data Analyst Nanodegree program. The aim of the project is to use R and apply exploratory data analysis techniques to explore relationships between one variable to multiple variables and to explore a selected data set for distributions, outliers, and anomalies.    
 
 The analysis should be almost like a stream-of-consciousness as you ask questions, create visualizations, and explore your data. This project is open-ended in that there is not one right answer. As John Tukey stated, "The combination of some data and an aching desire for an answer does not ensure that a reasonable answer can be extracted from a given body of data."     

## Project Workspace
**WhiteWines.rmd:** The RMD file containing the analysis (final plots and summary, and reflection)    
**WhiteWines.html:** the HTML file knitted from the RMD file using the knitr package    
**wineQualityWhites.csv:** the original data set and source     
**Sources.txt:** A list of Web sites used in creating the submission   
## Reflection
In this analysis, I examined a dataset related to the quality of white wine. Variables of this study are, Fixed Acidity, Volatile Acidity, Citric Acid, Chlorides, Density, Total Sulphur Dioxide, Residual Sugar, pH, Alcohol, Sulphates, Quality. I analyzed the relationship between all of the variables. I grouped variables by two.

Then, I combined three acidity variables under the name of total acidity. My purpose was to develop a model based on variables to determine quality. After that, I examined the distribution of every variable in the dataset. All of them was similar to normal distribution except residual sugar. When I checked the log distribution of sugar, it was more close to a bimodal distribution.

Later I started to examine the interaction between variables. After calculating the correlations, I plotted the highest correlated variables. My primary interest was the quality which seemed like a result based on the other variables. Research findings suggested that alcohol, sweetness, and acidity were so crucial regarding the quality of the wine.

The model based on acidity, alcohol, and sweetness didn`t perform very well. The r-squared value was meager which was around 0.2. I concluded that quality measurement is more complicated, to get a more precise prediction of the wine quality, In my view, it requires in-depth chemistry knowledge and probably including more variables would be nice.

Finally, I decided to examine some critical variables with the quality and to reach out new conclusions. I reached out that, sweetness and alcohol levels are significant factors of quality. As residual sugar decrease and Alcohol level decrease, quality of wine increase. Also, the quality of white wine has a negative correlation with total acidity, chlorides, density, sulfur dioxide, residual sugar and positive correlation with pH, alcohol, and sulfates.
## Author
This project was completed by Mehmet Saruhan
