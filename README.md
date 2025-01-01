# SENTIMENT ANALYSIS A COMPARATIVE ANALYSIS BETWEEN CLASSICAL ML AND TRANSFORMERS BERT AND DISTILBERT
This project focuses on classifying tweets into predefined categories using a labeled dataset. The goal is to 
leverage both classical machine learning techniques and modern Transformer-based architectures to achieve high 
accuracy and efficiency in tweet classification.

## Methodology
- Classical Machine Learning: Traditional algorithms such as Naive bayes were employed as baselines for comparison.
  These models used TF-IDF vectorization to represent the text data numerically.
- BERT (Bidirectional Encoder Representations from Transformers): A pre-trained deep learning model designed
  for understanding the context of words in a sentence by processing text bidirectionally. Its large size
  and deep layers allow it to capture nuanced features of tweet text.
- DistilBERT: A smaller, distilled version of BERT that maintains 97% of BERT's performance while being faster
  and more resource-efficient. It is well-suited for tasks where computational efficiency is essential without
  sacrificing much accuracy.

## Results
- DistilBERT emerged as the best-performing model, achieving the highest accuracy and efficiency. Its smaller
  size made it quicker to train and deploy while still delivering excellent results.
- BERT followed closely, showcasing robust performance but with a higher computational cost due to its larger size.
- Classical machine learning models performed adequately but were outshined by the Transformer architectures.

## Conclusion
The success of Transformer-based models, especially DistilBERT, highlights the importance of leveraging pre-trained 
architectures for text classification tasks. Their ability to understand context and semantics gives them a significant 
edge over classical approaches.
