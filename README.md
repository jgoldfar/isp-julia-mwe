# Julia Codes for ISP #

##  What is this repository for? ##
* We are developing a Julia package for solution of Inverse Free Boundary Problems, in the general context of optimal control with distributed parameters.

* [Julia](julialang.org) is a fast language for numerical/scientific computing which outperforms MATLAB for similar tasks (written in an obvious way... see the [benchmarks](http://julialang.org/benchmarks/).) Since we optimize, but don't go to C for the most part (nor do we write highly optimized C code when it comes to that, most likely) Julia is likely to be faster. Moreover, we don't suffer from vendor lock-in or lack of free availability..

## Dependencies ##
The ISP Module is relatively self-contained and runs on Julia 0.3+

* To run the tests and benchmarks, we use the Benchmark.jl package

* Integration routines using Cubature.jl (optional)

* Optimization tests/comparisons using Optim.jl (optional)

* For plotting, Gadfly.jl is needed

* For interactive/notebook development, IJulia and a working IPython environment is required (optional).

* CI Currently runs on a [local Jenkins server](http://163.118.100.57:8081) (optional)

## How do I contribute? ##

Contribution is encouraged: we need tests, as detailed in the issues so far. All code is reviewed by the project maintainer. Other improvements can be discussed through a pull request and corresponding issue, or just an enhancement request or issue.

## Who is in charge? ##

* Jonathan Goldfarb <jgoldfar@gmail.com>