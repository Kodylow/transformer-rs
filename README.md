# Transformer-rs Notes

Transformer-rs is a Rust implementation of a Transformer using the Candle framework from Hugging Face. Follows the paper "Attention is All You Need" closely and the tutorial by https://www.youtube.com/watch?v=B2WRY21VV4A&list=PLIUa1VcxJuwmLW50WObscmBCC_5PsPpPe

# Input Embeddings

Input embeddings map every word in a sequence to a point in space where similar words and meanings are physically close. This mapping exists in an embedding space.

### Vocab Size

- Number of unique tokens in vocabulary

### Embedding Size

- Also called hidden size
- Represents dimensionality of each embedding vector
- Configured in Embedding Layer

### Embedding Matrix

- Dimensions: (vocab_size, d_model)
- Maps each token to its vector representation
