# VerifAI #

## Introduction ##
This repository contains source code for paper "VerifAI: Verified Generative AI [Vision]". In this paper, we propose that verifying the outputs of generative AI from a data management perspective is an emerging issue for generative AI. This involves analyzing the underlying data from multi-modal data lakes, including text files, tables, and knowledge graphs, and assessing its quality and consistency. By doing so, we can establish a stronger foundation for evaluating the outputs of generative AI models. Such an approach can ensure the correctness of generative AI, promote transparency, and enable decision-making with greater confidence.

## Quick Start ##

## Dataset ##
In our paper, we use tabular and textual data to construct a data lake.  The text files are in *./data/missing_value_imputation/wikipages.jsonl* . Also, you can get the tabular corpus from [this](https://drive.google.com/file/d/1-BPOYgC9sDIJ2c5GBj2qprisGuF__TDr/view?usp=share_link), and put the tables into the *./data/missing_value_imputation* and *./data/tabfact* folders respectively.

## Running Code ##
You can run **index.ipynb, retrieve.ipynb, generate_by_chat.ipynb** and **verify.ipynb** step by step.

