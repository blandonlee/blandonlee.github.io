World College Rankings

The focus of this project was to see if quality education can only be garnered from top-ranked universities. In an attempt to answer this, I created a Null and an alternate hypothesis.

Null: The quality of education has no effect on world ranking Alternate: The quality of education does have a strong connection to world rankings

Based on the analysis conducted the determination was made to reject the Null hypothesis and accept the alternate hypothesis. This indicates that there is indeed a strong connection between them. There were some substantial factors deemed to be significate that contributed to the world rankings such as graduation Rates and student retention. However, other major contributors found throughout the research was quality of education, citations, and the amount/type of research conducted by the schools. Analyzing the different variables, it was found that citation and world rankings and quality of education and quality of the school’s facilities returned strong correlations .94 and .76 respectively. Also, the p_values for these two models were near zero and this made accepting the alternative hypothesis much easier.

To address the problem statement, I collected four datasets that were found on Kaggle.com and proceeded to clean them in preparation for the project. I was then able to merge some of them to make the data a bit easier to manipulate. Utilizing regressions (linear and multiple) helped determine which variables had the greatest effect on the problem statement . Through the correlation tests and calculations of p-values and other summary statistics additional information because apparent. Creating models helped identify variables that had a significant impact on rankings.

Sports Analysis

-Does strength of an athlete play into a sports consideration for being toughest to play? -What attributes are considered the most important in a sport being labeled as tough to play? -What attributes are the least desirable to the overall score for a sport? -Can a single attribute influence the overall ranking? Are multiple attributes necessary? -Are the toughest sports to play the most popular?

After considering all the variables in the dataset I decided to go with the six that I thought would provide the best possible outcome. I decided to use endurance, durability, strength, analytical aptitude, flexibility, and agility. The reason I chose these variables is because they are great attributes for measuring the toughest sport. I proceeded to compare the chosen variables with the variable popularity from a different source. Using the popularity variables, I created another called popularity total to measure/test the variable. For the test variable I used the given score divided by total recorded sports in the dataset and produced the mean value. The various actions that were performed using python were for variance, standard deviation, correlation, means test, tails, and p-values.

Once the analysis was complete, I concluded that strength has a significate impact on determining the toughness of a sport. With the p-value being 6.34554956574914e-38 between strength and total and the null hypothesis being rejected indicates that they were in fact significate. This can be verified with the ANOVA hypothesis test. There was also a multiple regression conducted for strength using total and popularity total as the contributing factors. Having and R2 of .50898 tells me that strength is a crucial element when looking at ranks. I wanted to see if power was able to produce changes and it did bring the value up to .7568 much closer to 1. Testing PFM and CDF I was able to discern that I needed at least a value of 5 on the attributefor strength to be a factor in ranking and overall score. Using the CDF I was able to conclude that at the 50th percentile a value of 5.19 was achieved and as the percentile increases the value of strength increases as well. I also used a probability plot against the variable strength, and it returned as expected a normal distribution.

Time Series Analysis

Loaded the data mj-clean.csv and conducted a time series analysis. This exercise was used to gain additional knowledge and skill with time series analysis, moving averages, serial correlation, autocorrelation, prediction, and linear models.

Textblob and NLTK

This exercise was done to help further knowledge, skills, and proficiency when using Textblob and NLTK. Usinf the data labeledTrainData.tsv I wanted to see the number of positive and negative reviews were in the data. Using textblob I was able to classify each movie review as positive or negative. Using vaderSentiment to compound pilarity scores and test the vader model accuracy.

Clustering Algorithm Kmodes

This project contains data and models used to predict police shootings in the United States. Police shootings are a hot button topic in the United States as their frequency increases year over year. By examining data provided by the FBI, the project team will provide insights into factors contributing to these shootings that may aid in reducing their numbers.The project's main goal was to determine if the fatal shooting could be predicted based on race, age, or signs of mental illness. The project concluded that more data would need to be used for a solid prediction. The R-Squared value of the linear regression model was not significant enough to provide good analysis. The project's bright spot was the decision tree and how the results could provide a good idea of where and how the shooting occurred. The data map also provided also gives a good sense of where shootings have occurred throughout the country.

MNIST

This assignment contains the data and models used to generate/load images from a big data set. The peupose of this assignment was to further knowledge, skills, and compentency when working with big data and remote datasets and keras.

Determine Destination with Data

In this project I am wanting to attempt to identify filters through predictive modeling and determine if it could be used to create an application to be used on the Airbnb sites or bargain sites such as Hotels.com, Travelocity, and other similar sites.

I wanted to try and answer the following questions. • Does the cost/price of a booking correlate to review ratings? • What determines Success? • What variables can help predict if a host will be booked? • Does having instant booking produce more booking?

For this project I wanted to start it by looking at and examining the variables within the dataset. To do this I used a few different resources that were available to me such a R, Python, and PowerBi. • R Conducted summary statistics to see the trends and what the variables are telling me. I then used a linear regression model to determine what they mean. • PowerBI I used the summary statistics and the linear model to produce some visuals for the more prominent variables. I felt that doing this in the beginning would allow me to see the data prior to moving forward with modeling. What I noticed is that price would be a possible target for the models. Other areas of interest were review rating, host response, reviews per month, availability, room type, and guests included. • Python I used Python for the modeling the first was K-Modes clustering model; I then two linear regression models and, finally, a decision tree prediction model. These models provide some valuable insights into the questions being asked.
