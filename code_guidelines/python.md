Coding Standards
================

When contributing code to any QuazarTech repo, you must follow its coding standards. 

All our Python code enforces a variant of `PEP-8`_, with the docstrings following
`PEP-257`_ (WIP - Document the differences). A quick-reference is provided below

Quick-Reference
---------------

* Use 4 spaces per indentation level.(Please DO NOT use tabs)
* Limit all lines to a maximum of 79 characters.
* Use the following structure when writing code that consists of multiple binary operators

.. code-block:: python

    income = (  gross_wages
              + taxable_interest
              + (dividends - qualified_dividends)
              - ira_deduction
              - student_loan_interest
             )

* Also note the alignment of brackets in the above example. To elaborate further:

.. code-block:: python

    T_ls = (  energy
            - density * p1_bulk**2
            - density * p2_bulk**2
            - density * p3_bulk**2
           ) / density

The above is an acceptable format. Do NOT use this:

    T_ls = (  energy
            - density * p1_bulk**2
            - density * p2_bulk**2
            - density * p3_bulk**2) / density

* While PEP-8 recommends that assignment operations have a single space between variables and the equal to(`=`) sign, we recommend that you vertically align all the equal to signs like this:

.. code-block:: python

    pl.rcParams['figure.figsize']  = 12, 7.5
    pl.rcParams['figure.dpi']      = 300
    pl.rcParams['image.cmap']      = 'jet'
    pl.rcParams['lines.linewidth'] = 1.5

Do NOT use this:

.. code-block:: python

    pl.rcParams['figure.figsize'] = 12, 7.5
    pl.rcParams['figure.dpi'] = 300
    pl.rcParams['image.cmap'] = 'jet'
    pl.rcParams['lines.linewidth'] = 1.5

* Surround top-level function and class definitions with two blank lines.
* Method definitions inside a class are surrounded by a single blank line.
* Code in the core Python distribution should always use UTF-8
* Imports should usually be on separate lines
* Imports are always put at the top of the file, just after any module comments and docstrings
* Imports should be grouped in the following order:
    * standard library imports
    * related third party imports
    * local application/library specific imports
* Absolute imports are recommended, as they are usually more readable and tend to be better behaved

.. _`PEP-8`: https://www.python.org/dev/peps/pep-0008/
.. _`PEP-257`: https://www.python.org/dev/peps/pep-0257/
