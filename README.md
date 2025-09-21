IMDB Movie Reviews Sentiment Analysis

Overview:
I built a sentiment analysis model to classify IMDB movie reviews as positive, neutral, or negative using BERT in both TensorFlow and PyTorch. The model achieves ~89% validation accuracy and effectively classifies reviews into positive, neutral, and negative categories.

Used IMDB Dataset (Kaggle)

Key Steps:
Cleaned text (removed URLs, special characters, and lowercased text).
Tokenized reviews with bert-base-uncased tokenizer.
Mapped sentiments: positive → 2, neutral → 1, negative → 0.
Split data into training (80%) and test (20%) sets.
Trained a BERT-based classifier for sentiment prediction.

Visualizations:
Training/Validation Loss and Accuracy over epochs. 

Training Loss: [0.316, 0.189, 0.101, 0.053, 0.035] 

Validation Accuracy: [0.896, 0.896, 0.897, 0.899, 0.897]

BLEU Score over Epochs.
Heatmap of Sentence Similarities.
PCA & t-SNE scatter plots for embeddings visualization. 
Loss vs Epoch
Model Performance

Sample Predictions:
Sample texts: ['The product quality is great!', 'This is a terrible purchase.']

Predicted sentiments: [2, 1]

![performance](https://github.com/user-attachments/assets/8615cc4d-5771-4c08-afd4-0514490b0b6f)
![PCA + t-SNE img](https://github.com/user-attachments/assets/f07d25cf-31b3-4d2b-a19c-c85e76a00a44)
