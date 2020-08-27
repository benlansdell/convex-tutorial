## A very short introduction to convex optimization

Here I cover a basic introduction to concepts and theory of convex optimization. The goal is to give an impression of why this is an important area of optimization, what its applications are, and some intiution for how it works. This is of course not meant to overview all areas of convex optimization, it's a huge topic, but more to give a flavor of the area by describing some results and theory, particularly as they relate to other areas that may be familiar to people (e.g. Lagrange multipliers). By presenting this in a notebook the aim is to focus on providing some geometric intuition whenever possible through plotting simple examples whose parameters you can play with. Images not generated in this notebook are taken from one of the standard references: [Convex Optimization](https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf), by Boyd and Vandenberghe. 

Here I will cover:

### Contents

**Part A.**
1. Basics of convex functions and sets
2. Why care about convexity?
3. A convergence proof of gradient descent

**Part B.**
1. Conjugate functions
2. Lagrangian duality
3. Generalizing Lagrange multipliers: the KKT conditions

An easy way to launch this notebook interactively is through google colab. Just follow [this](https://colab.research.google.com/github/benlansdell/convex-tutorial/blob/master/convex-tutorial.ipynb) link.
