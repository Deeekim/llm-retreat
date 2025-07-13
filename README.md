# Introduction to this LLM Retreat

This is a collection of learning and practise modules on the basics of large language models. The repository includes jupyter notebook files focused on different libraries such as datasets, transformers, among others. Topics range from the implementation of various NLP techniques, understanding both the use and reconstruction of some significant functions such as pipline and tokenizer, and so on... This is a small introduction for the month of July, complemented with various simple tasks using the libraries, such as toxic classification, emotion identification, and named entity recognition using pretrained models. See below for further details.

Learning progress is following the LLM tutorial listed on Hugging Face. [1] Many thanks to the writers and authors on the Hugging Face Hub. Datasets used are publicly available on the hub.

# Topics covered:

## In-depth understanding of different tasks; progress so far 🕖
- Text Classification
- Named Entity Recognition
- Question and Answering (on context)

## Transformers models 🤖
- main transformer architectures: encoders, decoders, encoder-decoders
- auto tokenizers, auto models, then model heads
- training pipeline
- attention heads
- bias, limitations, ethics

## Fine-tuning a dataset 🔧
- Preprocessing inputs via dynamic padding
- TrainingArguments and Trainer classes
- Manual construction of training loop with the Accelerate and Evaluate libraries
- Different kinds of learning curves and how to interpret: underfitting, overfitting, and erratic learning curves

## Datasets Library 🗂️
- Manipulating via slices and formats of the Dataset class (and vice-versa). Accessing csv, JSON, pandas dataframes, etc
- Streaming large datasets, storing iterable data frames
- Memory-mapping 
- Semantic Search with FAISS index (for similarity search)

## Tokenizers Library
- training tokenization on new languages

## Journey of Progress

Last changes on July 13, 2025. Next steps further emphasizes on the tokenizer infrastructure, then change the direction to classical NLP tasks. Then move to fine-tuning large language models and building reasoning models.

# References
<a id="1">[1]</a> 
Hugging Face (2022)
The Hugging Face Course 
Communications of the ACM, 11(3), 147-148.
https://huggingface.co/course

