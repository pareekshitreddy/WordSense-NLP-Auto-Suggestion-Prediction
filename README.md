# WordSense: NLP Auto-Suggestion & Prediction

This repository contains the code and research paper related to next word prediction in natural language processing (NLP). The goal of this project is to predict the next word in a given sentence, which has various applications in text generation, autocomplete, and more.

## Overview

- **Auto-Suggest Next Word**: The paper discusses the importance of predicting the next word in NLP, highlighting its everyday use and potential market growth.

- **Data and Modelling**: We used Project Gutenberg datasets, specifically from Plato and Shakespeare, for training n-gram, LSTM, and GPT language models.

- **Results**: The paper presents perplexity as the evaluation metric, showing that fine-tuned GPT models outperform others, especially on the Plato dataset.

## Getting Started

1. Clone this repository: `[git clone [your-repo-url]](https://github.com/pareekshitreddy/WordSense-NLP-Auto-Suggestion-Prediction.git)`
2. Download the Project Gutenberg datasets (Plato and Shakespeare) and preprocess the text.

## Usage

- Train the language models using the provided scripts.
- Evaluate the models using perplexity.
- Fine-tune the GPT model on additional data for better performance.

## Future Work

Suggestions for future work include:
- Training models on longer sequences.
- Using larger corpora for improved word prediction and sentence generation.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
