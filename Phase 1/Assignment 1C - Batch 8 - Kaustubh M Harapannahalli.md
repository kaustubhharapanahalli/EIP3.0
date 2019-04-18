Name: Kaustubh M Harapanahalli

Batch No.: 8

----------------------------------------------------------------------------------------------

Topic 1: **Convolution** 

Convolution is a process which helps us get to know by what factor a particular function overlaps another function. To get the amount of overlap that takes place, we perform the integration of these two different functions. 

![GIF of COnvolution Process](https://i.ibb.co/CJZLJWr/Wiki-Box-Conv-Anim.gif)

The convolution of two functions is defined by using the equation:

$f(t) * g(t) = \int_{-\infty}^{\infty}f(\tau)g(t-\tau)d\tau​$ 

Here the $*​$ indicates the convolution operation of two different functions over the scale of time which is denoted using $t​$ and the operation is performed over an infinite scale of time.

To give an example, let's say you have one function which is the sine wave and the second function is the cosine wave. If we perform the convolution of these two, we get the output as: $-\frac{\pi}{2}sin(x)​$

So this output tells us that, when we perform convolution of two different functions, we get the output which is another function. Thus, convolution of two functions give us a resultant function.

-----------------

Topic 2: **Filters**

When we hear the word filters, we can understand that filters are those things that allow only a certain required materials to pass through it. Similarly in Convolutional Neural Networks we have filters. To understand what is the meaning of filters with respect to CNN, let's consider the following image:![GIF of COnvolution Process](https://i.ibb.co/895fTNs/convolution-schematic.gif)



Here in the image, if you observe, we have a 3X3 yellow matrix which is running over a 5X5 matrix. This yellow matrix convolves with values present in the green matrix and the resultant value is seen in the pink matrix. This yellow matrix is a filter based on which only a certain values are allowed to pass through it and we get a resultant value based on its operation. 

Hence, we can generalize filters are matrices which allow only a certain set of values to get convolved and give us a particular result.

---

Topic 3: **3 X 3 Convolution**

In the above topic we learnt how filters act with respect to a given image. Each filter has got its own size. In the above image, we saw that the size of the filter was 3X3 and convolution of the image was happening with this 3X3 filter. 

The 3 X 3 convolution indicates that, the convolution of the data from the image happens with a filter whose size is 3 X 3. Basically, this 3X3 convolution depends on the size of the filter. If we hear 3X3 convolution, the size of the filter is 3X3.

---

Topic 4: **Activation Function**

In any given neural network, the output of the neural network is based on which all nodes in the neural network activate for a given input data. 

![Image of a Neural Network](https://i.ibb.co/zspCgxn/neural-Net.png)

The function which decides which all nodes should fire some value is called the *activation function*. There are different kinds of activation functions based on the purpose of why the neural network is constructed. Some of the activation functions are:

1. Sigmoid Function
2. Tanh Function
3. ReLU Function
4. Leaky ReLU Function
5. Softmax Function

These functions have got their own purposes and their own use cases. Based on the use case, we decide which activation function to use.

---

Topic 5: **Epochs**

While training a neural network we come across the term called Epoch. This is a value which is in the range of 100 - 1000. We usually confuse this term with number of iterations. Iterations mean each step that is taken to train a neural network where epochs give us how many times the neural network has seen the data. Each time in an epoch, it performs both forward propagation and back propagation while in iterations, each propagation is considered as one iteration.