# Arabic-Hate-speech

This is a repository for our work on Hate speech detection in Arabic Twittersphere.You can find the training and testing sets that we used to train and evaluate our models (will be published soon). Both files (train.csv and test.csv) have only tweets that annotated as hate or not hate. The files contain tweets ids along with their annotation (hate = 1 , non-hate = 0). 

You can also find the full dataset (dataset.csv) that contains 9,316 tweets annotated as (Abusive = 2 , hateful = 1, normal = 0) 

The repo also contains two lexicons of hate terms extracted from the dataset using two corpus statistical-based approaches: chi-square and Pointwise Mutual Information (PMI).  


We integrated the trained model into a web-based tool to detect hate speech. You can try here : http://hatespeech-detector.com/
