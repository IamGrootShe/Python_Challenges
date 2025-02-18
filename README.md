Summary
Dataset: Spam email classification dataset.
Preprocessing:
Renamed columns.
Converted labels (ham → 0, spam → 1).
Checked and handled missing values.
Data Splitting: 80% training, 20% testing.
Vectorization: TF-IDF with unigrams & bigrams (max 2000 features).
Model: Naïve Bayes (MultinomialNB) for classification.
Evaluation:
Accuracy.
Precision, Recall, and F1-score.
Confusion Matrix.
