# diffusion2d

## Instructions for students

Please follow the instructions in [pypi_exercise.md](https://github.com/Simulation-Software-Engineering/Lecture-Material/blob/main/03_building_and_packaging/pypi_exercise.md).

The code used in this exercise is based on [Chapter 7 of the book "Learning Scientific Programming with Python"](https://scipython.com/book/chapter-7-matplotlib/examples/the-two-dimensional-diffusion-equation/).

## Description
This code solves the diffusion equation over a two dimensional square domain which is at a certain temperature, and a circular disc at its center which is at a higher temperature. The diffusion equation is solved using the finite-difference method. The thermal diffusivity and initial conditions of the system can be changed by the user. The code produces four plots at various timepoints of the simulation. The diffusion process can be clearly observed in these plots.
Take a few minutes to play around with parameters dx, dy and D in the solver file and observe how the value of dt and the output changes. Do you notice if the code takes more or less time to finish the computation?

## Installing the package
`pip install --index-url https://test.pypi.org/simple/ zlatanza_diffusion2d`

## Running this package
```
from zlatanza_diffusion2d import diffusion2d

diffusion2d.solve()
```

## Citing
Information is taken from:
- https://github.com/Simulation-Software-Engineering/Lecture-Material/blob/main/03_building_and_packaging/pypi_exercise.md
- https://scipython.com/book/chapter-7-matplotlib/examples/the-two-dimensional-diffusion-equation/
- https://en.wikipedia.org/wiki/Finite_difference_method
