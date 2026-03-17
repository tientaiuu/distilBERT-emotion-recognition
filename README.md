# Emotion Analyzer: distilBERT-based Text Emotion Classification

A web application that uses a fine-tuned distilBERT model to recognize and classify text emotions. It features a terminal-style interface for analyzing user sentiment to assist in understanding text feedback.

## Key Features
- Long Text Processing: Splits texts exceeding 512 tokens into chunks (default 450 tokens with 50-token overlap) and averages the predictions.
- Multilingual Support: Detects language and translates Vietnamese input to English using Google Translator before analysis.
- Text Normalization: Converts input to lowercase, removes non-alphanumeric characters, and strips extra spaces.

## Model & Dataset
- Dataset: Trained on the dair-ai/emotion dataset.
- Classes: sadness, joy, love, anger, fear, and surprise.
- Architecture: distilbert-base-uncased. Retains 97% of BERT's performance with 60% faster inference.
- Performance: 94% accuracy on the validation set and 93% accuracy on the test set.

## UI Preview
 <img width="1512" height="828" alt="Ảnh màn hình 2026-03-14 lúc 14 42 42" src="https://github.com/user-attachments/assets/ccb76639-5918-4808-9061-38f2ced469c1" />
 
<img width="1512" height="827" alt="Ảnh màn hình 2026-03-14 lúc 14 39 38" src="https://github.com/user-attachments/assets/fdb0036e-913a-4f6f-97ac-c4b8744629f2" />


 
