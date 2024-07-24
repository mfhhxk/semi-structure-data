# Part 1: Text Classifications
This part is to build a text classification predicting the class ComputationalLinguistics. Various setting  of the model are tested in the training process:  
1. Data input: Abstract vs Title
2. Algorithm: Statistic model vs RNN
3. Training size: Full training dataset vs first 1000
cases

A total of 6 (2x2x2) models are generated and the results are measured by using 4 metrics: F1, precision, recall and accuracy, and they were visualized in Part D. 

# Part 2: Topic Modelling
This part is to build models detecting topics of documents. There would be 2 variations of the base model to compare the performance of model:
1. Unigram only vs Unigram and Bigram
2. Different number of topics (10 vs 40)
3. Training size: first 1000 vs first 20000 articles.

A total of 4 models generated: 10 topics with bigram, 40 topics without bigram using 1000 articles or 20000 articles as input.
