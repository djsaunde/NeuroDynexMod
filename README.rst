|Build Status| |Doc Status| |Pypi Repo| |Conda Repo|

Neuronal Dynamics: Python Exercises
===================================

This repository contains python exercises accompanying the book
`Neuronal Dynamics <http://neuronaldynamics.epfl.ch/>`__ by Wulfram Gerstner, Werner M. Kistler, Richard Naud and Liam Paninski. References to relevant chapters will be added in the `Teaching Materials <http://neuronaldynamics.epfl.ch/lectures.html>`__ section of the book homepage.

Exercises & Documentation
-------------------------

The full documentation and the exercises `can be found at readthedocs <http://neuronaldynamics-exercises.readthedocs.org/>`__.

Quickstart
----------

To install the exercises using ``pip`` simply execute:

.. code-block:: bash

   pip install --upgrade neurodynex

To install the exercises with anaconda/miniconda execute: 

.. code-block:: bash

   conda install -c brian-team -c epfl-lcn neurodynex

Brian1
------

This (master) branch is a rewrite of all python exercises for the more recent `Brian2 Simulator <https://github.com/brian-team/brian2>`__. The old exercises using brian1 are still available on the `brian1 branch <https://github.com/EPFL-LCN/neuronaldynamics-exercises/tree/brian1>`__.

License
-------

This free software: you can redistribute it and/or modify it under the terms of the GNU General Public License 2.0 as published by the Free Software Foundation. You should have received a copy of the GNU General Public License along with the repository. If not, see http://www.gnu.org/licenses/.

Should you reuse and publish the code for your own purposes, please point to the webpage http://neuronaldynamics.epfl.ch or cite the book: *Wulfram Gerstner, Werner M. Kistler, Richard Naud, and Liam Paninski. Neuronal Dynamics: From Single Neurons to Networks and Models of Cognition. Cambridge University Press, 2014.*

Contributors (alphabetically)
-----------------------------
* Parima Ahmadipouranari (LCN, EPFL)
* Bernd Illing (LCN, EPFL)
* Marco Lehmann (LCN, EPFL)
* Alexander Seeholzer (LCN, EPFL)
* Hesam Setareh (LCN, EPFL)
* Lorric Ziegler (LCN, EPFL)

.. |Build Status| image:: https://travis-ci.org/EPFL-LCN/neuronaldynamics-exercises.svg?branch=master
   :target: https://travis-ci.org/EPFL-LCN/neuronaldynamics-exercises
.. |Doc Status| image:: https://readthedocs.org/projects/neuronaldynamics-exercises/badge/?version=latest
   :target: http://neuronaldynamics-exercises.readthedocs.org/
.. |Conda Repo| image:: https://anaconda.org/epfl-lcn/neurodynex/badges/version.svg
   :target: https://anaconda.org/epfl-lcn/neurodynex
.. |Pypi Repo| image:: https://badge.fury.io/py/neurodynex.svg
   :target: https://pypi.python.org/pypi/neurodynex
