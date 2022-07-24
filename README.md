# Bayesopt Tutorial in Python & BoTorch

Bayesian optimization (BayesOpt) is a powerful and widely-used set of machine-learning-based methods that can solve really hard optimization problems:  optimization problems with non-convex objective functions and constraints that take a long time to evaulate, don't provide derivatives, and may be noisy.

The tutorials in this repository aim to quickly show you how to use BayesOpt to solve practical problems in python. They start in pure python to illustrate the main ideas. Then they switch to using the [BoTorch](botorch.org) package to do the main BayesOpt calculations. They are divided into two secctions: essential topics, which are enough to solve many problems effectively using BayesOpt; and advanced topics, which can help you solve problems faster while producing better solutions.

There is a [companion tutorial paper on the arxiv](https://arxiv.org/pdf/1807.02811.pdf). For readers who have never seen BayesOpt before, we recommend reading the first 7 pages of the tutorial paper while going through the python tutorials listed under "Essential topics". There are also [slides](https://people.orie.cornell.edu/pfrazier/Presentations/2018.11.INFORMS.tutorial.pdf) and a [YouTube video](https://www.youtube.com/watch?v=c4KKvyWW_Xk) that go with this tutorial paper. For readers that want to learn more, we recommend this [2021 book](https://bayesoptbook.com/) on BayesOpt that goes into much more depth.

### Essential Topics:
- Tutorial 1: [Gaussian process regression in pure python](https://github.com/frazier-lab/bayesopt-tutorial/blob/main/tutorials/Tutorial1_GP_Regression_in_Pure_Python.ipynb)
- Tutorial 2: [Gaussian process regression in BoTorch](https://github.com/frazier-lab/bayesopt-tutorial/blob/main/tutorials/Tutorial2_GP_Regression_in_BoTorch.ipynb)
- Tutorial 3: [Expected improvement](https://github.com/frazier-lab/bayesopt-tutorial/blob/main/tutorials/Tutorial3_ExpectedImprovement.ipynb)

### Advanced Topics:
- Tutorial 4: [BayesOpt of composite functions](https://github.com/frazier-lab/bayesopt-tutorial/blob/main/tutorials/Tutorial4_Composite_Functions.ipynb)
- Tutorial 5: [Parallel BayesOpt with the Knowledge Gradient acquisition function](https://github.com/frazier-lab/bayesopt-tutorial/blob/main/tutorials/Tutorial5_Parallel_KG.ipynb) 
- We hope to build on and expand these tutorials on advanced topics

These python tutorials are also used in a short-course teaching Bayesian optimization over a few days with complementary lectures. This was last taught as part of the [Optimization, Big Data, and Applications machine learning summer school](https://sites.google.com/diag.uniroma1.it/oba2022/) in Veroli, Italy near Rome in 2022, and at Lancaster University in the UK in 2020. Here is a [link to the 2022 course materials](https://docs.google.com/document/d/1mFAa27I0kIeDQPnEXFmUC2qyhf1YO8AHOh-BAqF42oY/edit?usp=sharing).
