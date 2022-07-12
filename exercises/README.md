# Exercises

These exercises were solved and discussed during the in-person classroom sessions.

The exercises build on the preceding lectures; therefore, it is expected that for exercise **E{n}**, one has covered lectures **L{1}**..**L{n}**.


## Prerequisites

Exercises are provided as Jupyter notebooks.

It is strongly recommended to have Python 3.7+ installed from an [Anaconda distribution](https://www.anaconda.com/products/individual#Downloads).

Additionally, you need to install the `ipython-ipytest` package (it adds magic commands that make it easier to define tests directly inside a notebook using the standard `pytest` framework).  You can install it either using [conda](https://anaconda.org/conda-forge/ipytest) or using pip: `pip install ipytest`.


## Workflow

You may use git to get the exercise files or download them from the GitHub website directly.

When using git, the repository is supposed to be used in read-only mode, that is, you only pull changes and make changes locally without committing them.

### Specific steps

  * **First time (if using git)**: Clone this repository to your computer.
    - Note: unless you're a git guru and you know what you're doing, simply clone it and don't fork it.
  * **At the beginning of each class session**: Pull changes from the repository or download the files from the `exercises/E{n}` folder manually..
  * **Complete the exercises in the Jupyter notebook(s)**
    - Easiest is to navigate to the `[YOUR_LOCAL_FOLDER]/exercises` folder and issue `jupyter notebook` in a terminal/command line window. (`YOUR_LOCAL_FOLDER` either refers to the folder where you cloned the git repo or where you saved the files manually.)
    - Complete the exercises by making the tests pass.
    - Do *NOT* commit/push changes, as you won't be able to submit them.
  * **Study the reference solutions** (posted [here](solutions/)) after the class session.



## Exercises and solutions

| **Module** | **Topic** | **Exercises** | **Solutions** |
| -- | -- | -- | -- |
| 1 | Text classification and preprocessing | [0 - Python basics](exercises/E1/0-Python_basics.ipynb)<br>[1 - TF-IDF weighting](exercises/E1/1-TFIDF_weighting.ipynb)<br>[2 - Text preprocessing](exercises/E1/2-Text_preprocessing.ipynb)<br>[3 - Document term matrix](exercises/E1/3-Document_term_matrix.ipynb) | [0 - Python basics](solutions/E1/0-Python_basics.ipynb)<br>[1 - TF-IDF weighting](solutions/E1/1-TFIDF_weighting.ipynb)<br>[2 - Text preprocessing](solutions/E1/2-Text_preprocessing.ipynb)<br>[3 - Document term matrix](solutions/E1/3-Document_term_matrix.ipynb) |
| 2 | Text clustering and similarity | [1 - Term vector similarity](exercises/E2/1-Term_vector_similarity.ipynb)<br>[2 - Cross-validation](exercises/E2/2-Cross_validation.ipynb)<br>[3 - Naive Bayes](exercises/E2/3-Naive_Bayes.ipynb)<br>[4 - Text classification sklearn](exercises/E2/4-Text_classification_sklearn.ipynb) | [1 - Term vector similarity](solutions/E2/1-Term_vector_similarity.ipynb)<br>[2 - Cross-validation](solutions/E2/2-Cross_validation.ipynb)<br>[3 - Naive Bayes](solutions/E2/3-Naive_Bayes.ipynb)<br>[4 - Text classification sklearn](solutions/E2/4-Text_classification_sklearn.ipynb) |
| 3 | Search engine architecture and basic retrieval models | [1 - Inverted index](exercises/E3/1-Inverted_index.ipynb)<br>[2 - Query processing DaaT](exercises/E3/2-Query_processing_DaaT.ipynb)<br>[3 - Vector space retrieval](exercises/E3/3-Vector_space_retrieval.ipynb) |  [1 - Inverted index](solutions/E3/1-Inverted_index.ipynb)<br>[2 - Query processing DaaT](solutions/E3/2-Query_processing_DaaT.ipynb)<br>[3 - Vector space retrieval](solutions/E3/3-Vector_space_retrieval.ipynb) |
| 4 | Retrieval evaluation | [1 - Evaluation measures](exercises/E4/1-Evaluation_measures.pdf)<br>[2 - Interpolated Precision](exercises/E4/2-Interpolated_Precision.ipynb)<br>[3 - NDCG](exercises/E4/3-NDCG.ipynb) | [1 - Evaluation measures](solutions/E4/1-Evaluation_measures.pdf)<br>[2 - Interpolated Precision](solutions/E4/2-Interpolated_Precision.ipynb)<br>[3 - NDCG](solutions/E4/3-NDCG.ipynb) |
| 5 | Advanced retrieval models | [1 - PageRank](exercises/E5/1-PageRank.pdf)<br>[2 - PageRank](exercises/E5/2-PageRank.ipynb)<br>[3 - Rocchio feedback](exercises/E5/3-Rocchio_feedback.ipynb) | [1 - PageRank](solutions/E5/1-PageRank.pdf)<br>[2 - PageRank](solutions/E5/2-PageRank.ipynb)<br>[3 - Rocchio feedback](solutions/E5/3-Rocchio_feedback.ipynb) |
| 6 | Entity-oriented search Part I (Entity Ranking) | [1 - DBpedia Trivia](exercises/E6/1-DBpedia_Trivia.ipynb)<br>[2 - Elasticsearch](exercises/E6/2-Elasticsearch.ipynb)<br>[3 - Elasticsearch](exercises/E6/3-Elasticsearch.ipynb) | [1 - DBpedia Trivia](solutions/E6/1-DBpedia_Trivia.ipynb)<br>[3 - Elasticsearch](solutions/E6/3-Elasticsearch.ipynb) |
| 7 | Entity-Oriented Search Part II: (Entity Linking) | [1 - Naive entity linker](exercises/E7/1-Naive_entity_linker.ipynb)<br>[2 - Entity linking pipeline](exercises/E7/2-Entity_linking_pipeline.ipynb) | [1 - Naive entity linker](solutions/E7/1-Naive_entity_linker.ipynb)<br>[2 - Entity linking pipeline](solutions/E7/2-Entity_linking_pipeline.ipynb) |
| 8 | Entity-oriented search Part III (Semantic Search) | [1 - TETI Evaluation](exercises/E8/1-TTI_Evaluation.ipynb) | [1 - TETI Evaluation](solutions/E8/1-TTI_Evaluation.ipynb) |
| 9 | Neural IR | [1 - Word2Vec w\ Gensim](exercises/E9/1-Word2Vec_w_Gensim.ipynb)<br>[2 - Sentiment  with transformers](exercises/E9/2-Sentiment_w_transformers.ipynb) | [1 - Word2Vec w\ Gensim](solutions/E9/1-Word2Vec_w_Gensim.ipynb)<br>[2 - Sentiment  with transformers](solutions/E9/2-Sentiment_w_transformers.ipynb) |
| 10 | Advanced topics | [1 - WordPiece tokenizer](exercises/E10/1-WordPiece_tokenizer.ipynb) | [1 - WordPiece tokenizer](solutions/E10/1-WordPiece_tokenizer.ipynb) |