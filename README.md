# Recipe Generation with GPT-2 and Evaluation Metrics

This repository contains code and resources for generating recipes using GPT-2 and evaluating the generated recipes against reference recipes. It includes code for model training, evaluation, and calculating various evaluation metrics.

## Dataset
The dataset used for this project is sourced from the [Recipe NLG Dataset](https://huggingface.co/datasets/recipe_nlg). It contains a collection of recipes suitable for training language models.

## Model
The GPT-2 model from the Hugging Face Transformers library was utilized for recipe generation. GPT-2 is a powerful language model capable of generating coherent text based on provided prompts.

## Evaluation Metrics
The following evaluation metrics were calculated for assessing the quality of the generated recipes:
- Character Error Rate (CER)
- Word Error Rate (WER)
- Exact Match (EM)
- BLEU Score
- METEOR Score
- ROUGE Score
