# GPT3_Text_Embedings_NLP

In this repo, we explore the types of embeddings offered by GPT3 and their use cases

### Software, Tools, and prerequisits

1. Access to Google Colab or some Jupyter Notebook.
2. Basic python programing.
3. Basic API call knowledge.

### Key Terms and Definitions

- **Embedding**: Converting a piece of text into its numerical vector representation. We would explore the two types of embedding below.

  - **Similarity Embedding**: Captures semantic similarities between multiple pieces of text.
  - **Search Embedding**: Measures relevance of long documents to reletively short search queries. both the long document or the short query can be embedded.

- **Dot Product**: Used to check similarity between two vectors. A dot product of 1 signifies bothe vectors have the same direction (effectively are equal).

- **Clustering**: This is a type of unsuperviced learning that draws references from unlabeled dataset by grouping the data by similarities. It is similar to classification in the realm of Superviced learning.
  - **KMeans Clustering**: This is the simplest clustering algorithm that partitions _n_ observations into _k_ clusters where each observation belonges to the cluster with the nearest mean.

In NLP, suppose we have 2 peices of text (sentences), once the texts are embedded (transformed into its numerical vector representation), and we take the dot product of both vectors. If the result is closer to one, it signifies similarity. closer to -1 signifies complete opposites. Everything else inbetween.

### Steps to completing the project

1. Install the necessary packages and modules (OpenAI).
2. Import the necessary modules/ packages needed for this project.
3. Retrieve your API key from OpenAI.
4. Load the dataset (already contains both Similarity & Search embeddings).
5. Implement Semantic Search using the Semantic embeddings.
6. Split the data into Train- Test Split.
7. Use Logistic Regression to classify the Similarity Embeddings.
8. Use K - Nearest Neighbors to classify the Similarity Embeddings.
9. Implement Clustering using the K-Means clustering algorithm on a different example.
