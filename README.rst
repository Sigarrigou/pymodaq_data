PyMoDAQ Data
############

.. image:: https://img.shields.io/pypi/v/pymodaq_data.svg
   :target: https://pypi.org/project/pymodaq_data/
   :alt: Latest Version

.. image:: https://readthedocs.org/projects/pymodaq/badge/?version=latest
   :target: https://pymodaq.readthedocs.io/en/stable/?badge=latest
   :alt: Documentation Status

.. image:: https://codecov.io/gh/PyMoDAQ/pymodaq_data/branch/0.0.x/graph/badge.svg?token=IQNJRCQDM2
    :target: https://codecov.io/gh/PyMoDAQ/pymodaq_data

====== ======= ======
Python OS      Passed
====== ======= ======
3.8    Linux   |38|
3.9    Linux   |39|
3.10   Linux   |310|
3.11   Linux   |311|
3.12   Linux   |312|
3.11   Windows |311win|
====== ======= ======


.. |38| image:: https://github.com/PyMoDAQ/pymodaq_data/actions/workflows/Testp38.yml/badge.svg?branch=0.0.x_dev
    :target: https://github.com/PyMoDAQ/pymodaq_data/actions/workflows/Testp385.yml

.. |39| image:: https://github.com/PyMoDAQ/pymodaq_data/actions/workflows/Testp39.yml/badge.svg?branch=0.0.x_dev
    :target: https://github.com/PyMoDAQ/pymodaq_data/actions/workflows/Testp39.yml

.. |310| image:: https://github.com/PyMoDAQ/pymodaq_data/actions/workflows/Testp310.yml/badge.svg?branch=0.0.x_dev
    :target: https://github.com/PyMoDAQ/pymodaq_data/actions/workflows/Testp310.yml

.. |311| image:: https://github.com/PyMoDAQ/pymodaq_data/actions/workflows/Testp311.yml/badge.svg?branch=0.0.x_dev
    :target: https://github.com/PyMoDAQ/pymodaq_data/actions/workflows/Testp311.yml

.. |312| image:: https://github.com/PyMoDAQ/pymodaq_data/actions/workflows/Testp312.yml/badge.svg?branch=0.0.x_dev
    :target: https://github.com/PyMoDAQ/pymodaq_data/actions/workflows/Testp312.yml

.. |311win| image:: https://github.com/PyMoDAQ/pymodaq_data/actions/workflows/Testp311_win.yml/badge.svg?branch=0.0.x_dev
    :target: https://github.com/PyMoDAQ/pymodaq_data/actions/workflows/Testp311_win.yml




.. figure:: http://pymodaq.cnrs.fr/en/latest/_static/splash.png
   :alt: shortcut


PyMoDAQ__, Modular Data Acquisition with Python, is a set of **python** modules used to interface any kind of
experiments. It simplifies the interaction with detector and actuator hardware to go straight to the data acquisition
of interest.

__ https://pymodaq.readthedocs.io/en/stable/?badge=latest

`PyMoDAQ data`__ is a set of utilities (constants, methods and classes) that are used
for Data Management. It is heavily used with the PyMoDAQ framework but can also be used as a standalone
package for data management in another context.

__ https://pymodaq.cnrs.fr/en/latest/developer_folder/data_management.html

What are Data?
--------------

Data are objects with many characteristics able to properly describe real data taken on an experiment
or calculated from theory:


*  a type: float, int, ...
*  a dimensionality: Data0D, Data1D, Data2D and higher
*  units (dealt with the pint python package)
*  axes
*  actual data as numpy arrays
*  uncertainty/error bars
* ...


.. figure:: https://pymodaq.cnrs.fr/en/latest/_images/data.png

   What is PyMoDAQ's data?.

The `PyMoDAQ Data` package
--------------------------

Because of this variety, `PyMoDAQ Data` introduce a set of objects including metadata (for instance the time of
acquisition) and various methods and properties to manipulate
them during analysis for instance (getting name, slicing, concatenating...),
save them and plot them (given you installed one of the available backend: *matplotlib* or *Qt* (
through the `pymodaq_gui` package)

To learn more, check the documentation__.

__ https://pymodaq.cnrs.fr/en/latest/developer_folder/data_management.html


Published under the MIT FREE SOFTWARE LICENSE

GitHub repo: https://github.com/PyMoDAQ

Documentation: http://pymodaq.cnrs.fr/
