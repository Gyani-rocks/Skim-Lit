# Skim-Lit
This is an end-to-end tensorflow project that is based on the concepts of deep learning and natural language processing. Here we're going to be replicating the deep learning model behind the 2017 paper PubMed 200k RCT: a Dataset for Sequenctial Sentence Classification in Medical Abstracts. When it was released, the paper presented a new dataset called PubMed 200k RCT which consists of ~200,000 labelled Randomized Controlled Trial (RCT) abstracts. The goal of the dataset was to explore the ability for NLP models to classify sentences which appear in sequential order.

## What we are going to cover (broadly):

1. Downloading a text dataset (PubMed RCT200k from GitHub)
2. Writing a preprocessing function to prepare our data for modelling
3. Setting up a series of modelling experiments
4. Making a baseline (TF-IDF classifier)
5. Deep models with different combinations of: token embeddings, character embeddings, pretrained embeddings, positional embeddings
6. Building our first multimodal model (taking multiple types of data inputs)
7. Replicating the model architecture from https://arxiv.org/abs/1612.05251
8. Find the most wrong predictions
9. Making predictions on PubMed abstracts from the wild
