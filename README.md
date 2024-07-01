# RNN Text Generation

RNN-Based Text Generation

### Objectives:

Implement a simple RNN for text generation to deepen your understanding of how recurrent neural networks can be used to model sequences and generate text based on learned patterns.

1. RNN Model Implementation (10 Points)
   •Implement a basic Recurrent Neural Network model from scratch using PyTorch or
   TensorFlow. Your model should include an embedding layer, at least one RNN layer,
   and a fully connected layer for output. Refer to the "Recurrent Neural Networks
   (RNN)"section of the lectures for guidance on the architecture.
   •Use the "Long Short-Term Memory RNNs (LSTMs)"section as a reference to enhance
   your model with LSTM cells to improve its ability to capture long-term dependencies
   in text.
2. Dataset Preparation (10 Points)
   •Select a small text dataset for training your model. This could be a collection of
   poems, song lyrics, or any text of your choice. Preprocess the data by tokenizing the
   text into sequences and converting them into numerical format suitable for training
   your RNN.
3. Training (10 Points)
   •Train your RNN model on the prepared dataset. Aim to optimize the model to
   predict the next word in a sequence based on the given context. Adjust hyper-
   parameters such as learning rate, number of epochs, and hidden layer dimensions to
   improve performance.
4. Text Generation (10 Points)
   •Once trained, use your model to generate text. Start with a seed sentence or word,
   then predict the next word using your model. Append the predicted word to your
   text and use the updated sequence as the new input to generate the next word.
   Repeat this process to generate a text of at least 100 words.
5. Analysis (10 Points)
   •Analyze the generated text. Discuss how well your model captures the style and
   coherence of the chosen dataset. Reflect on the performance of the basic RNN
   model versus the LSTM-enhanced version. Consider the effects of different hyper-
   parameters on the quality of the generated text
