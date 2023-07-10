This repository provides the two types of summarization of privacy policies (text):

## Dataset Scrapping
Built a Scraper for scrapping privacy policies of 100,000 websites and applications and made the dataset.

## Summarization

1) Extractive Method.
2) Abstractive Method.

As well as the Android Application to provide Summaries through application.

## EXTRACTIVE METHOD
Follw these steps to run the extractive methodology:

1)Extract the summy.rar file and place in the same directory.

2)Run the scraper_plus_extractor.ipynb notebook.


## ABSTRACTIVE METHOD
Follw these steps to run the abstractive methodology:

1)Run the seq2seq_integration_with_android_app.ipynb.

2)Firstly train the model for 100 epochs on the privacy_policies_extracted_summaries_dataset.csv dataset.

3)Then fine tune the model on the written_dataset.csv dataset.


## ANDROID APPLICATION

Extract the Summix_Android-App.rar file and run the project on Android Studio.

## Features:
1) Search the URL, the tool will get the privacy policy of the URL.
2) Generate Extractive Summarization of the key features of Privacy Policy in the form of Bullet Points.
3) Generate Abstractive Summarization of the Privacy Policy.
4) Get Top keywords of the paragraphs of the Privacy Policy text. 


##### THERE YOU GO ##### 
