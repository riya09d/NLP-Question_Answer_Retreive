# NLP-Question Answer Retrieval

## Overview
This project utilizes semantic search to retrieve relevant passages from Simple English Wikipedia based on user queries or questions. It leverages the `nq-distilbert-base-v1` model trained on the Natural Questions dataset, which contains real questions from Google Search along with annotated data from Wikipedia providing the answers.

## Dataset
The dataset used for this project is the Simple English Wikipedia dataset from November 1, 2020, which can be accessed [here](https://public.ukp.informatik.tu-darmstadt.de/reimers/sentence-transformers/datasets/simplewiki-2020-11-01.jsonl.gz).

## Dependencies
- [sentence-transformers](https://huggingface.co/models?library=sentence-transformers&sort=downloads) library

## Installation
```bash
pip install -U sentence-transformers
```

## Usage
1. Download the Simple English Wikipedia dataset.
2. Initialize the `nq-distilbert-base-v1` model.
3. Encode the passages from the dataset using the model.
4. Define a function to get answers to user queries.
5. Provide a query to retrieve relevant passages.

## References
- [Natural Questions dataset](https://ai.google.com/research/NaturalQuestions/dataset)
- [Simple English Wikipedia dataset](https://public.ukp.informatik.tu-darmstadt.de/reimers/sentence-transformers/datasets/simplewiki-2020-11-01.jsonl.gz)
