# Sigmoid Neuron:-

## Limitation of Perceptron:- 

- Here the Perceptron is more like a step function it cannot regret / give probability on the basis of given parameter.
- It classifies only in the binary classification
- Decision boundary is not actually separable the datasets like human do.

## advantage of Sigmoid :-

- Here the Learning Model function is exponential. 
![equation](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSqeVWCs204BAKd_2QZzxSQ8S6BaVczA3zgcof1UFO8YtPDRHY6&usqp=CAU)

- It has curve to separate and hence can give probability on the basis of given parameter.
- Decision boundary is more useful in real life scenario.
- We use gradient descent for parameter learning.
- We use `MSE`(Mean Squared Error) as well as `CE`(Cross Entropy) for loss function.

## Working of Sigmoid Gradient descent on toy data :-
![alt text](https://github.com/ShreyasSubhedar/Deep_Learning/blob/master/DL%23103/ezgif.com-video-to-gif%20(2).gif)
![alt text](https://github.com/ShreyasSubhedar/Deep_Learning/blob/master/DL%23103/ezgif.com-video-to-gif.gif)
- here the red dots are representing the events that never occur(Ex non-text, not-cat etc) 
- here the green dots are representing the events that  occurs(Ex text, cat etc)
- And animation tells us how sigmoid gradient separates these events. 
## Classification of text-non text prediction:- 

Level 1: - Accuracy-<h2>98.333</h2>
Level 2: - Accuracy-<h2>97.666</h2>
