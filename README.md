**German to english translation using encoder-decoder model using attention implemented in tensorflow**
(As a part of Machine learning course project)
The embeddings are produced using word2vec.

You can set the number of sentences considered for training by changing sentences_to_read

- Dataset used : german - english Europarl Parallel corpus(The dataset can be found at https://nlp.stanford.edu/projects/nmt/data/wmt14.en-de/)
- Library used : seq2seq(tensorflow)
- Trained for 60,000 iterations(can be changed)
- hidden size can be changed by changing num_units
- Embedding(word2vec)(trained embeddings are stored in the embeddings folder otherwise you can train word2vec using gensim library)
- Dictionary of vocabulary (taken from  https://nlp.stanford.edu/projects/nmt/data/wmt14.en-de/)
- maximum sentence length = 61 (can be changed by changing source_sequence_length and target_sequence_length) 
- used Adam optimiser

