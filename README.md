# Text Sentiment Analysis with Machine Learning

## Description

Uses machine learning to analyse and predict the class a text (comment) belongs to: Toxic, Abusive, Threat, Provocative, Obscene, Hatespeech, Racist, Nationalist, Sexist, Homophobic, Religious Hate, Radicalism.

## Getting Started

### Dependencies

* Required packages: nltk, re, sklearn, pandas, matplotlib.
* Developed with Python in Google Colab.

### Executing program

* Download these two files from Kaggle and place them in the same directory as the main file:
  * Youtube toxic comments: https://www.kaggle.com/datasets/reihanenamdari/youtube-toxicity-data
  * Depression Reddit Dataset: https://www.kaggle.com/datasets/infamouscoder/depression-reddit-cleaned

* Run the file 'Comments_sentiment.ipynb' in Google Colab.

### Changing the data
* The prediction is made on 'depression_dataset_reddit_cleaned.csv'. You may change which file to predict by changing the file:
```
reddit = pd.read_csv('depression_dataset_reddit_cleaned.csv')
```

## Help
* If errors such as 'object is not callable' appear, a simple restart to the colaboratory should fix the issue:
```
Runtime -> Restart runtime
```

## Authors

Vulnet Alija 

## Version History
* 0.1
    * Initial Release
