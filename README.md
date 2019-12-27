# Coding a neural network for XOR logic from scratch
In this repository, I implemented a proof of concept of all my theoretical knowledge of neural network to code a simple neural network from scratch in Python without using any machine learning library.

### Introduction:
Some machine learning algorithms like neural networks are already a black box, we enter input in them and expect magic to happen. Still, it is important to understand what is happening behind the scenes in a neural network. We can use libraries such as Keras to make our life easy but if we dont understand what happens inside a neural network, then we can easily get stuck in an infinite loop without understanding what is going wrong with our neural network. Coding a simple neural network from scratch acts as a Proof of Concept in this regard and further strengthens our understanding of neural networks.

In this project, a single hidden layer neural network is used, with sigmoid activation function in hidden layer units and sigmoid activation function for output layer too, since the output of XOR logic is binary i.e. 0 or 1 only one neuron is in the output layer. The maths behind neural network is explained below:

### Explanation of Maths behind Neural Network:
Following work shows the maths behind a single hidden layer neural network: 

![pic1](https://user-images.githubusercontent.com/41015749/71526629-c3ec9c80-28a5-11ea-85db-13a6ecd9a432.jpg)

![pic2](https://user-images.githubusercontent.com/41015749/71526634-c818ba00-28a5-11ea-993d-f527a397f202.jpg)

![pic3](https://user-images.githubusercontent.com/41015749/71526635-c9e27d80-28a5-11ea-86b0-3e019fd15f16.jpg)

![pic4](https://user-images.githubusercontent.com/41015749/71526636-cb13aa80-28a5-11ea-984e-8f8ca64eab18.jpg)

### Results
Following image shows the loss function for our network, it can be seen that it is decreasing.

![pic5](https://user-images.githubusercontent.com/41015749/71526684-feeed000-28a5-11ea-86e7-ecffc4d5e2e8.jpg)

Following are the predictions of neural network on test inputs:

![pic6](https://user-images.githubusercontent.com/41015749/71526730-3cebf400-28a6-11ea-870a-a36c946b445d.jpg)

Please view the jupyter notebook file attached, it has the code with comments to make it easy to understand for the readers.

### Conclusion:
Coding a neural network from scratch strengthened my understanding of what goes on behind the scenes in a neural network. I hope this project helps other readers understand the working of a neural network.
