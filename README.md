# Question Answering on Standford's SQuAD2.0
When it comes to Natural Language Processing, understading and responding to questions asked in everyday language is a critical task. The goal of this notebook is to showcase the potential of the [**Standford SQuaD2.0 dataset**](https://rajpurkar.github.io/SQuAD-explorer/), specifically made for Question Answering, by using it to train 3 very capable Transformer-based models like Google's BERT, Facebook AI's RoBERTa and Hugging Face's DistilBERT.

SQuAD consists of a set of around 150,000 questions collected by crowdworkers on a specific set of Wikipedia articles, so that the answer to every question is either a span of text from the article, or the question might be unanswerable. The goal of a model trained on this dataset is to be able to not only answer the questions when possible, but also refrain from answering when a question is unanswerable.
