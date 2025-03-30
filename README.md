# Self-Attention Mechanism in PyTorch

This project demonstrates the implementation of a simple **Self-Attention Mechanism** using PyTorch. The example processes a sequence of words by generating random embeddings and computing self-attention scores.

## Features
- Uses PyTorch to implement **Self-Attention**.
- Generates random embeddings for a sentence.
- Computes attention scores and attention-weighted output.

## Requirements
Ensure you have Python and PyTorch installed:
```bash
pip install torch
```

## Code Explanation
The script:
1. Defines a sample sentence.
2. Creates random embeddings for the words.
3. Implements a **scaled dot-product attention** function.
4. Computes self-attention scores and outputs them.

## Usage
Run the script using:
```bash
python self_attention.py
```

## Sample Output
```
Self-Attention Scores:
tensor([[...], [...], ...])
```
