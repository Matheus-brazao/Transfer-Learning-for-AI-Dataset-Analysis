# Dataset AI: Transfer Learning (Baseline vs VGG16)
> This project was developed as part of the DIO (Digital Innovation One) course on Deep Learning Bootcamp.


This project reproduces the **baseline CNN** and **transfer learning with VGG16** experiment.

## What this project does
- Trains a **baseline CNN from scratch** (reference model).
- Trains a **transfer learning model using VGG16 pretrained on ImageNet** (frozen base + new head).
- Compares the validation accuracy curves between baseline and transfer.
- Evaluates on a test split and shows quick predictions (2 images).

## How to run
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the script `transfer_learning_min.py` and run all cells.
3. Edit the line inside the script to choose the dataset:
   ```python
   DATA_SOURCE = "tfds:cats_vs_dogs"
