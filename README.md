# The boundary of neural network trainability is fractal

This repository contains code I used to explore fractal structure in neural network training hyperparameter landscapes.

- To make your own fractals, or reproduce my images and videos: [open this colab](https://colab.research.google.com/github/Sohl-Dickstein/fractal/blob/main/the_boundary_of_neural_network_trainability_is_fractal.ipynb)
- To learn more, see [the blog post] and [the short paper]

As a brief summary, the paper abstract:

*Some fractals -- for instance 
those associated with
the Mandelbrot and quadratic Julia sets -- 
are computed by iterating a function, and identifying the 
boundary between hyperparameters for which the resulting series diverges or remains bounded. 
Neural network training similarly involves iterating an update function (e.g. repeated steps of gradient descent), can result in convergent or divergent behavior, 
and can be extremely sensitive to small changes in hyperparameters. 
Motivated by these similarities, we experimentally examine the boundary between neural network hyperparameters that lead to stable and divergent training. 
We find that this boundary is fractal 
over more than ten decades of scale in all tested configurations.*
