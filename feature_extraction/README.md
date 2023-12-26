## Scripts for feature extraction

Files:

-   `data_collector.ipynb`: script for collecting and saving data for each NAICS code based on GitHub topics
-   `openai.ipynb`: script for feature extraction using openai embeddings
-   `doc2vec.ipynb`: script for feature extraction using doc2vec embeddings
-   `keyBert.ipynb`: script for feature extraction using keyBert embedding
-   `openai_multilabeling_eda.ipynb`: script for measuring gpt-4's performance for multi-labeling the data

Datasets:

-   `combined_df.csv`: the dataset with all the data without embeddings
-   `combined_df_similarity.csv`: the dataset with all the embeddings and information and the similarity scores
-   `NAICS descriptions - Sheet1.csv`: the NAICS descriptions and corresponding topics
-   `finished_df.csv`: script output
