# ESC50 Challenge

## Project Description

This project focuses on the ESC50 Challenge. The ESC-50 dataset is a labeled collection of 2000 environmental audio recordings suitable for benchmarking methods of environmental sound classification.
The dataset consists of 5-second-long recordings organized into 50 semantic classes (with 40 examples per class), loosely arranged into 5 major categories.

### Key Components
1. **Data Generation**: The `dataset_ESC50.py` file is used to generate the data.
2. **Training Pipeline**: The `Train_crossval.py` file provides the training pipeline, in which a 5-fold cross-validation training is conducted.
3. **Model Storage**: The trained models are stored in the `result` folder.
4. **Testing**: The `test_crossval.py` file tests all 5 folds and calculates a mean accuracy.
5. **Results**: The average accuracy of the model is 83.2%.

## Tech Stack
- Torch
- scikit-learn (sklearn)
- librosa

