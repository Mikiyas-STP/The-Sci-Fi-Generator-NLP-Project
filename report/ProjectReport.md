# Sci-Fi Story Generator using RNN
### Final Project – NLP for Creatives (Peckham DAZ Programme 2024/25)
### Code & Data Sources

- **Code Repository**: [GitHub Link to Project] (Replace with your actual GitHub URL)
- **Dataset**: Extracted from Project Gutenberg – “A Journey in Other Worlds” by John Jacob Astor (public domain sci-fi text).
- **Data Access**: Retrieved using Python's `requests` library and cleaned using `re` and `nltk`.

### Ethical Statement

- The text used for training is in the public domain and contains no personal or sensitive information.
- The model is designed solely for creative storytelling and has no predictive or decision-making function.
- It may generate grammatically inconsistent or culturally biased outputs due to the limitations of the training text and architecture.
- All outputs are fictional.
- **LLM Disclaimer**: I used ChatGPT to help guide and explain coding steps, structure the report, and refine ideas. All code was tested, reviewed, and adapted by me.
### Reflection & Learning Process

#### What I learned:
- How to tokenize and prepare a large text corpus for sequence modeling.
- How RNNs (specifically LSTM) work for text generation.
- How to implement, train, and evaluate a deep learning model using Keras/TensorFlow.

#### Challenges:
- Cleaning long and inconsistent text.
- Long training time (used Google Colab to speed this up).
- Managing memory usage during sequence creation and training.

#### What went well:
- Successfully generated sci-fi-like sentences.
- Learned to control randomness using seed phrases.
- Understood the power of sequence-to-sequence modeling.

#### What I'd do differently next time:
- Train with multiple sci-fi authors to reduce repetition.
- Explore more advanced models like GPT-2 or Transformer-based models.
- Add an interface or creative visualization.

### Additional Considerations
- This project could be extended into a creative writing tool or collaborative poetry bot.
- Could combine LSTM-based generation with a classifier to guide tone or genre (comedy, horror, etc).
- Markov Chains or Transformers could be used to compare generation styles.
