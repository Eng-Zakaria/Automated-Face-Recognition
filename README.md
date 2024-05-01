Below is a modified documentation based on your provided code and its output:

---

# RNN Translation AR-EN

## Overview

This project implements a Recurrent Neural Network (RNN) for translating text from Arabic (AR) to English (EN). The model is trained on a dataset of parallel Arabic-English sentences to learn the translation patterns between the two languages. It utilizes an LSTM-based encoder-decoder architecture with attention mechanism.

## Requirements

- Python 3.x
- TensorFlow 2.x
- NumPy
- pandas
- NLTK

## Installation

1. Install the required packages:

   ```bash
   !pip install arabic_reshaper
   ```

2. Clone the repository and navigate to the project directory:

   ```bash
   git clone https://github.com/eng-zakaria/rnn-translation-ar-en.git
   cd rnn-translation-ar-en
   ```

## Usage

1. Run the notebook `RNN_Translation_AR_EN.ipynb` in your Jupyter environment or any compatible environment like Google Colab.
2. Ensure you have downloaded the dataset `ara_.txt` and placed it in the project directory.
3. Execute each cell in the notebook to preprocess the data, train the model, and evaluate its performance.
4. You can modify the notebook to experiment with different hyperparameters, model architectures, or datasets.

## Example Output

The training process typically involves multiple epochs, with each epoch displaying the training and validation loss. Below is an example output from a training session:

```
Epoch 1/5
8593/8593 [==============================] - 57s 6ms/step - loss: 0.7862 - val_loss: 1.5368
Epoch 2/5
8593/8593 [==============================] - 52s 6ms/step - loss: 0.6292 - val_loss: 1.4960
Epoch 3/5
8593/8593 [==============================] - 52s 6ms/step - loss: 0.5804 - val_loss: 1.5729
Epoch 4/5
8593/8593 [==============================] - 51s 6ms/step - loss: 0.5630 - val_loss: 1.5472
Epoch 5/5
8593/8593 [==============================] - 51s 6ms/step - loss: 0.5460 - val_loss: 1.4822
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project is inspired by the works of many researchers in the field of Natural Language Processing (NLP) and machine translation.

---
