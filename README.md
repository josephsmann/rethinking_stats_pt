# __this is my clone of  https://fehiepsi.github.io/rethinking-pyro/ __
please get the real thing if that's what you're looking for.


# Statistical Rethinking with PyTorch and Pyro

[*Statistical Rethinking*](https://xcelab.net/rm/statistical-rethinking/) is an excellent book for applied [Bayesian data analysis](https://en.wikipedia.org/wiki/Bayesian_statistics). The [accompanying codes for the book](https://github.com/rmcelreath/rethinking) are written in **R** and **Stan**. They are then [ported to Python language](https://github.com/pymc-devs/resources/tree/master/Rethinking) using [PyMC3](https://docs.pymc.io/). Recently, [Pyro](http://pyro.ai/) emerges as a scalable and flexible Bayesian modeling tool (see its [tutorial page](http://pyro.ai/examples/)), so to attract statisticians to this new library, I decided to make a *Pyronic* version for the codes in this repository. Inspired by the *PyMC3onic* version, I keep the codes in this repository as close as possible to the original codes in the book.

To say a bit more about **Pyro**, it is a universal [probabilistic programming language](https://en.wikipedia.org/wiki/Probabilistic_programming_language) which is built on top of [PyTorch](https://pytorch.org/), a very popular platform for deep learning. If you are familiar with [numpy](http://www.numpy.org/), the transition from `numpy.array` to `torch.tensor` is rather straightforward (as demonstrated in [this tutorial](https://pytorch.org/tutorials/beginner/blitz/tensor_tutorial.html)).

## How to read the notebooks

+ Read on the site: https://fehiepsi.github.io/rethinking-pyro/

+ Use GitHub's renderer: https://github.com/fehiepsi/rethinking-pyro/tree/master/notebooks/

+ Use Jupyter's nbviewer: https://nbviewer.jupyter.org/github/fehiepsi/rethinking-pyro/tree/master/notebooks/

## Installation

```sh
pip install jupyter pandas pyro-ppl seaborn torch
```
