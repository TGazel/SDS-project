# SDS-project
Git repository for the SDS (S2021) final project: 

Only aggregates (cardinality of lists of shared followers) may be found in the shared data in order to ensure that data is fully anonymized. 

The dataset may be rebuilt by retrieving follower list from newspaper's Twitter account as described in the report and below. Note that data will not be exactly the same, as followers lists will be different at another point in time (the data for this analysis is of February 2021).

All plots and tables in the report may be reproduced by running the code in the folders Directed Graph and Undirected Graph.

Instructions
1. Run Data Preprocessing\DataRetrieval.Rmd to retrieve the newspaper follower lists (these should then be stored in the Data Preprocessing\Follower lists folder)
2. Run Data Preprocessing\DataPreprocessing to merge/discard any duplicated twitter accounts (these should then be stored in the Data Preprocessing\CleanData folder)
3. The code in the Directed Graph and Undirected Graph folder may be run in any order. Note, that the data retrieval takes a lot of time due to the twitter limits on collecting followers. Hence, we have provided the above mentioned aggregates of followers so you can start directly from 3. 

