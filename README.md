
# Image Caption Generator - Flickr Dataset
# Overview
This project generates captions for 8k images from the Flickr dataset, using a CNN-LSTM multimodal approach. Features from both images and captions are concatenated for predicting the next word. The model utilizes the VGG16 network for images and achieves a BLEU-1 Score of 0.544 and BLEU-2 Score of 0.319.

# Environment and Libraries
Developed on Kaggle, the project uses numpy, matplotlib, keras, tensorflow, and nltk.

# Neural Network Architecture
VGG16 processes images, and a CNN-LSTM network handles text.

# Evaluation Metrics
Model performance is measured by BLEU-1 (0.544) and BLEU-2 (0.319) Scores, reflecting word and bigram precision in generated captions.




