# ADL-Assigment-2

This task demonstrates how to build a movie search system based on semantic text embeddings. Data is first loaded and prepared from a CSV file, with missing values removed and text fields combined. Using Sentence transformers, embeddings are generated for each movie's title and description and saved for reuse. A user query is then matched against the movies using cosine similarity, with the most relevant results returned, including titles, descriptions, and similarity scores. The overviews are generated with the use of hugging face summarize function. This highlights the use of SBERT, a sentence transformer model, to create an search function.
