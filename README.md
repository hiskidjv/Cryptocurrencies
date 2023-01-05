# Cryptocurrencies

## Purpose and Overview
>We've been asked to help create a report based on available cryptocurrency data in order to help Martha and the Advisory Services Team at Accountability Accounting make investment decisions.  We need to use unsupervised machine learning to cluster and "classify" the various currencies according to some reduced dimensions (max 3- which allows for visualization).  This will hopefully help in the review of what patterns are in the data set and ultimately what kinds of investments could be advantageous.  

## Process and Deliverables
>After first clearning the data to narrow it down to data we care about (currencies that are actually available for trading, currencies that actually mined more than 0 coin, currencies without missing/null data, etc.), we then scaled it and encoded it for the machine learning algorithm (K-means clustering).  We determined that 4 clusters would be best based on the elbow curve report, and we built a table with the classification/clusters, side by side with the important data and the principal component scores..

## Results and Analysis
>Using our three dimensions (principal components), we found 4 main clusters, labelled classes 0,1,2,and 3.  Class 2 contains a single currency- "BitTorrent" which has the noteable outling aspect of TotalCoinsMined almost to 1 Trillion (almost 10 times the next in order). Class 1 also only has 2 currencies, each with a unique method of ProofType.  Otherwise, the bulk are in class 0 or 3, mostly based on proof-type (PoS or not).  This should cause further research into the prooftype used and what trends exist among them.