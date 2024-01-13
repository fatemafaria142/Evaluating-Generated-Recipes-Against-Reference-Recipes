# Recipe Generation with GPT and GPT-2 Medium

This repository contains code and resources for generating recipes using both the GPT and GPT-2 Medium models and evaluating the generated recipes against reference recipes. It includes code for model training, evaluation, and calculating various evaluation metrics.

## Dataset
The dataset used for this project is sourced from the Recipe NLG Dataset, comprising a collection of recipes suitable for training language models.

## Models
Two models have been utilized for recipe generation:

- **GPT**: The GPT model from the Hugging Face Transformers library. You can access the GPT model via this [link](https://huggingface.co/gpt2).
- **GPT-2 Medium**: An intermediate-sized variant of the GPT-2 model. The GPT-2 Medium model from the Hugging Face model hub is accessible through this [link](https://huggingface.co/gpt2-medium).

## Evaluation Metrics
The quality and accuracy of the generated recipes were assessed using various evaluation metrics:

- Character Error Rate (CER)
- Word Error Rate (WER)
- Exact Match (EM)
- BLEU Score
- METEOR Score
- ROUGE Score
