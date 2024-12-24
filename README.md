# Ensemble-Learning-NLP
A basic ensemble learning example: Ensembling the results of 5 different text representation methods (models) and 3 machine learning algorithms with "democratic voting" way
Model1 ->   all-MiniLM-L12-v2: dimension = 384 
Model2 ->   jina-embeddings-v3: dimension 1024 
Model3 ->   multilingual-e5-large-instruct: dimension 1024 
Model4 ->   nomic-embed-text-v1: dimension 1024 
Model5 ->   gte-large: dimension 1024 

Algorithms -> RF, SVM, MLP

# Using these 5 different text representation techniques for retrieval augmentation 

For each question from 2000 different ones and their answers in Turkish, get top1 and top5. Then using three different
ensemling methods (majority voting, average, weight average) get new results, and compare the accuracy values
