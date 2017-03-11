.. _Installation:

Installation
============
Altair can be installed via the Python Package Index with the following:

.. code-block:: bash

    $ pip install altair
    $ pip install --upgrade notebook
    $ pip install jupyterlab_vega
    $ jupyter nbextension install --sys-prefix --py jupyterlab_vega
    $ jupyter nbextension enable --sys-prefix --py jupyterlab_vega

The additional commands serve to set-up the `jupyterlab_vega`_ package to
automatically render Altair plots within the Jupyter Notebook (see
:ref:`displaying-plots-jupyter`) Alternatively, you can install with conda_,
which handles the Jupyter Notebook setup within the single install command:

.. code-block:: bash

    $ conda install altair --channel conda-forge

Dependencies
------------

Altair has the following dependencies, all of which are installed by default
with either of the above installation commands:

- Pandas_
- Traitlets_
- IPython_

Additionally, the following optional dependencies are required to use Altair
within the Jupyter Notebook:

- `Jupyter Notebook`_
- jupyterlab_vega_

Development Install
-------------------
The `Altair source repository`_ is available on github.
Once you have cloned the repository and installed all the above dependencies,
run the following command from the root of the repository to install the
master version of Altair:

.. code-block:: bash

    $ pip install -e .

If you do not wish to clone the source repository, you can install the development
version directly from github using:

.. code-block:: bash

    $ pip install git+https://github.com/altair-viz/altair


.. _Vega-Lite: http://vega.github.io/vega-lite
.. _Pandas: http://pandas.pydata.org
.. _traitlets: https://github.com/ipython/traitlets
.. _IPython: https://github.com/ipython/ipython
.. _Jupyter Notebook: https://jupyter.readthedocs.io/en/latest/install.html
.. _ipyvega: http://github.com/vega/ipyvega
.. _conda: http://conda.pydata.org
.. _Altair source repository: http://github.com/altair-viz/altair
