# Question Answering System for COVID-19
I implemented a model in this project that will be generalizable to new questions, and it won't be limited to specific questions.

As the Covid article dataset is too large, our purpose was to build a model that can almost answer most of the questions related to Covid among these versatile articles.

I use this considerable dataset as a context to fine-tune transformers and extract  favorable answers from them. 

After reviewing cuttin-edge methods in the field, we decided that the [Roberta-Squad model] (https://huggingface.co/deepset/roberta-base-squad2) and Biober-model, which are both Bert-Basd models, can be a desirable solution to our problem.
The attached PDF file shows a brief summary of the whole project result.

Required Data files
.json files containing the full texts for papers in the above dataset can be downloaded from here: https://bit.ly/3fzhlhD
