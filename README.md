
📚 Amharic-Tigrigna Text Similarity Analyzer


This Python project performs lexical and phonetic similarity analysis between Amharic and Tigrigna texts. It utilizes a Grapheme-to-Phoneme (G2P) conversion dictionary and computes word/phoneme frequency and overlap scores to assess how similar the texts are. 🛠 Features

✅ Read and clean Amharic and Tigrigna texts

✅ Grapheme-to-Phoneme transcription using a built-in mapping dictionary

✅ Word frequency analysis

✅ Word overlap score

✅ Phoneme distribution analysis

✅ Phoneme overlap score

✅ Support for UTF-8 encoded Ethiopic scripts

🧠 How It Works

Read text files from an assets/ directory.

Clean the text by removing punctuation and extra spaces.

Transcribe text into phonemes using a predefined g2p_mapping dictionary.

Compute frequency of words and phonemes.

Calculate overlap scores:

    Word Overlap Score = Intersection / Union of words

    Phoneme Overlap Score = Intersection / Union of phonemes