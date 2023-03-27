# PA-Nav
The code for **<u>P</u>**arallel **<u>A</u>**synchronous Multi-agent **<u>Nav</u>**igation(PA-Nav) project.

The core functionalities are encapsulated in the *panav* Python package.

## Required libraries
* Jupyter lab
* matplotlib
* polytope: a Python package that allows flexible construction of convex and non-convex polytopes, called polytope, which is part of the TuLip control toolbox. Install by `pip install polytope`.
* cvxopt: a convex optimization library. Install by `conda install -c conda-forge cvxopt`. 
* pypoman: this library implements common operations over convex polyhedra such as polytope projection, double description (conversion between halfspace and vertex representations), computing the Chebyshev center, etc. Install by `pip install pypoman`.
* shapely: a powerful library for geometry shape manipulations. Useful in visualization. Install by `conda install -c conda-forge shapely`

## Structure of the repo

* Virtual navigation environment construction and visualization.
* Global multi-agent motion planning.
* Local path tracking & distributed multi-agent collision avoidance.
* Experiments written on Python notebooks.
