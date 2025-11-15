# TheraMind
*(Discovering Emotional Patterns in Clustering Conversations)*

# Project Summary
TheraMind explores emotional patterns inside mental health counseling conversations. By using text clustering, we analyze how people express emotions such as anxiety, stress, sadness, or hope, and group similar messages together. The goal is to understand common emotional patterns in counseling settings and how they appear across conversations.

# Methods
This project follows a simple, structured NLP workflow:
- Data Loading: Counseling dataset from HuggingFace.
- Text Cleaning: Lowercasing, removing punctuation, and stopword filtering.
- Feature Engineering: TF-IDF vectorization to convert text into numerical form.
- Clustering: K-Means and Hierarchical Clustering to discover hidden emotional groups.
- Visualization: Elbow Method, Silhouette Score, PCA plots, and dendrograms.
- Interpretation: Identifying emotional tones by analyzing top keywords and sample messages in each cluster.

# Tools & Tech
- Language: Python
- Libraries: scikit-learn, Pandas, NumPy, Matplotlib, NLTK, datasets (HuggingFace)
- Dataset: *https://huggingface.co/datasets/Amod/mental_health_counseling_conversations*

# Team
- Arturo G. Valle
- James Furdui

# Research Paper
A full research paper for TheraMind is currently being written. Once complete, it will be uploaded to a folder named "ResearchPaper" in this repository.

Stay tuned!!!s
