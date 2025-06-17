# CSE 153R Assignment 2

## Video Presentation

https://drive.google.com/file/d/1pxgK0dGNNsZ79z3uDc5QIg0WlP0PMz37/view?usp=drive_link

## Workbook

See workbook.html

## Final Outputs

See symbolic_unconditioned (2).mid and symbolic_conditioned (2).mid

## Task Overviews

### Unconditioned Symbolic Generation

- Goal: Train a model to generate new MIDI sequences without any prompt.
  
- Method: We tokenize MIDI files using the REMI scheme and train various RNN-based models (vanilla RNN, GRU, LSTM).

- Result: LSTM outperformed others in perplexity and musical coherence.

### Conditioned Symbolic Generation

- Goal: Given a melody, generate a harmonizing bassline.

- Method: LSTM-based encoder-decoder model trained on melody-bass token pairs.

- Result: Generated basslines aligned rhythmically and harmonically with input melodies, validated by audio comparisons.

### Evaluation

- Used Perplexity to compare model predictions with baselines (Uniform and Unigram).

- Plotted training and validation loss to assess model convergence.

- Created side-by-side audio comparisons of generated vs. true basslines.
