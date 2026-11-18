# Some Miscellaneous Projects 

Hello, human! This repository hosts some small projects that otherwise would not deserve a dedicated repo of their own. 

Current offerings are listed below. 

## [Partial Fractions Generator and Solver](./RandomPartialFractions.astro)
The code behind [Exercise 5.1](https://r3birth.dev/math/heaviside/5b/)! Generate a random partial fractions problem, and compute the solution natively in the browser using the math.js library (with an estimate of the time it would take). Currently supports: linear poles, complex poles (quadratic), and repeated poles. Does NOT support repeated quadratic poles. Is limited to poles *s* with Re(*s*) <= 5 and Im(*s*) <= 5, since otherwise floating point precision does not always allow for valid solutions.
