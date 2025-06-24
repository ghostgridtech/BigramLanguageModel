# BigramLanguageModel
A simple character-level Bigram Language Model built with PyTorch and trained on The Wizard of Oz. This project explores how neural networks can generate text by predicting one character at a time using only bigram probabilities. Great for learning the basics of language modeling and deep learning with minimal code.

Overview

This is a minimal and educational implementation of a language model to demonstrate how character-level generation works using just bigrams (2-character sequences). It can generate random text based on the patterns it learned from the source material.

🚀 Features

🔡 Character-level bigram modeling

📚 Trained on The Wizard of Oz (public domain text)

🧠 Built using clean PyTorch code

📝 Text generation function to produce Oz-inspired nonsense

🧪 Includes validation and loss estimation for basic evaluation


How the Bigram Model Works

The model uses a single nn.Embedding layer of shape (vocab_size, vocab_size)

Each character (token) is mapped to a vector that scores all possible next characters

During training, it uses cross-entropy loss to adjust these scores

During generation, it samples from the probability distribution of the next character

 Want to Go Further?

Upgrade the model to:

🔁 Trigrams or n-grams

🧶 Recurrent Neural Networks (RNNs)

⚡ Transformers for state-of-the-art text generation

📖 License

This project is licensed under the MIT License.Wizard of Oz text is in the public domain.

