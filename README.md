``Mathematical Token Definition Extraction`` readme
================

Introduction
------------

This repo contains the Mathematical Token Definition Extraction (MTDE) dataset and the implementation of the five nueral natural language processing models described in [1]. This work d

The Dataset
-----------

The data was collected from a random sampling of mathematical and scientific arXiv preprint manuscripts.  The manuscripts cover a wide range of mathematic and scientific disciplines including Physics, Computer Science, and Biology.  Candidate data was generated via a corpus crawler and then pruned and cleaned manually. 

The Models
-----------

In this repo, the following models are implemented in jypter notebooks:

1. Vanilla Seq2Seq
2. Transformer Seq2Seq
3. Pointer Network
4. Match-LSTM
5. BERT (Huggingface's BertForQuestionAnswering)

Contact
-------
Email: <ebhamel2@illinois.edu>

Please message me with any feedback or errors you may find!  All help is appriciated :)

Notes
-------
There is a small error in right-most subfigure or figure 1 in [1]. The correct figure should be:

References
-------
[1] 
