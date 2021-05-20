# Author: Vaibhav Oberoi
# Topic: Implicit Opinion Mining

All of your source code (and other program resources) should be placed in this sub-directory.

Folder Structure
1. CRF:- Conditional Random Field
    1.1. src -> python notebook containing code to create a CRF model with L2 stochastic gradient descent
    1.2. result -> contains model, ROC-AUC curve and Precision v/s recall curve images along with a classification report
2. Scraper:- Selenium based web scrapper
    2.1. src -> python notebook to collect reviews from both TripAdvisor and AirlineRatings website for 16 airlines
3. Pre_Processing:- Review pre-processing python notebook
    3.1. src -> pre_processing notebook
4. Word Embeddings
    4.1. src -> CBOW_model -> experimental continiuous bag-of-words model
                Skipgram_model -> experimental skip-gram model
                word2vec on sequential with TSNE -> experimental code for implementing word2vec on a sequential neural network
                custom embeddings with pre-trained -> experimental code for implementing ACTUAL embeddings using pre-trained glove, code output a pickle 
                                                        embedding vector file, link to which is available in build/README.md
5. Feature Engineering
    5.1. src -> Entity_Level_Feature_Generation -> here feature engineering code for CRF model is stored

6. Corpus_Statistics
    6.1. Type_Token_Ratio_Zipfs -> Code to calculate TTR and Zipfs law

7. Evaluation
    7.1. Kappa_Coefficient -> Code to calculate inter-annotator agreement level

8. Exploratory Data Analysis
    8.1. corpus_EDA -> Code for exploratory data analysis on corpus
    8.2. intersection_words_EDA -> Code for EDA of intersection of common words in corpus
    8.3. most_used_words_EDA -> Code for EDA on most common words in corpus

