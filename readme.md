project steps

<----------------------Part 1----------------------------------->

=> Load and inspect the dataset.
=> Perform text preprocessing (lowercasing, removing special characters, stopwords, tokenization).
=> Split the dataset into training and development sets while maintaining label distribution.

<----------------------Part 2----------------------------------->

=> Convert text into numerical features using TF-IDF or CountVectorizer.

=> Train different Multi-Layer Perceptron (MLP) architectures on these features.

=> Evaluate performance using accuracy, precision, recall, and F1-score.

<----------------------Part 3----------------------------------->

=> Load pre-trained embeddings (e.g., word2vec, GloVe, or fastText).

=> Convert abstracts into sequences of word embeddings.

=> Merge word embeddings into fixed-size vectors using averaging, summing, or pooling.

=> Train a classifier on the fixed-size vectors.

=> Experiment with frozen vs. fine-tuned embeddings.

<----------------------Part 4----------------------------------->

=> Use RNN, LSTM, or GRU to process word sequences.

=> Extract a fixed-size representation using last state, first state (for bidirectional RNNs), concatenation, or pooling.

=> Train a classifier on these representations.

=> Compare different RNN architectures.

<----------------------Part 5----------------------------------->

=> Compare different feature extraction techniques (BoW vs. pre-trained embeddings vs. RNN embeddings).

=> Compare different classification models (MLP vs. RNN variants).

=> Document and analyze the results.
