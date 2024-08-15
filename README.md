***Semantic Search by Mohsan***

This project demonstrates the implementation of semantic search using the Sentence Transformers and FAISS (Facebook AI Similarity Search) libraries. The goal is to convert textual data into vectors and perform efficient similarity search queries on the dataset.

***Overview***

The notebook includes the following steps:

***1 :Loading the Dataset:***


The dataset containing text is loaded using the pandas library.

***2: Text to Vectors Conversion:***


Sentence Transformers (all-mpnet-base-v2 model) from Hugging Face is used to convert the text column into vectors.

***3: Vector Indexing with FAISS:***

FAISS is used for efficient similarity search and clustering of dense vectors.
The vectors are indexed using FAISS to facilitate quick nearest neighbor search.

***4: Search Query Execution:***

A sample search query is vectorized and used to search within the indexed vectors.
The search results are obtained and displayed.

***Dependencies:***

Ensure you have the following libraries installed:


pandas
sentence-transformers
faiss
numpy

***Conclusion***

This project demonstrates the basic workflow for implementing a semantic search using Sentence Transformers and FAISS. It converts textual data into vectors, indexes them for efficient similarity search, and performs search queries to find relevant results.
