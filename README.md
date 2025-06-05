# Attention Is All You Need Implementation

This repository implements the Transformer architecture from the paper "Attention Is All You Need" for translating English text into Italian.

## Installation

Create a Python environment with Python 3.8 or newer and install the dependencies:

```bash
pip install -r requirements.txt
```

## Training

Run the training script to train the model on the `opus_books` dataset:

```bash
python train.py
```

The default configuration in `config.py` uses English (`en`) as the source language and Italian (`it`) as the target language.
