### Weights
Weights near zero mean changing this input will not change the output. Many algorithms will automatically set those weights to zero in order to simplify the network.

### Bias 
Bias terms are additional constants attached to neurons and added to the weighted input before the activation function is applied.

### AW + B --> W = Weights, B = Bias 
### Optimization Algorithms
Helps to min or max a function (in ML, the Error Function). Two types-

1.  First Order OA - Minimizes or maximizes loss using its gradient values with respect to the parameters. First Order Derivative. Most widely used algo is Gradient Descent. Gradient reperesented by the Jacobian Matrix which is a Matrix of first order partial derivatives(gradients).
2.  Second Order OA - Minimizes or maximizes loss using secong ordr derivative. More costly than FOOA but better performance. Hessian is a matrix of second order partial derivatives.

### Synapse 
Synapses are like roads in a neural network. They connect inputs to neurons, neurons to neurons, and neurons to outputs. In order to get from one neuron to another, you have to travel along the synapse. Each connection between two neurons has a unique synapse with a unique weight attached to it. When we talk about updating weights in a network, we’re really talking about adjusting the weights on these synapses.

### Weighted Inputs 
Notice, it’s exactly the same equation we use with linear regression! In fact, a neural network with a single neuron is the same as linear regression! The only difference is the neural network post-processes the weighted input with an activation function.

### Activation Functions 
Activation functions live inside neural network layers and modify the data they receive before passing it to the next layer. Activation functions give neural networks their power — allowing them to model complex non-linear relationships. By modifying inputs with non-linear functions neural networks can model highly complex relationships between features. Types of function -

1.  Non-Linear 
2.  Continously Differentiable 
3.  Fixed Range 
