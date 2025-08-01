# Sentiment_Detection_in_Support_Interactions
This project aims to automatically detect the emotional tone (positive, negative, neutral) in customer support interactions—such as chats, emails, or service tickets—to help businesses improve responsiveness, prioritize critical cases, and enhance customer satisfaction.

The problem was tackled from three distinct perspectives, each implemented and analyzed in separate notebooks:

Machine Learning Approach:
Traditional models such as Logistic Regression, Support Vector Machines (SVM), and Random Forests were trained using TF-IDF and Bag-of-Words features. This approach focused on simplicity, interpretability, and efficiency.

Deep Learning Approach:
Sequential models like CNN, LSTM and BiLSTM were trained using word embeddings (e.g., GloVe), providing a deeper understanding of word order and context. These models were better at handling subtle sentiment shifts in longer texts.

Large Language Model (LLM) Approach:
Transformer-based models like BERT and RoBERTa were applied with fine-tuning on labeled data. These models captured complex language patterns and delivered the most contextually accurate sentiment predictions.

Each method was evaluated independently on the same dataset, allowing for a comparative analysis in terms of accuracy, interpretability, computational cost, and deployment feasibility.

