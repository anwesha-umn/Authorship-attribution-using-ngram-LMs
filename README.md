# Authorship-attribution-using-ngram-LMs

### Generative and Discriminative Authorship Classifier
Project Overview
This project implements both generative and discriminative models to classify the author of given text samples. The generative model relies on n-gram language modeling techniques, while the discriminative model uses HuggingFace's pre-trained DistilBERT for text classification. The goal is to accurately predict whether a text belongs to one of the following authors: Jane Austen, Charles Dickens, Leo Tolstoy, or Oscar Wilde.

### Project Structure
classifier.py: Contains the code for the generative authorship classifier as well as discriminative classifier. 

1. **Train on 90% of the dataset and evaluate on the reamining 10% of dataset**

   ```bash
   $ python classifier.py authorlist -approach generative
3. 
using NLTK-based n-gram models.
discriminative_classifier.py: Implements the discriminative classifier using the HuggingFace DistilBERT model.
data/: Contains the author text files used for training and evaluation.
README.md: This file, providing an overview of the project, instructions for usage, and key results.
