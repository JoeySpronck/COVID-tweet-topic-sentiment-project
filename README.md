# COVID-tweet-topic-sentiment-project

In this project we scraped 127,128 US tweets related to COVID. We performed topic analysis and sentiment analysis over time. Furthermore, we showed that we were able to identify related events to fluctuations of sentiment en topic proportions. Check out the "Final_paper.pdf" file for the final results and our e-mail. 

## Run order:
1. API_scrape_test3.ipynb
2. Sorted_by_date.ipynb
3. LDA
4. LDA_threshold_correction_FINAL.ipynb
5. Plotting.ipynb
6. Wordclouds_distinctive_words.ipynb

## Note:
Mallet was used to train the LDA models, you will need to download and install this yourself, and add the mallet path in your repository. Finally we used a LDA model with 50 topics and 10000 iterations (the data and model filenames are named accordingly). Some of the CSVs in the Data directory are quite big. In order to run all code, some of these files need to be unzipped first.