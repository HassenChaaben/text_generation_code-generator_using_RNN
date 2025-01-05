# Text Generation using RNN - Character Level

This project demonstrates how to generate text using a Recurrent Neural Network (RNN) at the character level. It uses the Linux kernel code as a training dataset to learn the patterns and structures of C code.

## How it works

1. **Data Preprocessing:**
   - The Linux kernel code is loaded and preprocessed.
   - The code is divided into sequences of characters with a fixed length.
   - Each character is converted into a numerical representation using one-hot encoding.

2. **Model Building:**
   - A Bidirectional LSTM model is created with two layers.
   - The model is trained on the preprocessed data to predict the next character in a sequence.

3. **Text Generation:**
   - A sampling function is used to generate text based on the model's predictions.
   - The `diversity` parameter controls the randomness of the generated text.
   - The generated text is printed to the console.

## Usage

1. **Clone the repository:**
