.. Places parent toc into the sidebar

:parenttoc: True

.. _toy_datasets:

Toy datasets
============

.. currentmodule:: sklearn.datasets

scikit-learn comes pre-loaded with a few small, well-known datasets which allows you to
experiment without downloading any external files.

They can be loaded using the following functions:

.. autosummary::

   load_iris
   load_diabetes
   load_digits
   load_linnerud
   load_wine
   load_breast_cancer

These datasets are useful to quickly illustrate the behavior of the
various algorithms implemented in scikit-learn. They are however often too
small to be representative of real world machine learning tasks.

.. include:: ../../sklearn/datasets/descr/iris.rst

.. include:: ../../sklearn/datasets/descr/diabetes.rst

.. include:: ../../sklearn/datasets/descr/digits.rst

.. include:: ../../sklearn/datasets/descr/linnerud.rst

.. include:: ../../sklearn/datasets/descr/wine_data.rst

.. include:: ../../sklearn/datasets/descr/breast_cancer.rst
