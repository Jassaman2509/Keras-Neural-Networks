# Keras-Neural-Networks
TensorFlow is an open-source set of libraries for creating and working with neural networks, such as those used in Machine Learning (ML) and Deep Learning projects. 

Keras, on the other hand, is a high-level API that runs on top of TensorFlow. Keras simplifies the implementation of complex neural networks with its easy to use framework.
Keras is less error prone than TensorFlow, and models are more likely to be accurate with Keras than with TensorFlow. This is because Keras operates within the limitations of its framework, which include:

Computation speed: Keras sacrifices speed for user-friendliness. 
Low-level Errors: sometimes you’ll get TensorFlow backend error messages that Keras was not designed to handle.
Algorithm Support – Keras is not well suited for working with certain basic machine learning algorithms and models like clustering and Principal Component Analysis (PCM). 
Dynamic Charts – Keras has no support for dynamic chart creation.

Models are the core entity you’ll be working with when using Keras. The models are used to define TensorFlow neural networks by specifying the attributes, functions, and layers you want. 

Keras offers a number of APIs you can use to define your neural network, including:

Sequential API, which lets you create a model layer by layer for most problems. It’s straightforward (just a simple list of layers), but it’s limited to single-input, single-output stacks of layers.
Functional API, which is a full-featured API that supports arbitrary model architectures. It’s more flexible and complex than the sequential API.
Model Subclassing, which lets you implement everything from scratch. Suitable for research and highly complex use cases, but rarely used in practice.
