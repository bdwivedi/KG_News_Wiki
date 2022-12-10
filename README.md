# KG_News_Wiki
Project under DSE203 to show knowledge graph
Data can be downloaded with the help of commented code and stored in csv file under Data folder. News and Wiki data has not been uploaded because of file size but intermediate data has been stored to create knowledge graph.

<B>Technique used to process text:</B>/n
Identify the Subject Verb Object triplet 
Identify Token & Entity to create node csv
Lemmatize the verb, remove stopwords and identify synonyms using Wordnet
Find the similarity for Subject and Object using Jaccard Similarity with threshold 0.5
Filter the entries that have subject and object are same
Filtered subject & object having less than 3 characters
Removed numerical & alpha numerical values from subject & object [e.g. A234, XYZ456]

