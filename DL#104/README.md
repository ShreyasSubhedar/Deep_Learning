# Feedforward Neural Network

## Do we need a complex function?

- Up till now we see 3 models , those are MP neuron, Perceptron, Sigmoid Neuron respectively. But no model can handle the `non-linearly separable data `
- Example If the mobile of screen size 3.5 to 5.5 and price from 9k - 13k are most affordable rather than other mobile phones then no module can actually help to separate this kind of dataset.

- ![Image](https://github.com/ShreyasSubhedar/Deep_Learning/blob/master/DL%23104/Images/Screenshot%20from%202020-06-01%2019-15-02.png)

- Sigmoid neuron is one of the continuous model but failed to separate this data, hence the reason why we require more complex functions.

![Image](https://github.com/ShreyasSubhedar/Deep_Learning/blob/master/DL%23104/Images/Screenshot%20from%202020-06-01%2019-15-33.png)

## Real world Complex functions and how to tackle them?

- yˆ = (sinwx + coswx e^x ) is an example of a function that could create a complex
- Clearly, we can see that it’s hard to come up with such functions, thus we need a simpler
approach
- Consider the following analogy, to build a house/building, we don’t simply conjure the building
out of thin air, instead we consider the most basic unit of the building: the brick.
- The bricks are combined one after the other, in different ways, that ultimately amount to a very
complicated structure.
- In our context, **The building would be the complex function and the brick would be a single sigmoid neuron**

![Image](https://github.com/ShreyasSubhedar/Deep_Learning/blob/master/DL%23104/Images/Screenshot%20from%202020-06-01%2020-33-23.png)
- The building that we have constructed with the sigmoid neurons is nothing but a **deep neural network.**
-  A deep neural network with a certain number of hidden layers would
be able to approximate any function between the input and output
**This is called the Universal Approximation Theorem (ŷ≃y’)**

## Illustrative Proof of Universal Approximation Theorem

> This proof is not really in mathematical way but it helps us to convince that the brick **sigmoid neuron** can approximate the relation b/w input and output.
- Consider one complex function like this:-
![Image](https://upload.wikimedia.org/wikipedia/commons/thumb/0/02/Simple_sine_wave.svg/1200px-Simple_sine_wave.svg.png)
- As we discussed its difficult to come up with complex function.
- Hence we assume the `impulsive functions` and these functions can further integrate to make the final output.

![Image](https://github.com/ShreyasSubhedar/Deep_Learning/blob/master/DL%23104/Images/Screenshot%20from%202020-06-01%2022-08-28.png)
- The `impulsive function`(rectangle shape function ) are formed with the help of 2 sigmoid functions.
    - As we know weights `w` decides the curve(sharpness) of sigmoid and bias `b` decides the shift of the sigmoid 
    - Consider the subtraction of 2 sigmoid given below:-
<img align="center" src="https://github.com/ShreyasSubhedar/Deep_Learning/blob/master/DL%23104/Images/Screenshot%20from%202020-06-01%2022-19-39.png" height=300px>
