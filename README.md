# NAICS Repository Classification

This repository contains Juypter notebooks and datasets working towards the goal of classifying Github repositories into [2022 North American Industry Classification System](https://www.census.gov/naics/?58967?yearbck=2022) codes. Pull requests or suggestions are welcome.

## Data

Data collection was automated through the Github REST API. 

See [feature_extraction](./feature_extraction) for data collection scripts, data processing scripts, and datasets. See [finished_dataset](./finished_dataset) for the data post-processed with various embedding models for convenience.

## Models

See the [baseline_models](./baseline_models) for attempting classification with similarity-based approaches. See the [models](./models) folder for the neural network, multi-label linear regression, and UMAP and clustering approaches.

## Remarks
- Repository description, README, and Github topics were found to be the most predictive features in classifying into NAICS codes.
- More novel features like images and organization names are potentially helpful but difficult to generalize for all repos. For instance, classes of images are extremely broad (logos, artwork, real-life, abstract).
- Currently, the trained models can classify into the 20 overarching NACIS codes. More specific industry sub-codes (Ex: 11111 - Soybean farming) would significantly expand the possible classes.
- The data suffers from class imbalance. Certain codes are overrepresented (51 - Information) while other codes (55 - Management of Companies) are difficult to find quality data for. 

## License 
This project is released under [CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/).

## Maintainers 
See [CODEOWNERS](./CODEOWNERS)

## Support
See [SUPPORT](./SUPPORT.md)
