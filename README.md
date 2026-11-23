# Chess Classification Using PyCaret

## Project Overview

This project uses machine learning to predict whether a chess endgame position is classified as a win or no win. It uses the Chess (King-Rook vs. King-Pawn) dataset from the UCI Machine Learning Repository.

## Abstract

The project uses 3,196 chess positions and 35 categorical input features to predict two outcomes: won and nowin. I used PyCaret to compare multiple classification algorithms with an 80/20 train-test split and five-fold cross-validation. LightGBM was selected as the best-performing model, achieving approximately 98% cross-validation accuracy. On the held-out test dataset, the model achieved 98.59% accuracy and an AUC of 0.9992, correctly classifying 631 out of 640 positions.

## Technologies Used

- Python
- Jupyter Notebook
- PyCaret
- Pandas
- UCI Machine Learning Repository

## Results

- Best Model: LightGBM
- Test Accuracy: 98.59%
- Test AUC: 0.9992
- Correct Predictions: 631 out of 640

## Video Presentation

[Watch the 5-minute project presentation](PASTE_YOUR_VIDEO_LINK_HERE)

## Dataset

UCI Chess (King-Rook vs. King-Pawn): https://archive.ics.uci.edu/dataset/22/chess+king+rook+vs+king+pawn

## License

MIT License
