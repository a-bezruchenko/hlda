Hierarchical Latent Dirichlet Allocation
----------------------------------------

This is faster version of [Python hlda library](https://github.com/joewandy/hlda). Due to some optimisations it can be up to 2 times faster.

Hierarchical Latent Dirichlet Allocation (hLDA) addresses the problem of learning topic hierarchies from data. The model relies on a non-parametric prior called the nested Chinese restaurant process, which allows for arbitrarily large branching factors and readily accommodates growing
data collections. The hLDA model combines this prior with a likelihood that is based on a hierarchical variant of latent Dirichlet allocation.

[Hierarchical Topic Models and the Nested Chinese Restaurant Process](http://www.cs.columbia.edu/~blei/papers/BleiGriffithsJordanTenenbaum2003.pdf)

[The Nested Chinese Restaurant Process and Bayesian Nonparametric Inference of Topic Hierarchies](http://cocosci.berkeley.edu/tom/papers/ncrp.pdf)



Implementation
--------------

- [sampler.py](sampler.py) is the Gibbs sampler for hLDA inference, based on the implementation from [Python hlda library](https://github.com/joewandy/hlda) having a fixed depth on the nCRP tree.


Examples
------------

- See the original repository for examples of using this library.
