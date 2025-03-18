# Alpaca to Odia Translation

This repository contains code to translate the Stanford Alpaca dataset from English to the Odia language.

## Overview

The project uses IndicTrans2 machine translation model from AI4Bharat to translate the Stanford Alpaca instruction-tuning dataset into Odia. The translated dataset can be used to train or fine-tune language models for Odia language support.

## Features

- Automatic translation of Alpaca dataset (instructions, inputs, and outputs)
- Preserves the original English text alongside translations
- Uploads the translated dataset to HuggingFace Hub

## Requirements

- Python 3.x
- PyTorch
- Transformers
- IndicTransToolkit
- Datasets library
- Hugging Face account (for uploading the dataset)

## Usage

1. Clone the repository
2. Install the required dependencies
3. Run the Jupyter notebook to:
   - Set up the translation environment
   - Download the Alpaca dataset
   - Translate the dataset to Odia
   - Create and upload the translated dataset to HuggingFace

## Dataset

The translated dataset is available on HuggingFace Hub at [sumankumarbhadra/alpaca-odia](https://huggingface.co/datasets/sumankumarbhadra/alpaca-odia).

## Acknowledgments

- [Stanford Alpaca](https://github.com/tatsu-lab/stanford_alpaca) for the original dataset
- [AI4Bharat](https://github.com/AI4Bharat/IndicTrans2) for the IndicTrans2 translation model
