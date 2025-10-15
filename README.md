# Spam_Ham
A custom Hindi SMS dataset (2,500 messages) through manual extraction, ensuring balanced represen- tation of spam/ham (non-spam) samples for robust model training.
Performed text preprocessing: Cleaning (removing noise, special characters, normalization), Label encoding for
binary classification (spam=1, ham=0) and Handling missing data via contextual imputation.
Engineered linguistic & statistical features: Message length, word count, punctuation density. Lexical features
(presence of spam-trigger keywords, monetary symbols).
Utilized TF-IDF vectorization to convert Hindi text into high-dimensional sparse embeddings, preserving se-
mantic relevance.
Conducted model benchmarking using LazyPredict, evaluating 20+ ML algorithms for optimal performance.
Random Forest classifier achieved 97% accuracy (highest among peers), demonstrating superior feature impor-
tance handling in imbalanced text data.
Tech Stack: Python, Scikit-learn, Pandas, NLTK, TF-IDF, LazyPredict, Matplotlib
