## Sentiment Analysis Using BERT

### Introduction
Sentiment analysis is the automated process of determining and categorizing sentiments expressed in textual data. It has witnessed significant advancements with the advent of transformer-based models. Among these models, BERT (Bidirectional Encoder Representations from Transformers) has emerged as a powerful tool for natural language understanding tasks, demonstrating exceptional performance across various domains. In this project, we present an exploration into the application of the BERT model, specifically the ‘BertForSequenceClassification‘ architecture, for sentiment analysis on the Yelp Review dataset.

### Experiment and Training:
The proposed sentiment analysis model, leveraging a BERT-based architecture, has been introduced and trained on the Yelp review dataset. Experiments were conducted to fine-tune the custom pre-trained BERT model with different types of hyperparameter tuning techniques. The model’s performance was evaluated and recorded on validation and test sets, demonstrating its capability in sentiment classification tasks. 

Training data is preprocessed by converting text to lowercase, removing HTML tags, removing punctuation and stopwords, removing special characters, and mapping star ratings to three sentiment levels: ’negative’ for ratings ≤ 2, ’neutral’ for ratings = 3, and ’positive’ for ratings > 3. The processed and prepared training dataset is then split into training and hold-out validation sets. The model is trained using stochastic gradient descent (SGD) as the optimizer in a mini-batch fashion over the processed and prepared training data. A learning rate scheduler and cross-entropy loss are employed for optimization. The training process spans multiple epochs, during which the model is fine-tuned on the training set. Training and validation accuracy and loss are monitored to assess model performance.

### Conclusion:
This experiment and the analysis of the hyperparameter tuning techniques used in this project provide a foundation for further exploration and improvement in sentiment analysis using transformer models. In summary, the systematic approach to model development, thorough experimentation, and careful evaluation on a separate test set contribute to the overall confidence in the reported sentiment analysis results.
