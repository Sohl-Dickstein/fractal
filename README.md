# The boundary of neural network trainability is fractal

This repository contains code I used to explore fractal structure in neural network training hyperparameter landscapes.

- For the code itself: [open this colab]
- For images, videos, and raw data I generated for my writeups: [mount this Google Drive folder](https://drive.google.com/drive/folders/1-LKmtV1-kP-VJClHUuPlzRb2WPQMq4mx)
- For more details, see [the blog post] and [the short paper]

As a brief summary, the paper abstract follows:

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
