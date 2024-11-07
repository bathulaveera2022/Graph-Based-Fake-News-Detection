Fake News Detection Using Machine Learning
Overview
This project explores advanced machine learning techniques to enhance the accuracy and reliability of fake news detection, focusing on Graph Convolutional Networks (GCNs). We compare the performance of GCNs with traditional models like Random Forest classifiers and neural networks, using a Twitter dataset.

Objectives
Investigate the effectiveness of various machine learning models in detecting fake news on social media.
Leverage GCNs to capture both local and global patterns in Twitter's social network.
Compare model performance to traditional classifiers like Random Forest and neural networks.
Identify strengths and limitations of these models in the context of misinformation.
Methodology
Data: The project uses a Twitter dataset, focusing on detecting fake news through user interactions, tweet content, and network features.
Models: We implemented and tested:
Graph Convolutional Networks (GCNs) for capturing complex relationships in the Twitter social network.
Neural Networks to utilize deep learning techniques for effective feature extraction and pattern recognition.
Random Forest Classifiers for comparison due to their robustness and interpretability.
Evaluation: Models were evaluated based on their accuracy, interpretability, and robustness, with a particular focus on their ability to handle misinformation on Twitter.
Results
Neural Networks: Achieved superior accuracy (64.91%) compared to Random Forest classifiers (57.04%) due to better feature extraction and deep learning capabilities.
Random Forest: Demonstrated robustness and interpretability, despite being slightly less accurate than neural networks.
GCNs: Showed promise in capturing both local and global patterns in the Twitter network, improving fake news detection capabilities.
Challenges and Future Work
Class Imbalance: One of the challenges was handling class imbalances in the dataset.
Dataset Expansion: Future work will include expanding datasets to cover a broader range of social media platforms and languages.
Model Explainability: Further work will focus on improving the explainability of the models, especially in the context of complex graph-based learning.
Conclusion
This research highlights the strengths and limitations of various machine learning models in detecting fake news on Twitter. The advancements made in model accuracy and network pattern detection pave the way for more reliable fake news detection systems, contributing to the overall integrity of information on social media platforms.
