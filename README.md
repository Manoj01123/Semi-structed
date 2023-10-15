# Semi-structed
(1) The NLTK library has a number of stemmers, such as the Porter, Lancaster and Snowball Stemmers. Use at least two of those stemmers and compare the differences in some of the stemmed words. Use the word tokenizer to tokenize words before stemming. Select one stemmer for the rest of the analysis.

(2) After stemming, construct the term-document matrix. Eliminate stop words when constructing the term document matrix.

(3) construct the TF-IDF matrix from the term-document matrix.

(4) combine the TF-IDF matrix with Customer data. Then do one-hot encoding on the categorical variables.

(5) There are two types of feature selection methods - the filter type and the wrapper type. Use both types to determine a good set of features. 

Filter type - Use Python's SelectKBest module to find the K best features. Use a variety of K values to determine the best set of features for the combined data.
Wrapper type - Use the SelectFromModel method to find a good set of features on the combined data. Use at least two different classification algorithms (e.g. gradient boosting and random forest) and compare the selected features.
(6) Spliting the combined dataset into a training (80%) and a test set (20%). Using the best set of features from each method (filter and wrapper), build new classification models and evaluate them on the test data.
