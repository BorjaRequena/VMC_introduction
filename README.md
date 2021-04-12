# Introduction to variational Monte Carlo 
> A thorough introduction to variational Monte Carlo from the foundations with code examples.


Here you will find a step-by-step introduction to variational Monte Carlo methods from the foundations. This is the notebook version of [my blogpost](https://brequena.com/variational%20monte%20carlo/machine%20learning/neural%20network%20quantum%20states/2021/03/24/VMC-intro.html), where you can find the content in a nicer format and directly run it in [Google Colab](https://colab.research.google.com/). The tutorial is in the notebook [`VMC_introduction.ipynb`](https://github.com/BorjaRequena/VMC_introduction/blob/master/VMC_introduction.ipynb), which can also be [viewed online](https://borjarequena.github.io/VMC_introduction/). The goal is to start from the most basic concepts to implement a state-of-the-art quantum Variational Monte Carlo with the [Restricted Boltzmann Machine ansatz](https://arxiv.org/pdf/1606.02318.pdf). 

This guide introduces the main concepts of Monte Carlo methods. Then, each concept is subsequently brought to the field of quantum physics, providing examples with code. Hence, this is not only restricted to quantum Monte Carlo, but it is also of use to anyone starting with classical Monte Carlo methods, as the main concepts are independent of the application field. 

The main covered topics are 
- Monte Carlo integration
- Importance sampling
- Statistical analysis and autocorrelation time
- Monte Carlo optimization (variational Monte Carlo)

All the code examples start from scratch with native python and [NumPy](https://numpy.org).
