# Cognitive Distortion Detection in Bilingual Filipino-English Text

This repository contains the datasets and notebooks developed for our thesis on cognitive distortion detection in bilingual Filipino-English social media text.

The study examines linguistic features associated with cognitive distortions in English and Filipino text, evaluates the performance of fine-tuned multilingual transformer models (`XLM-R` and `mBERT`), and assesses how well these models generalize to out-of-sample data. In general, `XLM-R` yielded more consistent performance than `mBERT`, while binary detection proved more manageable than multiclass classification.

## Research Questions

This thesis addresses the following research questions:

1. What linguistic features are associated with cognitive distortions in English and Filipino text?
2. How effectively do fine-tuned `XLM-R` and `mBERT` detect cognitive distortions in bilingual Filipino-English text?
3. How well do the fine-tuned models generalize to out-of-sample bilingual social media text?

## Repository Structure

- `RQ1/` contains the notebooks for the linguistic feature analysis of English and Filipino text.
- `RQ2/` contains the notebooks for the transformer model training and evaluation experiments.
- `RQ3/` contains the notebooks for the out-of-sample generalization experiments.
- Saved model artifacts generated in `RQ2` and reused in `RQ3` are available on [Google Drive](https://drive.google.com/drive/folders/1KMAcu0Gj9o8rJbeW7wj6yf4pUdWRLRDx?usp=drive_link).