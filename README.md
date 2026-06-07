Word-Based Tokenizer

This project demonstrates a complete tokenization workflow implemented in the notebook.

1. Choose a text corpus (here, The Verdict) and load it into Python.
2. Split the text into tokens using regular expressions (words and punctuation).
3. Build a vocabulary of unique tokens.
4. Assign a unique integer token ID to each vocabulary item.
5. Convert corpus tokens into token ID sequences.
6. Implement an encode function to map input text to token IDs.
7. Implement a decode function to reconstruct text from token IDs.
8. Extend the tokenizer with special tokens (<|unk|> and <|endoftext|>) in SimpleTokenizerV2.
9. Demonstrate byte pair encoding (BPE) with tiktoken (GPT-2 tokenizer).
10. Create training samples with a sliding window and build a PyTorch DataLoader.
11. Generate token embeddings and positional embeddings for model inputs.