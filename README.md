# Dense 3D Face Correspondence

This repository contains serial and parallel implementation of an algorithm taken from [Dense 3D Face correspondence](https://ieeexplore.ieee.org/abstract/document/7973095) paper that automatically establishes dense correspondences between a large number of 3D faces. Starting from automatically detected sparse correspondences on the outer boundary of 3D faces, the algorithm triangulates existing correspondences and expands them iteratively by matching points of distinctive surface curvature along the triangle edges.


## Files:

* `serial.py` contains serial implementation of the algorithm.
