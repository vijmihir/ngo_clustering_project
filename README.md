# ngo_clustering_project
Find cluster of countries by factors as mentioned using K-means and hierarchical (Single and Complete linkage) clustering and display the findings.

### Problem Statement
HELP International is an international humanitarian NGO that is committed to fighting poverty and providing the people of backward countries with basic amenities and relief during the time of disasters and natural calamities. It runs a lot of operational projects from time to time along with advocacy drives to raise awareness as well as for funding purposes.

After the recent funding programmes, they have been able to raise around $ 10 million. Now the CEO of the NGO needs to decide how to use this money strategically and effectively. The significant issues that come while making this decision are mostly related to choosing the countries that are in the direst need of aid. 

My job is to categorise the countries using some socio-economic and health factors that determine the overall development of the country. Then I need to suggest the countries which the CEO needs to focus on the most.  The datasets containing those socio-economic factors and the corresponding data dictionary are provided below.

### Objectives 
- Start off with the necessary data inspection and EDA tasks suitable for this dataset - data cleaning, univariate analysis, bivariate analysis etc.
- Outlier Analysis:Perform the Outlier Analysis on the dataset. However, I do have the flexibility of not removing the outliers if it suits the business needs or a lot   of countries are getting removed. Hence, all you need to do is find the outliers in the dataset, and then choose whether to keep them or remove them depending on the results you   get.  
- Try both K-means and Hierarchical clustering(both single and complete linkage) on this dataset to create the clusters. Note that both the methods may not produce identical results and you might have to choose one of them for the final list of countries.
- Analyse the clusters and identify the ones which are in dire need of aid. I can analyse the clusters by comparing how these three variables - [gdpp, child_mort and income] vary for each cluster of countries to recognise and differentiate the clusters of developed countries from the clusters of under-developed countries.
- Also, I need to perform visualisations on the clusters that have been formed.  I can do this by choosing any two of the three variables mentioned above on the X-Y axes and plotting a scatter plot of all the countries and differentiating the clusters. 
- Produce a final list of countries.
