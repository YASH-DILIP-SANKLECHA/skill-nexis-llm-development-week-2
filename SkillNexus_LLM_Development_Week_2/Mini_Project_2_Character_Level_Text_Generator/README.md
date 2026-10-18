# Mini Project 2 — Character-Level Text Generator

## Objective
Build a small character-level language model that generates short text from a starter character or sequence.

## Required outputs
- Training notebook
- Saved model checkpoint
- Training and validation loss results
- Ten generated samples

## Run
Install dependencies: `python -m pip install torch matplotlib jupyter`
Open `character_level_text_generator.ipynb` in VS Code and run all cells from top to bottom.

## Outputs created by the notebook
- `model/character_bigram_model.pt`
- `training_results.csv`
- `generated_samples.txt`

The included original educational dataset is dedicated to the public domain under CC0 1.0. This is a small teaching model: it predicts the next character from the current character and may generate incoherent text.
