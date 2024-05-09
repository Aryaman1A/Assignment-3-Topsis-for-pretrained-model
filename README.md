# Assignment-3-Topsis-for-pretrained-model
# Sentence Similarity Assessment

This project centers on the examination of sentence similarity through cutting-edge Sentence Transformer models. The objective is to evaluate and juxtapose various models in their ability to capture semantic likeness between a given query and a set of passages. The analysis encompasses the computation of similarity scores, normalization of distances, and the application of TOPSIS analysis to rank models based on diverse criteria.

# Prerequisites

sentence_transformers
Topsis-Himanshu-102103568
pandas
matplotlib
seaborn
numpy
# TOPSIS Analysis
The project employs TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution) analysis to assess and prioritize different Sentence Transformer models according to their performance metrics. It showcases TOPSIS analysis examples with varied weight configurations, demonstrating its adaptability in aiding decision-making for selecting the most suitable Sentence Transformer model for a given task.

# Evaluation Metrics
Various evaluation metrics are utilized to gauge the effectiveness of Sentence Transformer models in capturing sentence similarity:

Cosine Similarity: Evaluates the cosine of the angle between the query and passage embeddings, where higher values signify greater similarity.
Euclidean Distance: Reflects the Euclidean norm (L2 norm) between query and passage embeddings, with lower values indicating closer proximity and higher similarity.
Manhattan Distance: Measures the Manhattan norm (L1 norm) between query and passage embeddings, providing a robust metric for similarity assessment.
Minkowski Distance: A more generalized form encompassing both Euclidean and Manhattan distances, with the parameter 'p' influencing the norm and offering flexibility in similarity evaluation.
These metrics are computed for each Sentence Transformer model and subsequently normalized to ensure consistency and comparability across different scales. The normalized values are then employed in TOPSIS analysis to rank models based on their overall performance, considering specified weights and impacts for each metric.

# Results and Analysis
Model evaluation was conducted for the following case:

Query: "That is a happy person"
Passages:

"That is a happy dog"
"That is a very happy person"
"Today is a sunny day"
# Utilized Models
Several pre-trained Sentence Transformer models were employed for evaluation:

"Sakil/sentence_similarity_semantic_search"
"sentence-transformers/all-mpnet-base-v2"
"sentence-transformers/multi-qa-MiniLM-L6-cos-v1"
"sentence-transformers/distiluse-base-multilingual-cased-v2"
"sentence-transformers/all-MiniLM-L6-v2"
