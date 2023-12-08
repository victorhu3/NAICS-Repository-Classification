## Finished Dataset

-   `finished_dataset/doc2vec_finished_df.csv`: the dataset with doc2vec embeddings
-   `finished_dataset/openai_finished_df.zip`: the dataset with openai embeddings
-   `finished_dataset/keyBert_finished_df.csv`: the dataset with keyBert embeddings

### if the filles are too big:

-   `finished_dataset/doc2vec_finished_df`: https://drive.google.com/file/d/16fEiSKDF0YU8By-1wlwSZWXNpoYjn-gb/view?usp=sharing
-   `finished_dataset/openai_finished_df` : https://drive.google.com/file/d/1jow40GIm6F3zztjYb5yGgxtEQGU8Wk1W/view?usp=sharing
-   `finished_dataset/keyBert_finished_df` : https://drive.google.com/file/d/1dkf-E7tspnfrnRpTMb2g1J9EaGYT5H0i/view?usp=sharing

## Columns of the dataset

-   `readme`: the readme of the repository
-   `description`: the description of the repository
-   `label`: the label of the repository
-   `similarity_readme`: the cosine similarity between the readme and the topic
-   `similarity_description`: the cosine similarity between the description and the topic
-   `similarity_topic`: the cosine similarity between the readme and the description
-   `embedding_readme`: the embedding of the readme
-   `embedding_description`: the embedding of the description
-   `embedding_topic`: the embedding of the topic
