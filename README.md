# Text_Summarizer_With_SBERT_and_Flask


## Introduction


In this project, we will build a flask web application that summarizes text using the Sentence-BERT model.

Text summarization deals with the creation of sentence embeddings that supports over 100 languages. You can read more about Sentence-BERT [here](https://arxiv.org/abs/1908.10084).

SBERT can also be used to compare the semantic similarity of words. When summarizing a lengthy text, it is critical to seek similarities between sentences to ensure that the summary is correct and does not distort the original text’s meaning.

## Sentence-BERT (SBERT)

Sentence-BERT (SBERT), a siamese and triplet network-based variant of the BERT model is capable of deriving semantically meaningful sentence embeddings.

With SBERT, BERT got the additional capability to compare massive sets for semantic similarities, groups, and retrieve information via semantic search.

BERT established new benchmarks for performance on a variety of sentence categorization and pairwise regression problems.

Semantically related sentences can be identified using a similarity measure such as cosine similarity distance. 
Due to the high efficiency with which these similarity measures can be computed on modern technology, SBERT can be used for both semantic similarity search and clustering.

## The flask web application

We create a folder called templates with two files inside it:

index.html
summary.html
In the index.html file for the home page, we display a text field where the user can submit a textual content that is to be summarized:

![image](https://github.com/mustaphaamine1/Text_Summarizer_With_SBERT_and_Flask/assets/92463510/3f8539ce-b35d-497e-92d5-bc54d8ebc32c)

To display the text summary of the text we inputted, we create summary.html as shown:


In the project folder, we have the following folders and files:

The folder contains files installed during virtual environment creation.

The templates folder.

app.py file containing the Python script.


