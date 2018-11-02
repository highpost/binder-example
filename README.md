# Sample Jupyter Notebook for MyBinder

This repo includes a Jupyter Notebook named binder-example.ipynb
which contains two cells:

* Use NumPy to load some matrices from a data file and then use least squares
to find a line equation. Finally, plot the data and line equation.
* Use SymPy to compose a function and find its derivative. Finally, plot
the function and its derivative.

Deploying this repo to MyBinder.org:

1. Go to https://mybinder.org
2. Add the GitHub repo URL
3. Press Launch

The <i>binder-example</i> Binder will then be launched on the MyBinder.org site
and this process can take a few minutes while it creates a Docker image and
spins up a Kubernetes cluster. When it's ready students can then create their
own instances by visiting a URL with the following form:

<div style="display: inline">
https://mybinder.org/v2/gh/<i>user</i>/binder-example/master
</div>

