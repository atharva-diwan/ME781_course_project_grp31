## Dataset details

Big Five personality traits, also known as the five-factor model (FFM) and the OCEAN model, is for grouping different personality traits.

This theory uses descriptors of common language and suggests five broad dimensions commonly used to describe the human personality and psyche. The theory identifies five factors:

* Openness to experience (inventive/curious vs. consistent/cautious)
* Conscientiousness (efficient/organized vs. easy-going/careless)
* Extroversion (outgoing/energetic vs. solitary/reserved)
* Agreeableness (friendly/compassionate vs. challenging/detached)
* Neuroticism (sensitive/nervous vs. secure/confident)

![](https://drive.google.com/uc?id=1dbNj4UDAI9fRDpzo0t-RpvIOORStLZ4p)

This data set was collected (2016-2018) through an interactive on-line personality test. The personality test was constructed from the IPIP. 

The scale was labeled between 1=Disagree, 3=Neutral, 5=Agree.

You can find more info about each question in the data set link.

In this study I will analyse the data set and use unsupervised learning algorithm K-Means Clustering for clustering the participants.

Resources:
https://en.wikipedia.org/wiki/Big_Five_personality_traits
https://ipip.ori.org/newBigFive5broadKey.htm
https://www.kaggle.com/tunguz/big-five-personality-test

## Downloading the dataset

Link to download dataset: https://drive.google.com/uc?export=download&id=1EyZ8IBXhPrIkvLnjKaFVIAsAejbgTQHZ
\
Download and Unzip in the folder: AI_Matchmaking/big5_dataset

## Data Visualization
The code for visualizing the big 5 personality data is present inside the folder AI_Matchmaking/data_visualization

## PCA for dimensionality reduction
The code for applying principal component analysis to identify useful features in the data is present in the folder AI_Matchmaking/pca
 
## K-means Clustering
The code to segregate the data points into clusters for classification according to the personality traits and identifying potential matches within the data is present in the folder AI_Matchmaking/k_means_clustering

To implement all the functionalities above check out the jupyter notebook 'roommate_matchmaking.ipynb' or run it on google colab: https://drive.google.com/file/d/1clRayqqzdkPopaMcJehP21NZKHZVpBAj/view?usp=sharing 