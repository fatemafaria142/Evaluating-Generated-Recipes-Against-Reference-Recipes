# Automatic Recipe Generation

This repository contains code and resources for model training, evaluation, and calculating various metrics for generating food recipes.

## Dataset
The dataset used for this project is sourced from the Recipe NLG Dataset, a collection of recipes suitable for training language models. You can find more information about the dataset [here](https://huggingface.co/datasets/recipe_nlg).

## Models
Seven models have been utilized for recipe generation:

- **GPT**: [link](https://huggingface.co/gpt2).
- **GPT-2 Medium**: [link](https://huggingface.co/gpt2-medium).
- **Mistral-7B-v0.1**: [link](https://huggingface.co/mistral-7B-v0.1).
- **TinyLlama-1.1B-Chat-v1.0**: [link](https://huggingface.co/tinyllama-1.1B-chat-v1.0).
- **Starling-LM-7B-alpha**: [link](https://huggingface.co/berkeley-nest/Starling-LM-7B-alpha).
- **Mistral-7B-Instruct-v0.2**: [link](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.2).
- **OpenChat 3.5 1210**: [link](https://huggingface.co/openchat/openchat-3.5-0106).

## Evaluation Metrics
The quality and accuracy of the generated recipes were assessed using various evaluation metrics:

- Character Error Rate (CER)
- Word Error Rate (WER)
- Exact Match (EM)
- BLEU Score
- METEOR Score
- ROUGE Score
