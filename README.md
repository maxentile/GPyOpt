GPyOpt
======

Gaussian process optimization using [GPy](http://sheffieldml.github.io/GPy/). Performs global optimization with different acquisition functions. Among other functionalities, it is possible to use GPyOpt to optimize physical experiments (sequentially or in batches) and tune the parameters of Machine Learning algorithms. It is able to handle large data sets via sparse Gaussian process models. 

* [GPyOpt homepage](http://sheffieldml.github.io/GPyOpt/)
* [Tutorial Notebooks](http://nbviewer.ipython.org/github/SheffieldML/GPyOpt/blob/master/manual/index.ipynb)
* [Users Mailing list](https://lists.shef.ac.uk/sympa/info/gpyopt-users)
* [Online documentation](http://pythonhosted.org/GPyOpt)

### Citation

    @Misc{gpy2014,
      author =   {The GPyOpt authors},
      title =    {{GPy}: A Bayesian Optimization framework in python},
      howpublished = {\url{http://github.com/SheffieldML/GPyOpt}},
      year = {2015}
    }

Getting started
===============

Installing with pip
-------------------
The simplest way to install GPyOpt is using pip. ubuntu users can do:

    sudo apt-get install python-pip
    pip install gpyopt

If you'd like to install from source, or want to contribute to the project (e.g. by sending pull requests via github), read on. Clone the repository in GitHub and add it to your $PYTHONPATH.

    git clone git@github.com:SheffieldML/GPyOpt.git ~/SheffieldML
    echo 'PYTHONPATH=$PYTHONPATH:~/SheffieldML' >> ~/.bashrc

Dependencies:
------------------------
  - GPy
  - numpy
  - scipy
  - DIRECT (optional)
  - cma (optional)
  - pyDOE (optional)

Funding Acknowledgements
========================
* [BBSRC Project No BB/K011197/1](http://staffwww.dcs.shef.ac.uk/people/N.Lawrence/projects/recombinant/) "Linking recombinant gene sequence to protein product manufacturability using CHO cell genomic resources"

* See GPy funding Acknowledgements






