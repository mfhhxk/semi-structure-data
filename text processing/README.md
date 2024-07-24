# README: Text Classification and Topic Modelling

## Part 1: Text Classifications

This part focuses on building a text classification model to predict the class "ComputationalLinguistics". Various settings of the model are tested in the training process:

### Settings and Variations

1. **Data Input**: 
   - Abstract 
   - Title

2. **Algorithm**: 
   - Statistical Model 
   - RNN (Recurrent Neural Network)

3. **Training Size**: 
   - Full Training Dataset 
   - First 1000 Cases

### Models and Evaluation

A total of 6 (2x2x2) models are generated. The results are measured using the following metrics:
- F1 Score
- Precision
- Recall
- Accuracy

The performance metrics of these models are visualized in Part D.

## Part 2: Topic Modelling

This part focuses on building models to detect topics within documents. There are variations of the base model to compare performance:

### Settings and Variations

1. **N-Grams**: 
   - Unigram Only 
   - Unigram and Bigram

2. **Number of Topics**: 
   - 10 Topics 
   - 40 Topics

3. **Training Size**: 
   - First 1000 Articles 
   - First 20000 Articles

### Models and Evaluation

A total of 4 models are generated:
1. 10 Topics with Unigram and Bigram
2. 40 Topics without Bigram using 1000 Articles
3. 10 Topics with Unigram and Bigram using 20000 Articles
4. 40 Topics without Bigram using 20000 Articles

The performance of these models is compared to evaluate their effectiveness in topic detection.

## Summary

This README provides an overview of the methodologies and variations tested in both text classification and topic modelling tasks. The detailed performance metrics and visualizations are documented in the corresponding parts of the report.
