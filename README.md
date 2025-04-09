# Seq2seq_RE
Towards Extracting Software Requirements from App Reviews using Seq2seq Framework

### Introduction

This repository includes all the materials (code, input data, evaluation results) of our approach to extracting requirements from app reviews. These materials support the replication of our study.

### File Descriptions

There are three directories in total, and the content of each directory is described as follows:

`datafiles`: the input data used for this study.

- `dataset_1_RE-BERT.csv` is the ground-truth Dataset 1 from the baseline study RE-BERT.
- `dataset_2_T-FREX.csv` is the groud-truth Dataset 2 from the baseline study T-FREX.
- `dataset_1_preprocessed.csv` is the preprocessed Dataset 1.
- `dataset_2_preprocessed.csv` is the preprocessed Dataset 2.

`docs`: additional supporting documents for our study.

- `results.md` contains the evaluation results on both datasets.

`programfiles`: the source code of our study.

- `dataset1_preprocessing.ipynb` contains the code to preprocess the Dataset 1 according to our modeling approach.
- `dataset2_preprocessing.ipynb` contains the code to preprocess the Dataset 2 according to our modeling approach.
- `s2s.ipynb` contains the architecture of our sequence-to-sequence framework and its training and evaluation code.