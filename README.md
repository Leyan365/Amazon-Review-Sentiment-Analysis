# Amazon Review Sentiment Analysis

This project performs sentiment analysis on the Amazon Fine Food Reviews dataset using two different models: VADER (a lexicon-based approach) and a pre-trained RoBERTa model (a transformer-based approach). The goal is to compare their performance in classifying reviews as positive, neutral, or negative.

## Dataset

The dataset used in this project can be found on Kaggle:
[Amazon Fine Food Reviews Dataset](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)

### Libraries Used in this Project

This project leverages several key Python libraries for sentiment analysis, data manipulation, and visualization.

* **Pandas:**
* **Numpy:** 
* **NLTK (Natural Language Toolkit):** This library provides the **VADER** (Valence Aware Dictionary and sEntiment Reasoner) model, a lexicon-based tool specifically designed for sentiment analysis of social media text.
* **Hugging Face `transformers`:** This is the core of the project's deep learning component. It allows for easy loading and use of the pre-trained **RoBERTa** model, a state-of-the-art transformer for natural language processing tasks.
* **`tqdm`:** Used to display intelligent progress bars, making it easy to track the status of computationally intensive tasks.
* **`scikit-learn`:** A foundational machine learning library used here to generate the **confusion matrix**, a critical metric for evaluating the performance of the VADER and RoBERTa models.
* **Matplotlib** and **Seaborn:** These libraries work together to create the plots and visualizations, specifically the confusion matrices.
* **`scipy`:** Used for its `softmax` function, which converts the raw model scores into probabilities.


## Results

The confusion matrices below compare the predicted sentiment to the actual sentiment (derived from the star ratings).

### VADER Confusion Matrix

<img width="653" height="552" alt="image" src="https://github.com/user-attachments/assets/afba0a7c-b34d-4a1a-899a-f70357d0384e" />


### RoBERTa Confusion Matrix

<img width="653" height="552" alt="image" src="https://github.com/user-attachments/assets/59a67076-1769-4407-945a-ef832efcd463" />

