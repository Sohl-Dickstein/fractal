# The boundary of neural network trainability is fractal

This repository contains code I used to explore fractal structure in neural network training hyperparameter landscapes.

- To make your own fractals, or reproduce my images and videos: [open this colab](https://colab.research.google.com/github/Sohl-Dickstein/fractal/blob/main/the_boundary_of_neural_network_trainability_is_fractal.ipynb) (or to generate the single Mandelbrot image I had use [this colab](https://colab.research.google.com/github/Sohl-Dickstein/fractal/blob/main/Mandelbrot_set_visualization.ipynb))
- To learn more, see [the blog post](https://sohl-dickstein.github.io/2024/02/12/fractal.html) and [the short paper](https://arxiv.org/abs/2402.06184)

As a brief summary, here is the paper abstract:

> *Some fractals -- for instance those associated with the Mandelbrot and quadratic Julia sets -- are computed by iterating a function, and identifying the boundary between hyperparameters for which the resulting series diverges or remains bounded. Neural network training similarly involves iterating an update function (e.g. repeated steps of gradient descent), can result in convergent or divergent behavior, and can be extremely sensitive to small changes in hyperparameters. Motivated by these similarities, we experimentally examine the boundary between neural network hyperparameters that lead to stable and divergent training. We find that this boundary is fractal over more than ten decades of scale in all tested configurations.*

And here are some example images, showing parts of the fractals that result from neural network training, in a variety of experimental conditions:

![Examples of fractals resulting from neural network training in a variety of experimental configurations](fractal_tiles_midres.png)
