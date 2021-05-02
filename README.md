# Mac vs Windows - Laptop buying behavior - Unsupervised Learning - Python
-------------------------------------------------------------------------
*Contains Principal Component Analysis and Clustering*

Business Case : From a personality survey taken using business school students, predict their laptop buying behavior whether Mac or Windows.

Participants of the survey take the Big 5 personality test and also the Hult DNA test.

The data from these personality tests are used to determine the laptop buying behavior of the participants. 

The techniques used for this analysis were Principal Component Analysis and Clustering. 

Packages used : pandas, numpy, seaborn, matplotlib, sklearn 

Principal Component Analysis
----------------------------

The scores from the survey were grouped into the Big 5 personalities which were Extraversion, Agreeableness, Conscientiousness, Neuroticism and Openess.

This dataframe was scaled and PCA was conducted on this data. 

With the help of the factor loadings we further classified the 5 principal components as 5 personalities.

They were Ameanable, Equanimous, Obsessive and Indecisive. 

Similarly score from the survey were grouped into the Hult DNA which were Thinking, Communicating and Team Building.

This dataframe was scaled and PCA was conducted on this data. 

With the help of the factor loadings we further classified the 2 principal components as 2 personalities.

They were Apatheitc and Cerebral. 

Cluster Analysis
-----------------
With the help of a Dendogram we decided to use 4 clusters to analyze the Big 5 data. 

The clusters were named as 4 personality subgroups called Indifferent, Passionate, Spontaneous and Temperamental. 

With the help of a Dendogram we decided to use 3 clusters to analyze the Hult DNA data. 

The clusters were named as 3 personality subgroups called Trend Follower, Realist and Autogenicist. 

Insights and Recommendations
-----------------------------

Big 5 strategy:

1. Customizable products and additional discounts for the Obsessive and Equanimous
2. Sales calls to the Indecisive

Hult DNA strategy:

1. Boost brand presence through Social Media for Apathetic Trend Followers
2. Conduct A/B Testing for Payment plan options to Apathetic Realists

Additional Insights:

1. Attract Customers with Affordable Trade-in options for South America
2. Promotion through sports for male customers

 




