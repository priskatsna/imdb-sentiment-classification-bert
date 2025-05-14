# Sentiment Classification on IMDb Movie Reviews using BERT

## Project Summary
This project aims to classify movie reviews as **positive** or **negative** using a fine-tuned **BERT model**. By leveraging transfer learning and pretrained language models, we demonstrate how modern NLP techniques can effectively perform sentiment analysis on real-world data.

### ⭐ Situation  
With the massive growth of online reviews and user-generated content, identifying the **sentiment** behind a review is crucial for businesses, media platforms, and content moderation. The IMDb dataset provides 50,000 movie reviews with sentiment labels, making it a great benchmark for evaluating sentiment classification models.

### ⭐ Task  
The goal was to build a robust, generalizable text classification model that can **predict the sentiment** of English movie reviews using deep learning, specifically transformer-based language models like **BERT**.

### ⭐ Action  
- Preprocessed the IMDb dataset from Kaggle (balanced 25k positive and 25k negative samples).
- Tokenized the data using the `BertTokenizer` from HuggingFace Transformers.
- Fine-tuned the **bert-base-uncased** model using the `ktrain` library for ease of experimentation.
- Used appropriate batch size, learning rate, and early stopping for training efficiency.
- Conducted prediction tests on real review texts.

### ⭐ Result  
- Achieved a **accuracy of 88.6%** and **validation accuracy of 93.3%**.  
- The model was able to generalize well to unseen review data.
- The results showcase that **fine-tuned transformer models can effectively interpret sentiment context**, even in nuanced language.
