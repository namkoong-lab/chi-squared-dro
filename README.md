# RobustOpt

Code for solving robust stochastic---or distributionally robust---optimization problems with f-divergences.


## Efficient computation of full-batch gradient for the robust loss

The files simple_projections.py, SimpleProjections.jl each contain efficient binary search algorithm for solving the inner worst-case problem of the robust formulation.

## Papers 
* Variance Regularization with Convex Objectives ([NIPS Version](https://papers.nips.cc/paper/6890-variance-based-regularization-with-convex-objectives), [Long Version](https://arxiv.org/abs/1610.02581))
* Statistics of Robust Optimization: A Generalized Empirical Likelihood Approach ([arXiv link](https://arxiv.org/abs/1610.02581))

## Authors

* **[Hongseok Namkoong](http://web.stanford.edu/~hnamk/)** and **[John Duchi](http://web.stanford.edu/~jduchi/)** 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
