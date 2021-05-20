#################################################################
#		Author: Kanishk Verma				#
#		Course: MCM Computing				#
#		University: Dublin City University		#
#		ID: 19210344					#
#		Topic: Implict aspect-based opinion mining	#
#################################################################

This is a requirements file for Custom_embeddings_with_pretrained.ipynb and 
Word2Vec_on_sequential_with_TSNE.ipynb

The code is developed in Google Colab environment

1. Installing and importing project dependencies
	1.1. Installing glove
		pip install glove-python
	1.2. Other dependencies
		numpy, pandas, gensim.models import Word2Vec, pickle
		keras.models import Sequential, keras.layers import Dense, Activation, 		Embedding, tensorflow, scipy, matplotlib, seaborn
2. Results from this embedding
	2.1. Word2Vec_on_sequential hosts TSNE code and results
	2.2. Custom_embeddings gives a .pickle model of the trained word2vec+glove pre-		trained embeddings