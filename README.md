This repository contains the information of final project for Data Science I: Foundations.

### **Exploring Pollution Levels and Media Trends Between States:** 

### **A Study of New York Times News Reports**

#####  Tian Tong, Wendy Shi, Irene Chen

-   (i) Python Code:

    *'Python_web_scrapping_sentiment.ipynb'* : This code is used to scrape data and calculate the mean sentiment score across collected states

    *'Python_geo_plot1.ipynb'* : This code is used to create the geo plot for US news ranking

    *'Python_geo_plot2_3.ipynb'* : This code is used to create the geo plot for the number of articles and sentiment

    *'Python_bi_gram_5states.ipynb'* : This code is used to create the bi-grams of 5 states which has more than 100 articles collected

    *'Python_bigram_similarity.ipynb'*: This code is used to run similarity test based on extracted bigrams

    *'Python_simi_2.ipynb'*: This code is used to further visualize and analyze similarities in bigrams in separate groups of states

-   (ii): Images:

    rank_cut.JPG: Geo plot for US news ranking by state

    number_cut.JPG: Geo plot for the total number of articles found by state

    senti_cut.JPG:  Geo plot for mean sentiment score by state

    Sample_states_combined_barplot.PNG: Combined top bigrams for sample states to observe national trend

    10states.PNG: Cosine similarity for states across the spectrum in Figure 4.

    all_simi_filter.JPG: Cosine similarity matrix for all 31 states filtered by \>0.4

    inlfation_plot.PNG: Inflation in NYT sentiment ranking against U.S.News ranking

    lowest3_barplot.PNG: Top bigrams for states with lowest Inflation in NYT

    high3_barplot.PNG: Top bigrams for states with highest Inflation in NYT

    lowest6.JPG: Similarity matrix for 6 states with lowest Inflation in NYT, filtered by \>0.35

    top_bigrams_Alaska: The top 20 bigrams of Alaska

    combined_bigrams.PNG: The combined plot of top 20 bigrams of New Jersey and Connecticut

-   (iii). Data:

    full_data_updated.csv : The full data set contains all news articles in all states with data available

    senti_clean.csv : Data set that contains mean sentiment score and total number of articles available.

    Usnews_ranking.csv : US news ranking
