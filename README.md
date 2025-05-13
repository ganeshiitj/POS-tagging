# HMM POS Tagger

This project implements a Part-of-Speech (POS) tagger using Hidden Markov Models (HMM), supporting both first-order and second-order models. It also includes optional word-dependent emissions and tag collapsing into 4 categories (N, V, A, O).

## Features
- First and second-order HMM
- Word-dependent emission (optional)
- 36-tag and 4-tag evaluation
- Handles unknown words
- Viterbi decoding
- Accuracy evaluation (overall, per-tag, unknown words)

## Usage
1. Install requirements:
2. Run the code:
3. Ensure `penn-data.json` is in the same directory.

## Tag Collapsing (4-tag)
- **N**: NN, NNS, NNP, NNPS
- **V**: VB, VBD, VBG, VBN, VBP, VBZ
- **A**: JJ, JJR, JJS, RB, RBR, RBS
- **O**: All others

## Output (Example)
Testing First Order HMM
Unknown word accuracy: 0.2067
Overall accuracy: 0.8766
