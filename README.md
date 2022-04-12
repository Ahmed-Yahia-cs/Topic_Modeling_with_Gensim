## Objective:
Topic Modeling is a technique to extract the hidden topics from large volumes of text. Latent Dirichlet Allocation(LDA) is a popular algorithm for topic modeling with excellent implementations in the Python’s Gensim package. The challenge, however, is *how to extract good quality of topics that are clear, segregated and meaningful.* This depends heavily on the quality of text preprocessing and the strategy of finding the optimal number of topics. This tutorial attempts to tackle both of these problems.

### Data:
- Data is a medical related dataset, containing 5k articles in excel format on https://www.minapharm.com/gShare/Pubmed5k.rar


### content:
1. Prerequisites Installation.
2. Import and prepare the Data.
3. Tokenize words.
4. Remove Stopwords and Make multigrams.
5. Create the Dictionary and Corpus needed for Topic Modeling.
6. Building the Topic Model.
7. View the topics in LDA model.
8. Compute Model Perplexity and Coherence Score.
9. Visualize the topics-keywords.
10. Building LDA Mallet Model.
11. How to find the optimal number of topics for LDA?
12. Finding the top n dominant topics in each sentence.
13. Finding the most representative document for each topic.
14. Saving the model.
