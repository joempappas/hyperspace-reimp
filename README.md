<p align="center">
    <img width="300" src="https://github.com/yngtodd/hyperspace/blob/master/img/hyperspace_logo.png">
</p>

----------------------------

[![DOI](https://zenodo.org/badge/113602572.svg)](https://zenodo.org/badge/latestdoi/113602572)


# Joe's Directions:
I used conda (I've grown to hate conda, but I don't have time to set anything else up. Don't judge me.)
conda create environment, I used python 3.9

Notes:
Their original example uses the boston housing dataset. I switched to the california housing dataset.

Steps:
pip install . (mpi4py might fail. I installed with conda install mpi4py after that.)
pip install -U scikit-learn



### Welcome to HyperSpace!

If you have a complicated model with many hyperparameters, there is a lot to explore here.
A combinatorial explosion, in fact. Details can be found in the [documentation](http://hyperspace.readthedocs.io/en/latest/).

Here is a *Hitchhiker's Guide*:

### Preparations

You can't just waltz out into space without the proper preparations! 

HyperSpace makes use of MPI through `mpi4py`. Make sure to have either [MPICH](http://www.mpich.org/) or [Open MPI](https://www.open-mpi.org/).

```
git clone https://github.com/yngtodd/hyperspace.git
cd hyperspace

# Get you gear!
pip install .
```

### Modules

Here is a Hubble height view of the library: 

### Space

> _"Space," it says, "is big. Really big. You just won't believe how vastly, hugely,
mindbogglingly big it is. I mean, you may think it's a long way down the road to the
chemist's, but that's just peanuts to space." - The Hitchhiker's Guide to the Galaxy_

In [space](https://github.com/yngtodd/hyperspace/blob/master/hyperspace/space/space.py)
you will find the various classes that define hyperparameter search spaces.

### Mapping Space

In [mapping_space](https://github.com/yngtodd/hyperspace/blob/master/hyperspace/space/mapping_space.py)
we have functions that define hyperspaces, the many subregions
of our hyperparameter search space to be distributed across cluster resources.


### Hyperdrive

In [hyperdrive](https://github.com/yngtodd/hyperspace/tree/master/hyperspace/hyperdrive)
we have various methods for distributing our optimization procedure.

    @misc{hyperspace,
      author = {M.Todd Young},
      title = {HyperSpace},
      year = {2017},
      publisher = {GitHub},
      journal = {GitHub repository},
      howpublished = {\url{https://github.com/yngtodd/hyperspace}},
    }
