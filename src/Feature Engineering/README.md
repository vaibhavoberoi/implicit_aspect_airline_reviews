#################################################################	
#               Author: Vaibhav Oberoi				#
#               Course: MCM Computing				#
#            University: Dublin City University			#
#               ID: 19210149					#
#          Topic: Implicit aspect-based opinion mining		#
#################################################################

This file is requirement text file. 
The code is in the SRC folder of this directory
This project is run in Google Colab environment, so mount drive
The project dependencies that need to be imported  are,
1. Install inflect engine
	pip install inflect
2. All scraped csvs need to be placed in the same location where running the pre-processing notebook
3. Other dependencies needed to be imported
	import pandas as pd
	import glob
	import csv
	import re
	import string
	import nltk
	download nltk stopwords
	from nltk.corpus import stopwords
	from nltk.tokenize import word_tokenize, sent_tokenize
4. Adding below words to NLTK's stopwords
	['was', 'and', 'the', 'to', 'in', 'of', 'a', 'an', 'is', 'were', 
	'for', 'with', 'are', 'one', 'our', 'gave', 'have','me', 'an', 
	'i', 'or', 'had', 'did', 'get', 'made', 'take', 'given', 'told',
	'let', 'us', "n't", 'air', 'one', 'two', 'three','four', 'five', 
	'thousand', 'cc', 'twenty', 'ten', 'hundred', 'eightyseven']
5. Removing 'not' from stopword list
