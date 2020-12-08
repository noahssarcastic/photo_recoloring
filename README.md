# Materials Referenced:
Lazy Snapping, Li et al. (2004)
Palette-based Photo Recoloring, Chang et al. (2015)
https://github.com/zhijie/lazy-snapping-
https://github.com/pmneila/PyMaxflow
https://realpython.com/k-means-clustering-python/


# Requirements:
PyMaxflow package


# PyMaxflow License Note:

The core of the library is the C++ implementation by Vladimir Kolmogorov. It is also licensed under the GPL, but it REQUIRES that you cite [BOYKOV04] in any resulting publication if you use this code for research purposes. This requirement extends to PyMaxflow. 

[BOYKOV04] (1, 2) An Experimental Comparison of Min-Cut/Max-Flow Algorithms for Energy Minimization in Vision. Yuri Boykov and Vladimir Kolmogorov. In IEEE Transactions on Pattern Analysis and Machine Intelligence (PAMI), September 2004


# Installation:

## PyMaxflow:
```
conda skeleton pypi pymaxflow
conda build pymaxflow
conda install --use-local pymaxflow
```
or
```
pip install --upgrade-strategy only-if-needed pymaxflow
```
