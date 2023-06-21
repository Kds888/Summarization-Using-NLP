# Summarization-Using-NLP
It contains various methods that we can use to summarize a given text.

    FREQUENCY-BASED-SUMMARIZER
The first method that we are using is Frequency based summarizer, refer the notebook for preprocessing of text and getting the data from the internet of user given text.

    LUNH-ALGO-BASED-SUMMARIZER
    
The second method that we are using is Lunh-Algo based summarizer, refer the notebook for preprocessing of text and getting the data from the internet of user given text, the way for calculating the scores in this is a bit different. We take the most important words in a text, by taking in account of their frequency then, based of their frequency we calculate the score like, imp_words**2/total_numer_of_words_in_a_sentence, Making use of this formulae we assign scores to each of the sentences given to us.

    Cosine-Similarity

In This approach we calcuate the similarity matrix, by using the cosine_distance formulae and later on uses the pagerank algorithm to calculate the scores for the sentneces, It is one of the best approaches as we amke use of Bag of words algorithm as well, but this is alos a bit time consuming. Cosine distance formulae is based of the cosine angle calculation through dot products if two vectors and we are making a sentnec as vector by using the bag of word approach, and finally using page rank algorithm we are able to get the scores of each sentnce.

    

