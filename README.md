# Automatic Recipe Generation

This repository contains code and resources for generating recipes using GPT, GPT-2 Medium, Mistral-7B-v0.1, and TinyLlama-1.1B-Chat-v1.0 models. It includes code for model training, evaluation, and calculating various metrics.

## Dataset
The dataset used for this project is sourced from the Recipe NLG Dataset, a collection of recipes suitable for training language models. You can find more information about the dataset [here](https://huggingface.co/datasets/recipe_nlg).

## Models
Four models have been utilized for recipe generation:

- **GPT**: [link](https://huggingface.co/gpt2).
- **GPT-2 Medium**: [link](https://huggingface.co/gpt2-medium).
- **Mistral-7B-v0.1**: [link](https://huggingface.co/mistral-7B-v0.1).
- **TinyLlama-1.1B-Chat-v1.0**: [link](https://huggingface.co/tinyllama-1.1B-chat-v1.0).

## Evaluation Metrics
The quality and accuracy of the generated recipes were assessed using various evaluation metrics:

- Character Error Rate (CER)
- Word Error Rate (WER)
- Exact Match (EM)
- BLEU Score
- METEOR Score
- ROUGE Score
