# Vanishing Gradient

As we know, the gradient descent algorithm finds the global minimum of the cost function that is going to be an optimal setup for a network

In RNNs

* Information travels through time, which means that information from previous timepoint is fed as input to the next timepoint.
* We can calculate the error, at each point.

Lets look into error which is calcualted after forward pass,

In the backpropagation process, we adjust our weight matrices with the use of a gradient. In the process, gradients are calculated by continuous multiplications of derivatives. The value of these derivatives may be so small, that these continuous multiplications may cause the gradient to practically “vanish”.

RNNs suffer from the problem of vanishing gradients, which hampers learning of long data sequences

For instance we have a sentence like ' I went to France, - - - -. And now I speak \_? '

So in this particular sentence, after _France_, there are say 4-5 words and then the sentence , _I speak_ and we need to predict the next word. In order to do that , we need to go way back in the sentence to understand the context and then predict the word as _'French'_ in this case.

This is commomly referred to as the 'Long term dependency'

