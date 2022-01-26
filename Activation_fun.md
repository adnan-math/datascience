# Assignment

## Activation Functions in Machine Learning

In **artificial neural networks**, an activation function is a function that outputs a small value for small inputs and a higher value if the inputs exceed a threshold. The activation function "fires" if the inputs are large enough; otherwise, it does nothing. In other words, an activation function acts as a gate, ensuring that an incoming value is greater than a threshold value.

## Types of activation functions and usage

1. ### Binary Step Function


  If the input to the activation function is greater than a threshold, then the neuron is activated, else it is deactivated, i.e. its output is not considered for the next hidden layer. Let us look at it mathematically

$$ f(x)=   \left\{
\begin{array}{ll}
      1 & x\geq0 \\
      0 & x<0 \\
\end{array} 
\right.  
$$

 _How to plot Binary function in Python_

```python
        import numpy as np
        import matplotlib.pyplot as plt
        def binaryStep(x):
         return np.heaviside(x,1)
        x = np.linspace(-10, 10)
        plt.plot(x, binaryStep(x))
        plt.axis('tight')
        plt.title('Activation Function :binaryStep')
        plt.show()
```




1. ### Linear Function
2. ### Sigmoid
3. ### Tanh
4. ### ReLU
5. ### Leaky ReLU
6. ### Parameterised ReLU
7.  ### Exponential Linear Unit
8.  ### Swish
9.  ### Softmax
10. 

