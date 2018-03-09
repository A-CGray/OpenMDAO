************************
Working with Derivatives
************************

Using Finite Difference or Complex Step
-----------------------------------------
.. toctree::
    :maxdepth: 1

    approximating_partials.rst
    approximating_totals.rst


Providing Analytic Partial Derivatives
----------------------------------------

.. toctree::
    :maxdepth: 1

    specifying_partials.rst
    sparse_partials.rst
    checking_partials.rst
    unit_testing_partials.rst



Computing Total Derivatives Across a Model
-------------------------------------------

.. toctree:: 
    :maxdepth: 1

    picking_mode.rst
    compute_totals.rst
    check_total_derivatives.rst


Reducing the Cost of Total Derivative Solves For Special Cases
--------------------------------------------------------------

There are a number of special cases where a model has a particular structure that can be exploited to reduce the cost of linear solves used to compute total derivatives. 
You can learn details on how to determine if your problem has the necessary structure to use one of these features or  how to restructure your problem to make use of them in the theory manual on how OpenMDAO computes total derivatives. 

.. toctree::
    :maxdepth: 1

    simul_derivs.rst

.. vectorizing_derivatives
.. parallel_derivatives
.. caching linear solution for restarting the linear solve