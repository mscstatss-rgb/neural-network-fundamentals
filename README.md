# neural-network-fundamentals
A fundamentals-level neural network project trained on a small dataset to generate names character by character. The project explores tokenization, embeddings, forward propagation, loss calculation, backpropagation, gradient descent, and neural network training using PyTorch.

## Project Workflow

1. **Dataset Preparation**

   * `name.txt` contains the training dataset with a collection of people's names used to train the neural network.

2. **Data Representation**

   * Convert characters/words into integer representations.
   * Convert the integer representations into learned embeddings that can be used as inputs to the neural network.

3. **Parameter Initialization**

   * Set up and initialize the model parameters, including weights and biases.

4. **Learning Rate Selection**

   * Experiment with different learning rates to identify a suitable learning rate for training the model effectively.

5. **Model Training & Validation**

   * Train the neural network on the training dataset.
   * Evaluate its performance on a validation set to monitor how well the model generalizes to unseen data.

6. **Name Generation**

   * Use the trained neural network to generate new names character by character.
   * Evaluate the generated names to understand how well the model has learned the patterns present in the training data.

