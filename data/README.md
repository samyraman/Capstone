# Data Collection

The aim of this capstone project is to create a text summarizer. Given an article, we will predict an abstractive summary of the text, generating entirely new phrases that will capture the main idea of the article. As such, I will be looking at datsets that contain large amounts of high-quality text data. 

## Datasets explored

### 1. WikiHow
The [WikiHow Dataset](https://arxiv.org/abs/1810.09305) is a large-scale dataset of over 230,000 articles on WikiHow with summaries. The articles span a large range of topics, and since they were written by different human authors, represent a diverse set of writing styles. 

### 2. Amazon Fine Food Reviews
The [Amazon Fine Food Reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews) dataset consists of 500,000 reviews of fine foods on Amazon. The data span a period of 10 years and contains reviews by 250k users for 75k different products. It contains a summary string, the full text of the review, and some data about the number of users who found the reivew helpful.

### 3. CNN/Daily Mail 
The [CNN/Daily Mail](https://github.com/abisee/cnn-dailymail) is a large-scale dataset of 300,000 news articles written by journalists at CNN and the Daily Mail. The dataset contains the articles as well as a highlights string, as written by the author. 


The code to fetch and preprocess WikiHow data is in `data.ipynb`