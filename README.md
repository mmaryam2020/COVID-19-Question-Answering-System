# Question Answering System for COVID-19
I implemented a model in this project that will be generalizable to new questions, and it won't be limited to specific questions.

As the Covid article dataset is too large, our purpose was to build a model that can almost answer most of the questions related to Covid among these versatile articles.

I use this considerable dataset as a context to fine-tune transformers and extract  favorable answers from them. 

After reviewing cuttin-edge methods in the field, we decided that the [Roberta-Squad model](https://huggingface.co/deepset/roberta-base-squad2) and [Biobert-model](https://huggingface.co/clagator/biobert_squad2_cased), which are both Bert-Based models, can be a desirable solution to our problem.


## Required Data files
The path to Data file can be fined in the Data folder
