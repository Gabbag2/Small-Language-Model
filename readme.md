# TP04 — RNN Language Model
 
A small LSTM-based Language Model trained on the Penn Treebank (PTB) dataset

## Overview
 
The model learns to predict the next token in a sequence, either at the **word level** or **character level**. Given a prompt, it generates a continuation token by token.
 
## Dataset
 
Penn Treebank (PTB) — journalistic text with ~10k word vocabulary. Numbers are replaced by `N` and rare words by `<unk>`.

## Results

Here is an example generation from the model:

PROMPT    : the stock market  
GENERATED : the stock market crash is getting strongly the prime news they 're going  
 
## Acknowledgements
 
Thanks to Professor Pierre Wolinski for his teachings and for the notebook structure throughout the Deep Learning course in the second semester of the third year DL IASO.
