.. -*- mode: rst -*-

|Azure| |Codecov| |CircleCI| |Nightly wheels| |Ruff| |PythonVersion| |PyPi| |DOI| |Benchmark|

.. |Azure| image:: https://dev.azure.com/scikit-learn/scikit-learn/_apis/build/status/scikit-learn.scikit-learn?branchName=main
   :target: https://dev.azure.com/scikit-learn/scikit-learn/_build/latest?definitionId=1&branchName=main

.. |CircleCI| image:: https://circleci.com/gh/scikit-learn/scikit-learn/tree/main.svg?style=shield
   :target: https://circleci.com/gh/scikit-learn/scikit-learn

.. |Codecov| image:: https://codecov.io/gh/scikit-learn/scikit-learn/branch/main/graph/badge.svg?token=Pk8G9gg3y9
   :target: https://codecov.io/gh/scikit-learn/scikit-learn

.. |Nightly wheels| image:: https://github.com/scikit-learn/scikit-learn/actions/workflows/wheels.yml/badge.svg?event=schedule
   :target: https://github.com/scikit-learn/scikit-learn/actions?query=workflow%3A%22Wheel+builder%22+event%3Aschedule

.. |Ruff| image:: https://img.shields.io/badge/code%20style-ruff-000000.svg
   :target: https://github.com/astral-sh/ruff

.. |PythonVersion| image:: https://img.shields.io/pypi/pyversions/scikit-learn.svg
   :target: https://pypi.org/project/scikit-learn/

.. |PyPi| image:: https://img.shields.io/pypi/v/scikit-learn
   :target: https://pypi.org/project/scikit-learn

.. |DOI| image:: https://zenodo.org/badge/21369/scikit-learn/scikit-learn.svg
   :target: https://zenodo.org/badge/latestdoi/21369/scikit-learn/scikit-learn

.. |Benchmark| image:: https://img.shields.io/badge/Benchmarked%20by-asv-blue
   :target: https://scikit-learn.org/scikit-learn-benchmarks

.. |PythonMinVersion| replace:: 3.10
.. |NumPyMinVersion| replace:: 1.22.0
.. |SciPyMinVersion| replace:: 1.8.0
.. |JoblibMinVersion| replace:: 1.2.0
.. |ThreadpoolctlMinVersion| replace:: 3.1.0
.. |MatplotlibMinVersion| replace:: 3.5.0
.. |Scikit-ImageMinVersion| replace:: 0.19.0
.. |PandasMinVersion| replace:: 1.4.0
.. |SeabornMinVersion| replace:: 0.9.0
.. |PytestMinVersion| replace:: 7.1.2
.. |PlotlyMinVersion| replace:: 5.14.0

.. image:: https://raw.githubusercontent.com/scikit-learn/scikit-learn/main/doc/logos/scikit-learn-logo.png
   :target: https://scikit-learn.org/
   :align: center

scikit-learn
============

**scikit-learn** is a Python module for machine learning, built on top of SciPy, and distributed under the 3-Clause BSD license. The project was initiated in 2007 by David Cournapeau as a Google Summer of Code project, and has since grown with contributions from many volunteers. See the `About us <https://scikit-learn.org/dev/about.html#authors>`__ page for a list of core contributors. It is currently maintained by a dedicated team of volunteers.

**Website**: https://scikit-learn.org

Installation
------------

Dependencies
~~~~~~~~~~~~

scikit-learn requires the following dependencies:

- Python (>= |PythonMinVersion|)
- NumPy (>= |NumPyMinVersion|)
- SciPy (>= |SciPyMinVersion|)
- joblib (>= |JoblibMinVersion|)
- threadpoolctl (>= |ThreadpoolctlMinVersion|)

Plotting capabilities in scikit-learn (functions starting with ``plot_`` and classes ending with ``Display``) require Matplotlib (>= |MatplotlibMinVersion|). For running the examples, Matplotlib (>= |MatplotlibMinVersion|) is required. Some examples require scikit-image (>= |Scikit-ImageMinVersion|), pandas (>= |PandasMinVersion|), seaborn (>= |SeabornMinVersion|), or plotly (>= |PlotlyMinVersion|).

User Installation
~~~~~~~~~~~~~~~~~

If you have a working installation of NumPy and SciPy, the easiest way to install scikit-learn is using ``pip``::

    pip install -U scikit-learn

Alternatively, you can use ``conda``::

    conda install -c conda-forge scikit-learn

For detailed installation instructions, refer to the `official documentation <https://scikit-learn.org/stable/install.html>`_.

Changelog
---------

A history of notable changes to scikit-learn is available in the `changelog <https://scikit-learn.org/dev/whats_new.html>`__.

Development
-----------

We welcome contributors of all experience levels. The scikit-learn community strives to be helpful, welcoming, and effective. The `Development Guide <https://scikit-learn.org/stable/developers/index.html>`_ provides detailed information on contributing code, documentation, tests, and more. Below is some basic information to get started.

Important Links
~~~~~~~~~~~~~~~

- **Official source code repository**: https://github.com/scikit-learn/scikit-learn
- **Download releases**: https://pypi.org/project/scikit-learn/
- **Issue tracker**: https://github.com/scikit-learn/scikit-learn/issues

Source Code
~~~~~~~~~~~

To access the latest source code, use the following command::

    git clone https://github.com/scikit-learn/scikit-learn.git

Contributing
~~~~~~~~~~~~

To contribute to scikit-learn, please review our `Contributing Guide <https://scikit-learn.org/dev/developers/contributing.html>`_ for detailed information.

Testing
~~~~~~~

After installation, you can run the test suite from outside the source directory (requires ``pytest`` >= |PytestMinVersion|)::

    pytest sklearn

For more details, see the `testing guide <https://scikit-learn.org/dev/developers/contributing.html#testing-and-improving-test-coverage>`_. Random number generation during testing can be controlled by setting the ``SKLEARN_SEED`` environment variable.

Submitting a Pull Request
~~~~~~~~~~~~~~~~~~~~~~~~~

Before submitting a Pull Request, ensure your code complies with our guidelines by reviewing the `full Contributing page <https://scikit-learn.org/stable/developers/index.html>`_.

Project History
---------------

The scikit-learn project began in 2007 as a Google Summer of Code project by David Cournapeau. Since then, numerous volunteers have contributed to its development. The `About us <https://scikit-learn.org/dev/about.html#authors>`__ page lists core contributors. The project is maintained by a team of volunteers. **Note**: scikit-learn was previously known as `scikits.learn`.

Help and Support
----------------

Documentation
~~~~~~~~~~~~~

- **Stable release documentation**: https://scikit-learn.org
- **Development version documentation**: https://scikit-learn.org/dev/
- **FAQ**: https://scikit-learn.org/stable/faq.html

Communication
~~~~~~~~~~~~~

Main Channels
^^^^^^^^^^^^^

- **Website**: https://scikit-learn.org
- **Blog**: https://blog.scikit-learn.org
- **Mailing list**: https://mail.python.org/mailman/listinfo/scikit-learn

Developer & Support
^^^^^^^^^^^^^^^^^^^

- **GitHub Discussions**: https://github.com/scikit-learn/scikit-learn/discussions
- **Stack Overflow**: https://stackoverflow.com/questions/tagged/scikit-learn
- **Discord**: https://discord.gg/h9qyrK8Jc8

Social Media Platforms
^^^^^^^^^^^^^^^^^^^^^^

- **LinkedIn**: https://www.linkedin.com/company/scikit-learn
- **YouTube**: https://www.youtube.com/channel/UCJosFjYm0ZYVUARxuOZqnnw/playlists
- **Facebook**: https://www.facebook.com/scikitlearnofficial/
- **Instagram**: https://www.instagram.com/scikitlearnofficial/
- **TikTok**: https://www.tiktok.com/@scikit.learn
- **Bluesky**: https://bsky.app/profile/scikit-learn.org
- **Mastodon**: https://mastodon.social/@sklearn@fosstodon.org

Resources
^^^^^^^^^

- **Calendar**: https://blog.scikit-learn.org/calendar/
- **Logos & Branding**: https://github.com/scikit-learn/scikit-learn/tree/main/doc/logos

Citation
~~~~~~~~

If you use scikit-learn in a scientific publication, please include a citation. Details are available at: https://scikit-learn.org/stable/about.html#citing-scikit-learn
