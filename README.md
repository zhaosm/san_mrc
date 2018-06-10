# Stochastic Answer Networks for Machine Reading Comprehension

This PyTorch package implements the Stochastic Answer Network (SAN) for Machine Reading Comprehension, as described in:

Xiaodong Liu, Yelong Shen, Kevin Duh, Jianfeng Gao
Stochastic Answer Networks for Machine Reading Comprehension
Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)
<a href="https://arxiv.org/abs/1712.03556>arXiv link</a>

Please cite the above paper if you use this code. 

## Quickstart 

### Setup Environment
1. python3.6
2. install requirements:
   > pip install -r requirements.txt
3. download data/word2vec 
   > sh download.sh


### Train a SAN Model
1. preprocess data
   > python prepro.py
2. train a model
   > python train.py


## TODO
1. Publish the pretrained models.

## Notes and Acknowledgments
Some of code are adapted from: https://github.com/hitvoice/DrQA

Related: <a href="https://arxiv.org/abs/1804.07888">NLI</a>

by
xiaodl@microsoft.com




