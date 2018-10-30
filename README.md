# CNN-1
CNNtrain_1 is a tensorflow based convolutional neural network.

Defining terms:

Learning rate: It is defined in the context of optimization and helps in minimizing the loss function of the neural network.

Epoch: An epoch is a single step in training a neural network.

Batch: Total number of training examples present from the data.

Placeholders: Placeholders are objects that allow you to feed in data of a specific type.

Weights: A set of weighted inputs allows each artificial neuron or node in the system to produce related outputs.

Biases:Biases are values associated with each node in the input and hidden of a network.

Activation Function: The activation function of a node defines the output of that node, or "neuron," given an input or set of inputs.                        This output is then used as input for the next node and so on until a desired solution to the original problem is                        found.

ReLu:(Rectified Linear Unit) A non-Linear Activation Function

Max Pooling: Max pooling uses the maximum value from each of a cluster of neurons at the prior layer.
             Reduce the number of parameters in your network (pooling is also called “down-sampling” for this reason)
             To make feature detection more robust by making it more impervious to scale and orientation changes

Softmax activation: The softmax activation function in the output layer of the neural network is to represent a categorical distribution                     over a class of labels and give an output.

Steps involved in training as mentioned in the Adventures of ML website:

1. Create an optimiser
2. Create correct prediction and accuracy evaluation operations
3. Initialize operations
4. Determine the number of batch runs within an training epoch.
5. For each epoch:
5.1 For each batch:
5.1.1 Extract batch data
5.1.2 Run the optimiser and cross entropy operations
5.1.3 Add to average Cost
5.2 Calculate current test accuracy
5.3 Print out some results
6. Calculate final results and print("Training Complete")
   
