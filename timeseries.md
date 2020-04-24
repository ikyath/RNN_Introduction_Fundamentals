# Sequence Data

Study of machine learning algorithms designed for sequential data is known as sequence learning

In a neural network, you have one output per input. You have an image and you have a label, for instance. There is no way you can input image after image on Neural Networks and get an output based on all of them. The nature of neural networks make them unable to process sequential data.

So, in a feed forward neural network, output at a time t is independent of the output at time \(t-1\).

On the other hand, RNNs work very well with sequential data. They have a mechanism of “remembering” the previous inputs and producing an output based on all of the inputs. This makes them well-suited for sequential type of data such as text, audio, video or any time-series data.

![Source : Google](.gitbook/assets/sequence.gif)



* The brain consists of billion of neurons, without any single duration.
* A Decision made now is not only based only on what you hear/see now.
* We can think and reason based on past inputs.
* What happens if we add feedback loops and memory to neural network.

Traditional neural networks can’t do this, and it seems like a major shortcoming. For example, imagine you want to classify what kind of event is happening at every point in a movie. It’s unclear how a traditional neural network could use its reasoning about previous events in the film to inform later ones.  


