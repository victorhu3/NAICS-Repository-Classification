# NAICS Repository Classification

This repository contains Juypter notebooks and datasets working towards the goal of classifying Github repositories into [2022 North American Industry Classification System](https://www.census.gov/naics/?58967?yearbck=2022) codes. 

## Data

Data collection was automated through the Github REST API. 

See [feature_extraction](./feature_extraction) for data collection scripts, data processing scripts, and datasets. For conveniece, see [finished_dataset](./finished_dataset) for the data post-processed with various embedding models.

## Models


## Limitations
Currently, the trained models can classify into the 20 overarching NACIS codes. Industry sub-codes (Ex: 11111 - Soybean farming) are left as future work. 

## License 
This project is released under [CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/).

## Maintainers 
See [CODEOWNERS](./CODEOWNERS)

## Support
See [SUPPORT](./SUPPORT.md)
