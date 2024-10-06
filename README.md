# Grammar Correction Model using BERT

This repository contains a fine-tuned BERT-based model for sequence classification, trained to predict whether a sentence is grammatically correct or not.

## Dataset

The model is trained using the [JFLEG](https://huggingface.co/datasets/jfleg) dataset, which provides sentences along with corrections. The dataset is automatically downloaded using the `datasets` library.

## Model Details

- **Model**: `bert-base-uncased` pre-trained BERT model.
- **Task**: Binary classification (grammatically correct vs. incorrect).
  - `Label 0`: Sentence is grammatically correct.
  - `Label 1`: Sentence is grammatically incorrect.
  
## Dependencies

To run this project, you need the following Python libraries:
- `transformers`
- `datasets`
- `torch`

You can install them using pip:

```bash
pip install transformers datasets torch
