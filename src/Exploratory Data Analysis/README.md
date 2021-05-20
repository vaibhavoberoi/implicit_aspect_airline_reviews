#################################################################	
#               Author: Vaibhav Oberoi				#
#               Course: MCM Computing				#
#            University: Dublin City University			#
#               ID: 19210149					#
#          Topic: Implicit aspect-based opinion mining		#
#################################################################

Filename: corpus_EDA.ipynb
1. Dependencies:
		json, pandas
2. Description: Code to calculate and analyze corpus statistics and general EDA over entire annotated dataset.
3. Input: Annotated reviews in JSON format.


Filename: intersection_words_EDA.ipynb
1. Dependencies: 
		pandas, collections, operator.itemgetter, collections.OrderedDict
2. Description: Code to find out same/repeating words among various entities/aspects.
3. Input: Entity labeled files CSV format


Filename: most_used_words_EDA.ipynb
1. Dependencies: 
		pandas, matplotlib.pyplot, collections.Counter, wordcloud
2. Description: Code to form wordcloud and barchart of most common tagged words for each entity-aspect.
3.Input: Entity labeled files CSV format