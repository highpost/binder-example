# Sample Jupyter Notebook for MyBinder

This repo includes a Jupyter Notebook named binder-example.ipynb
which contains two cells:

* Use NumPy to load some matrices from a data file and use least squares
to find a line equation to fit the data. Then plot the data and line equation.
* Use SymPy to compose a function and find its derivative. Then plot
the function and its derivative.

Deploying this GitHub repo to MyBinder.org:

1. Go to https://mybinder.org
2. Add the GitHub repo URL
3. Press Launch

The <i>binder-example</i> Binder will then be launched on the MyBinder.org site.
This process can take a few minutes while it creates a Docker image and
spins up a Kubernetes cluster. When it's ready students can create their own
instances by visiting a URL with the following form:

<div style="display: inline">
https://mybinder.org/v2/gh/<i>github-user</i>/binder-example/master
</div>

NB: if you need to view the Jupyter notebook locally, then go to the directory
containing the notebook and run <tt>jupyter notebook</tt>. This will launch
a local web server and redirect your browser to a web page containing the
notebook.
