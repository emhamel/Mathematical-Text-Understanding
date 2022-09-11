``Mathematical Token Definition Extraction``
================

Introduction
------------

This work describes and answers a problem in Mathematical Named-Entity Recognition: Given a mathematical object and the context in which it, can we extract its definition?  This repo contains a dedicated, Mathematical Token Definition Extraction (MTDE) dataset, the MTDE dataset, as well as the implemetations of five different neural defintion extraction models. [1] is a peer-reviewed full analysis on the MTDE problem and how the models perform on the MTDE dataset. 

The Dataset
-----------

The MTDE dataset contains around 10,000 entries of variable names, the contexts in which they are defined, their ‘short’ definitions and their ’long’ definition.  Here, short defintion is a 1-word-long definition and long definition is a one-or-more-word-long definition. The data was collected from a random sampling of mathematical and scientific arXiv preprint manuscripts. The manuscripts cover a wide range of mathematic and scientific disciplines including Physics, Computer Science, and Biology. Candidate data was generated via a corpus crawler and then pruned and cleaned manually. 

The Models
-----------

In this repo, the following models are implemented in jypter notebook tutorials:

1. Vanilla Seq2Seq
2. Transformer Seq2Seq
3. Pointer Network
4. Match-LSTM
5. BERT (Huggingface's BertForQuestionAnswering)

These tutorials are aimed to full explain the mechanisms behind each mathematical defintion extraction model examined in [1] as well as serve as a blueprint for .

Contact
-------
Email: <ebhamel2@illinois.edu>

Please message me with any feedback or errors you may find!  Any help is appriciated :)

Notes
-------
There is a small error in right-most subfigure or figure 1 in [1]. The correct figure should be:
![Corrected Subfigure](/images/correct_subfigure.png)

References
-------
[1] 
