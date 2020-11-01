
https://www.tensorflow.org/model_optimization/guide/pruning
    
<h5>Weight pruning means eliminating unnecessary values in the weight tensors. We are practically setting the neural network parameters’ values to zero to remove what we estimate are unnecessary connections between the layers of a neural network. This is done during the training process to allow the neural network to adapt to the changes.</h5>
<h5>An immediate benefit from this work is disk compression: sparse tensors are amenable to compression. Thus, by applying simple file compression to the pruned TensorFlow checkpoint, or the converted TensorFlow Lite model, we can reduce the size of the model for its storage and/or transmission.</h5>
<img src='neuralnetworklayersbeforeandafterpruning.png' width="600" height="500" />
