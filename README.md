# Bayesian-Hierarchical-Model-for-Spotify-Song-Popularity

What makes a song popular? There is an unmeasurable number of features that might affect how well a certain song will behave in the charts. Those variables interact with each other in such complex ways that artists usually claim that their success is mostly dependent on luck. This might be true, but as data scientists we ahould at least attempt to estimate and model the phenomenae that contribute to a song’s popularity, since the music industry is one of the most important ones in the field of entertainment.

In this project, our aim is to disentangle the effects of some song attributes on their popularity using Bayesian modeling. We will build and compare different models (namely fully pooled, hierarchical, and fully unpooled) to predict the popularity of a song based on its features and genre. Our focus will be on the hierarchical model approach, which allows us to model both the individual effects at the song level and the group-level effects at the genre level, leveraging the strengths of Bayesian inference to capture uncertainty and provide more robust estimates than more classic approaches that would provide simple linear estimates for each feature, which is an unlikely way of how the underlying data generating process might be producing our data.


### Dataset

I used a publicly available dataset on Kaggle that gathers the top 2000 tracks on Spotify up until 2019. This dataset has no missing values, is clean, well-organized and has a wide set of variables that we can work on. More information and access to the dataset in the link below:
https://www.kaggle.com/datasets/iamsumat/spotify-top-2000s-mega-dataset
