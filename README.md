# Cognizant AI Externship
# Fine-Tuning a Foundation Model
A Jupyter Notebook of Fine-Tuning a BERT Foundation model using the Yelp Dataset found here: https://huggingface.co/datasets/Yelp/yelp_review_full

The main purpose of fine-tuning the BERT model is so it can help classify Yelp reviews from 1 star to 5 stars. All the code is from the HuggingFace
library in Python, which is made for Machine Learning. The model uses the "bert-base-uncased" tokenizer to tokenize the reviews and analyzes them 
for classification. First, the BERT foundation model is assessed on the dataset to see how accurate it can classify the ratings. Afterwards, it is 
fine-tuned to three different LoRA configurations and trained on the dataset to see how accurate they are.
