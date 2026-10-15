# T5 Text Summarizer

An NLP project that explores automatic text summarization using the T5 (Text-to-Text Transfer Transformer) model. Built with Python, PyTorch, and Hugging Face Transformers.

## Overview

Text summarization is a Natural Language Processing (NLP) task that converts lengthy text into a shorter version while preserving its key information.

This project uses the pretrained T5-small model to generate summaries from input text and explores fine-tuning on the SAMSum dialogue summarization dataset.

The project is being developed as part of my learning journey in Artificial Intelligence and Machine Learning.

## Objectives

* Understand the fundamentals of transformer-based language models.
* Generate summaries from input text using T5.
* Preprocess and tokenize dialogue data.
* Experiment with fine-tuning a pretrained model.
* Explore methods for evaluating summary quality.

## Technologies Used

* Python
* PyTorch
* Hugging Face Transformers
* SentencePiece
* Pandas
* JupyterLab

## Model

**T5-small**

T5 is a text-to-text transformer model that can be used for various Natural Language Processing tasks, including summarization.

The project uses a pretrained T5-small checkpoint and explores adapting it to dialogue summarization.

## Dataset

This project uses the SAMSum dataset, which contains conversations paired with human-written summaries.

The dataset files are not included in this repository. Users can access the dataset through the [SAMSum dataset page on Hugging Face](https://huggingface.co/datasets/Samsung/samsum).

## Project Structure

```text
T5-Text-Summarizer/
├── text_summarizer.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## Installation

### 1. Clone the repository

Replace `YOUR-USERNAME` with your GitHub username.

```bash
git clone https://github.com/YOUR-USERNAME/T5-Text-Summarizer.git
cd T5-Text-Summarizer
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch JupyterLab

```bash
jupyter lab
```

Open `text_summarizer.ipynb` and run the notebook cells in order.

The first model-loading step may download pretrained model files from Hugging Face.

## Current Status

This project is a work in progress.

The current implementation explores loading a pretrained T5 model, generating summaries, preprocessing dialogue data, and fine-tuning experiments.

The final training results and summary quality will be evaluated as development progresses.

## Future Improvements

* Evaluate summary quality using ROUGE metrics.
* Improve fine-tuning and training efficiency.
* Compare generated summaries with reference summaries.
* Experiment with different model configurations.
* Build an interactive interface using Streamlit.
* Document performance and limitations.

## Learning Outcomes

Through this project, I aim to gain practical experience with transformer models, text preprocessing, tokenization, model fine-tuning, and NLP evaluation.

## Author

Developed as a personal learning project in Artificial Intelligence, Machine Learning, and Natural Language Processing.
