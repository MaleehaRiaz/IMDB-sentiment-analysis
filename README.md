IMDB Movie Reviews Sentiment Analysis

Overview:
I built a sentiment analysis model to classify IMDB movie reviews as positive, neutral, or negative using BERT in both TensorFlow and PyTorch.

Dataset:
Used: IMDB Dataset from Kaggle
I used the Kaggle IMDB Dataset with 49,582 reviews, containing review and sentiment columns.

Key Steps:
Cleaned text (removed URLs, special characters, and lowercased text).
Tokenized reviews with bert-base-uncased tokenizer.
Mapped sentiments: positive → 2, neutral → 1, negative → 0.
Split data into training (80%) and test (20%) sets.
Trained a BERT-based classifier for sentiment prediction.

Visualizations:
Training/Validation Loss and Accuracy over epochs. 
BLEU Score over Epochs.
Heatmap of Sentence Similarities.
PCA & t-SNE scatter plots for embeddings visualization. 
Loss vs Epoch
Model Performance
![performance](https://github.com/user-attachments/assets/8615cc4d-5771-4c08-afd4-0514490b0b6f)
![validation accuracy](https://github.com/user-attachments/assets/ab4b9b92-aeaf-4eb3-9674-b32f29c56edd)
![PCA + t-SNE img](https://github.com/user-attachments/assets/f07d25cf-31b3-4d2b-a19c-c85e76a00a44)



Sample Predictions:
Sample texts: ['The product quality is great!', 'This is a terrible purchase.']
Predicted sentiments: [2 1]

