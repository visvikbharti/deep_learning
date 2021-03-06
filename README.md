<h1 align="center">Preparation for NMD classification</h1>

## Description
Here I have begun the journey of my NMD classification project: starting with ml first.
I have tried to implement ML/DL algorithms from scratch using numpy, because getting your hands dirty is the best way to learn.


## Comparision of optimization Algorithms on saddle point
[Source code](./src/misc/optimizer_comparision.py)

<table>
    <tr>
        <td><p align="center">Scratch optimizers</p></td>
        <td><p align="center">Tensorflow optimizers</p></td>
    </tr>
    <tr>
        <td><img width="350" src="temp/plot/nn/optimizers/optimizers_comparision_scratch.gif"></td>
        <td><img width="350" src="temp/plot/nn/optimizers/optimizers_comparision_scratch.gif"></td>
    </tr>
</table>

## Comparision of optimization Algorithms on MNIST dataset
[Source code](./src/dl/example.py)

I have compared the performance of a Convolutional Neural Network(CNN) with different optimizers.
Models used same test and train datasets. Here are the results.
​

<table>
    <tr>
        <td><p align="center">Gradient Descent Accuracy</p></td>
        <td><p align="center">Gradient Descent Loss</p></td>
    </tr>
    <tr>
        <td><img width="500" src="./temp/plot/nn/mnist/gd/accuracy.png" alt="Gradient Descent"></td>
        <td><img width="500" src="./temp/plot/nn/mnist/gd/loss.png" alt="Gradient Descent"></td>
    </tr>
    <tr>
        <td><p align="center">Momentum Accuracy</p></td>
        <td><p align="center">Momentum Loss</p></td>
    </tr>
    <tr>
        <td><img width="500" src="./temp/plot/nn/mnist/momentum/accuracy.png" alt="Momentum Optimizer"></td>
        <td><img width="500" src="./temp/plot/nn/mnist/momentum/loss.png" alt="Momentum Optimizer"></td>
    </tr>
    <tr>
        <td><p align="center">RMSProp Accuracy</p></td>
        <td><p align="center">RMSProp Loss</p></td>
    </tr>
    <tr>
        <td><img width="500" src="./temp/plot/nn/mnist/rmsprop/accuracy.png" alt="RMSProp Optimizer"></td>
        <td><img width="500" src="./temp/plot/nn/mnist/rmsprop/loss.png" alt="RMSProp Optimizer"></td>
    </tr>
    <tr>
        <td><p align="center">Adam Accuracy</p></td>
        <td><p align="center">Adam Loss</p></td>
    </tr>
    <tr>
        <td><img width="500" src="./temp/plot/nn/mnist/adam/accuracy.png" alt="Adam Optimizer"></td>
        <td><img width="500" src="./temp/plot/nn/mnist/adam/loss.png" alt="Adam Optimizer"></td>
    </tr>
</table>
