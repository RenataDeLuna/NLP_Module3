# Module 3: NLP

Repository for the NLP module. The activity includes three parts for learning to implement:
- Sentiment analysis
- Pretrained NER models
- Pretrained translation models

# Description

In this proyect, we can find three parts that are included in NLP:

- Sentiment analysis: from a movie review dataset, the code analyzes the emotion of each review (positive or negative), using TextBlob.
- Pretrained NER models: a model that identifies the tags of different words, using Spicy (a Python Library). 
- Pretrained translation models: compare the translation made by two different models (Google Translate and Tranlate, a Python library), and getting the BLEU score of each one. 

 The repository includes: 

 - Module3NLPActivity.ipynb : file with the activity. All the dependencies needed for the activity can be installed in Google Colab when running each line of code. 
 - tiny_movie_reviews_dataset.txt : dataset necessary for the first part of the activity. 
 - europarl-v7.es-en.es : dataset used for the third part of the activity. Drive link: https://drive.google.com/drive/folders/1YyrDDg_u-66sHQoXMf2tiN02Smh6BME6?usp=share_link
 - europarl-v7.es-en.en : dataset used for the third part of the activity. Drive link: https://drive.google.com/drive/folders/1YyrDDg_u-66sHQoXMf2tiN02Smh6BME6?usp=share_link
 - Corona2.json : dataset used for the second part of the activity. 

 As I had troubles with Anaconda Navigator, all the dependencies can be installed in Google Colab by running some lines of code. 


 The original Notebook can be found in: https://colab.research.google.com/drive/1cynropxBumb3b5HHiVoiyKmtmFEEbjWG?usp=sharing

 ### Installing

 For this proyect, the user should install:
 - textblob
 - translate
 - googletrans
 
 This can be installed in Google Colab by running a few lines of code (!pip install...)
 - python -m textblob.download_corpora
 - pip install translate
 - pip install googletrans==3.1.0a0

 All the requirements can be found in "requirements.txt"


### Executing program

* The code can be runned entirely in Google Colab: https://colab.research.google.com/drive/1cynropxBumb3b5HHiVoiyKmtmFEEbjWG?usp=sharing
* Or run the "run.py" file.


## Authors

Author: Renata de Luna Flores   A01750484