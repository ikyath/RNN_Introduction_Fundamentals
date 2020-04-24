# Architecture of RNN

The below image show a RNN being unfolded to a full network, x\_t is input to the network at time t, h\_t is the hidden state at time t also referred to as the memory of the network. It is calculated based on previous hidden state and current input.

Represented by

ℎ\_𝑡=𝑓\(𝑈𝑥\_𝑡+𝑊ℎ\_𝑡−1+𝑏\_ℎ\)  


![](../.gitbook/assets/rnn.png)

Here U and W are weights for input and previous state value input, 𝑏ℎbh is the bias associated to the hidden network and f is the non-linearity applied to the sum to generate final cell state.

And ou**t**put at time t is calculated as shown below :

𝑂\_𝑡=𝑓\(𝑊ℎ\_𝑡+𝑏\_0\)

b\_0 is the bias for the output layer

