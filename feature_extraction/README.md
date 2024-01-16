## Scripts for feature extraction

Files:

-   `data_collector.ipynb`: script for collecting and saving data for each NAICS code based on GitHub topics
-   `openai.ipynb`: script for feature extraction using openai embeddings
-   `doc2vec.ipynb`: script for feature extraction using doc2vec embeddings
-   `keyBert.ipynb`: script for feature extraction using keyBert embedding
-   `openai_multilabeling_eda.ipynb`: script for measuring gpt-4's performance for multi-labeling the data

Datasets:

-   `NAICS Topics.csv`: Selected Github topics associated with NAICS codes, used by `data_collector.ipynb` 
-   `combined_df.csv`: the dataset with all the data without embeddings
-   `all_languages_combined.csv`: dataset with foreign language repos included
-   `combined_df_similarity.csv`: the dataset with all the embeddings and information and the similarity scores
-   `NAICS descriptions.csv`: the NAICS descriptions and corresponding topics
-   `finished_df.csv`: script output

## Data Labeling Methodology

To try to speed up the data labeling process, Github Topics that closely corresponded with NAICS codes were manually selected. Repos were then collected by Github Topic
with the associated NAICS code assumed to be the ground truth label. Github topic was later used as a feature with the ground truth label removed to avoid a data leakage during training.

For repos that could fall under multiple NAICS industries, we experimented with using GPT4 to multi-label repos. These results were compared with the original single label approach.