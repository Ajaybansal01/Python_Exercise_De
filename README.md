<h1>Overview</h1><br>
This Python script, implemented in the 'De_Word2vec_phrases.ipynb' file, is designed to analyze the similarity between phrases using a TF-IDF vectorizer and cosine similarity metrics. The primary input is a 'phrases.csv' file containing the phrases to be analyzed.<br>
<h1>How it Works</h1>

**Data Input and Preprocessing**: The script begins by reading the 'phrases.csv' file and performing necessary preprocessing on the input data.<br>

**TF-IDF Vectorization**: The phrases are converted into vectors using the TF-IDF (Term Frequency-Inverse Document Frequency) vectorizer. This step transforms the textual data into a numerical format suitable for similarity analysis.<br>

**Cosine Similarity Calculation**: The cosine similarity between different phrase vectors is computed using a cosine similarity function. This metric measures the cosine of the angle between two vectors and is commonly used for text similarity analysis.<br>

**User Input**: The script prompts the user to input a phrase of interest.

**Similarity Scores**: Based on the user input, the script calculates the cosine similarity scores between the user-provided phrase and all other phrases in the dataset.

**Sorting and Output**: The phrases are then sorted in decreasing order of similarity scores, and the top 30 phrases, along with their respective similarity scores, are printed.
<h1>How to Use</h1>
Ensure you have the required dependencies installed. You can find them listed in the 'requirements.txt' file.

Run the 'De_Word2vec_phrases.ipynb' notebook in a Jupyter environment or any Python IDE.

Input your phrase of interest when prompted.

Analyze the output, which includes the top 30 phrases sorted by similarity scores.
<h1>Conclusion</h1>
The Phrase Similarity Analyzer provides a convenient and effective way to explore and understand the relationships between phrases within a dataset. By leveraging TF-IDF vectorization and cosine similarity metrics, the script transforms textual data into a numerical representation and calculates the similarity between phrases.

The user-friendly interface allows individuals to input a phrase of interest, enabling targeted analysis and comparison. The output, presented in descending order of similarity scores, facilitates the identification of phrases closely related to the user-provided input.

This tool proves valuable in various applications, including natural language processing, information retrieval, and semantic analysis. The combination of preprocessing techniques, vectorization, and similarity metrics offers a robust solution for uncovering meaningful patterns and connections within textual data.
