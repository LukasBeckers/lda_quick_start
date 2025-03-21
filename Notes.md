*20.03.2025*
* Initialized Project
* The plan is to create a simple notebook with text-normalization, lda-topic-modeling and visualizations
    * The documents should be made accessible by putting them in a `dokumente` folder.

*21.03.2025*
* Adding preprocessing using nltk
    * should include stemming, normalization, stopword-removal and compound word detection
* Adding LDA topic modeling with gensim
    * gensim takes really long and does not seem to converge with my test-dataset (the test dataset really are just random papers)
* Adding LDA topic modeling with tomotopy
    * It´s much faster and the loglikelyhood per word converges nicely
* Adding visualizations
    * nice formatted topics-words
    * topic word-clouds