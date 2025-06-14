# Dataset: Twitter Sentiment Analysis

This dataset is an adapted version of the [Sentiment Analysis: Emotion in Text](https://www.kaggle.com/competitions/tweet-sentiment-extraction) dataset originally curated by Figure Eight (now Appen) and hosted on Kaggle under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

## Overview

The dataset consists of English-language tweets annotated with sentiment labels:  
- **positive**  
- **negative**  
- **neutral**

While the original dataset includes additional annotations (specifically the `selected_text` field, which highlights the text span justifying the sentiment), this project uses only the following columns for training and evaluation:

| Column       | Type   | Description                                                                 |
|--------------|--------|-----------------------------------------------------------------------------|
| `text`       | string | The full content of the tweet. This serves as the input for sentiment analysis. |
| `sentiment`  | string | The sentiment label: `positive`, `negative`, or `neutral`.                   |

## Files

- `train.csv` – Contains 27,481 annotated tweets.
- `test.csv` – Contains 3,534 annotated tweets for model evaluation.

The `train.csv` file is further split into training and validation sets using a **stratified 80/20 split**, ensuring the label distribution is preserved across subsets.

## Why This Dataset?

This dataset was selected for several reasons:

1. **Quality and Community Validation**  
   Curated through a Kaggle competition with a \$15,000 prize pool, the dataset benefits from high-quality annotations and rigorous community feedback.

2. **Real-World Data**  
   The tweets represent authentic, noisy, user-generated content, ideal for testing a model’s ability to generalize across informal and diverse language styles.

3. **Open and Reproducible**  
   The dataset is publicly available under a permissive license, allowing for open experimentation and reproducible research.

## Licensing

This dataset is distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license.  
You are free to share and adapt the data, provided appropriate credit is given.

## Acknowledgments

- This dataset is originally curated by [Figure Eight](https://appen.com/) and made available via [Kaggle](https://www.kaggle.com/competitions/tweet-sentiment-extraction).
- We thank the Kaggle community and competition organizers for providing a high-quality, well-annotated dataset for sentiment analysis research.

## Citation

If you use this dataset in your work, please cite it as follows:

```bibtex
@misc{kaggle2020sentiment,
  title={Tweet Sentiment Extraction},
  author={Kaggle},
  year={2020},
  url={https://www.kaggle.com/competitions/tweet-sentiment-extraction}
}
```
---

For more details or to download the original dataset, please visit the [Kaggle competition page](https://www.kaggle.com/competitions/tweet-sentiment-extraction).
