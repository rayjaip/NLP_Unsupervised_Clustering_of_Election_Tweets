# NLP_Unsupervised_Clustering_of_Election_Tweets
This repository contains the data and code used in a Natural Language Processing project involving the k means clustering of TF-IDF scores of tweets related to the 2016 Presidential Election. The data was collected from [data.world](https://data.world/alexfilatov/2016-usa-presidential-election-tweets). the NLTK python package was used for the preprocessing of the corpus, and sklearn was used for the calulation of TF-IDF scores, conducting the clustering, and dimensionality reduction for graphing.

My original goal was to scrape twitter for tweets with context ids that are associated with the topics “Kamala Harris”, and “Donal Trump”, the candidates of this year's election. However, a change in X’s API policy meant that my code for collecting this data will no longer work on the free developer plan. Therefore, instead I have decided to change my topic to focus on tweets making mention of Election candidates during the 2016 Presidential Election. I believe this is a good source of alternative data, because there are many political similarities between the race in 2016 and the current Presidential Election. Therefore, substituting in newer posts will remain a feasible option, if anyone with access to a better version of the X dev API would like to test this code on more recent tweets.

The notebook will need to be run via a virtual machine. Google Colab is recommended. 

A detailed description of the project can be found in the 'Report.pdf' file.
