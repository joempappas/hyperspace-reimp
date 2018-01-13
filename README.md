# HyperSpace

### Welcome to HyperSpace!

If you have a complicated model with many hyperparameters, there is a lot to explore here.
A combinatorial explosion, in fact. Here is a *Hitchhiker's Guide*:

### Preparations

You can't just waltz out into space without the proper preparations!

```
git clone https://github.com/yngtodd/hyperspace.git
cd hyperspace

# Get you gear!
pip install .
```

### Modules

A Hubble height view of the library. For details, check out the [wiki](https://github.com/yngtodd/hyperspace/wiki).

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
