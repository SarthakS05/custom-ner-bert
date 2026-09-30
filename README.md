# Custom NER with BERT

Python code-cell export of a named-entity-recognition example using a pretrained BERT token-classification model and the English WikiANN dataset. It includes dataset preparation, training, evaluation, inference, and saving the model.

## Requirements

Install the notebook's dependencies with:

```bash
python -m pip install transformers seqeval datasets pandas numpy scikit-learn torch
```

A CUDA-capable GPU is optional; training falls back to CPU.

## Usage

```bash
python custom_ner_bert.py
```

This is an export of the notebook code, not an end-to-end validated application. Review the dataset/model setup before running; the notebook's training cells may need adjustment for the selected Transformers version and dataset class API.
