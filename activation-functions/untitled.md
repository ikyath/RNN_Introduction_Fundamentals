# Various Activation Functions

![alt text](https://miro.medium.com/max/1192/1*4ZEDRpFuCIpUjNgjDdT2Lg.png)

Selection of the activation function is mostly dependent on the problem and nature of the data. For example, sigmoid is suitable for networks where the output is in the range \[0, 1\]. However, the tanh and “sigmoid” activation functions saturate the neuron very fast and can vanish the gradient. Despite tanh, the non-zero centered output from sigmoid can cause unstable dynamics in the gradient updates for the weights. The ReLU activation function leads to sparser gradients and greatly accelerates the convergence of stochastic gradient descent \(SGD\) compared to the sigmoid or tanh activation functions. ReLU is computationally cheap, since it can be implemented by thresholding an activation value at zero. However, ReLU is not resistant against a large gradient flow and as the weight matrix grows, the neuron may remain inactive during training.

