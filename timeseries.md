# Sequence Data

Study of machine learning algorithms designed for sequential data is known as sequence learning

In a neural network, you have one output per input. You have an image and you have a label, for instance. There is no way you can input image after image on Neural Networks and get an output based on all of them. The nature of neural networks make them unable to process sequential data.

So, in a feed forward neural network, output at a time t is independent of the output at time \(t-1\).

On the other hand, RNNs work very well with sequential data. They have a mechanism of “remembering” the previous inputs and producing an output based on all of the inputs. This makes them well-suited for sequential type of data such as text, audio, video or any time-series data.

