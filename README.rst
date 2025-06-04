.. -*- mode: rst -*-

.. image:: https://raw.githubusercontent.com/scikit-learn/scikit-learn/main/doc/logos/scikit-learn-logo.png
   :align: center
   :target: https://scikit-learn.org/
   :alt: scikit-learn logo

|Azure| |Codecov| |CircleCI| |Nightly wheels| |Ruff| |PythonVersion| |PyPi| |DOI| |Benchmark|

.. |Azure| image:: https://dev.azure.com/scikit-learn/scikit-learn/_apis/build/status/scikit-learn.scikit-learn?branchName=main
   :target: https://dev.azure.com/scikit-learn/scikit-learn/_build/latest?definitionId=1&branchName=main
   :alt: Azure Build Status

.. |CircleCI| image:: https://circleci.com/gh/scikit-learn/scikit-learn/tree/main.svg?style=shield
   :target: https://circleci.com/gh/scikit-learn/scikit-learn
   :alt: CircleCI Build Status

.. |Codecov| image:: https://codecov.io/gh/scikit-learn/scikit-learn/branch/main/graph/badge.svg?token=Pk8G9gg3y9
   :target: https://codecov.io/gh/scikit-learn/scikit-learn
   :alt: Codecov Coverage

.. |Nightly wheels| image:: https://github.com/scikit-learn/scikit-learn/actions/workflows/wheels.yml/badge.svg?event=schedule
   :target: https://github.com/scikit-learn/scikit-learn/actions?query=workflow%3A%22Wheel+builder%22+event%3Aschedule
   :alt: Nightly Wheels Status

.. |Ruff| image:: https://img.shields.io/badge/code%20style-ruff-000000.svg
   :target: https://github.com/astral-sh/ruff
   :alt: Ruff Code Style

.. |PythonVersion| image:: https://img.shields.io/pypi/pyversions/scikit-learn.svg
   :target: https://pypi.org/project/scikit-learn/
   :alt: Python Versions Supported

.. |PyPi| image:: https://img.shields.io/pypi/v/scikit-learn
   :target: https://pypi.org/project/scikit-learn
   :alt: PyPI Version

.. |DOI| image:: https://zenodo.org/badge/21369/scikit-learn/scikit-learn.svg
   :target: https://zenodo.org/badge/latestdoi/21369/scikit-learn/scikit-learn
   :alt: DOI

.. |Benchmark| image:: https://img.shields.io/badge/Benchmarked%20by-asv-blue
   :target: https://scikit-learn.org/scikit-learn-benchmarks
   :alt: Benchmarked by ASV

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

scikit-learn
============

**scikit-learn** is a powerful Python library for machine learning, built on SciPy and distributed under the 3-Clause BSD license. Launched in 2007 by David Cournapeau as a Google Summer of Code project, it has grown with contributions from a global community of volunteers. Explore the `About Us <https://scikit-learn.org/dev/about.html#authors>`_ page for core contributors. A dedicated team maintains the project, ensuring its reliability and growth.

**Website**: https://scikit-learn.org

Get Started
-----------

Dependencies
~~~~~~~~~~~~

scikit-learn requires:

- Python (>= |PythonMinVersion|)
- NumPy (>= |NumPyMinVersion|)
- SciPy (>= |SciPyMinVersion|)
- joblib (>= |JoblibMinVersion|)
- threadpoolctl (>= |ThreadpoolctlMinVersion|)

For plotting (functions starting with ``plot_`` or classes ending with ``Display``), you need Matplotlib (>= |MatplotlibMinVersion|). Some examples also require:

- scikit-image (>= |Scikit-ImageMinVersion|)
- pandas (>= |PandasMinVersion|)
- seaborn (>= |SeabornMinVersion|)
- plotly (>= |PlotlyMinVersion|)

Installation
~~~~~~~~~~~~

With NumPy and SciPy installed, install scikit-learn using::

    pip install -U scikit-learn

Or, with conda::

    conda install -c conda-forge scikit-learn

For detailed instructions, visit the `installation guide <https://scikit-learn.org/stable/install.html>`_.

What's New
----------

Stay updated with the latest features and fixes in the `changelog <https://scikit-learn.org/dev/whats_new.html>`_.

Contribute
----------

We welcome contributors of all skill levels! Our community is inclusive, supportive, and collaborative. The `Development Guide <https://scikit-learn.org/stable/developers/index.html>`_ covers contributing code, documentation, and tests.

Key Links
~~~~~~~~~

- **Source Code**: https://github.com/scikit-learn/scikit-learn
- **Releases**: https://pypi.org/project/scikit-learn/
- **Issues**: https://github.com/scikit-learn/scikit-learn/issues

Get the Source Code
~~~~~~~~~~~~~~~~~~~

Clone the repository with::

    git clone https://github.com/scikit-learn/scikit-learn.git

Contributing
~~~~~~~~~~~~

Learn how to contribute in the `Contributing Guide <https://scikit-learn.org/dev/developers/contributing.html>`_.

Testing
~~~~~~~

Run tests after installation (requires ``pytest`` >= |PytestMinVersion|)::

    pytest sklearn

Control random number generation during testing with the ``SKLEARN_SEED`` environment variable. See the `testing guide <https://scikit-learn.org/dev/developers/contributing.html#testing-and-improving-test-coverage>`_ for details.

Submitting a Pull Request
~~~~~~~~~~~~~~~~~~~~~~~~

Before submitting, review the `Contributing Guidelines <https://scikit-learn.org/stable/developers/index.html>`_ to ensure compliance.

Project History
---------------

Started in 2007 by David Cournapeau, scikit-learn (formerly `scikits.learn`) has evolved through contributions from a vibrant community. The `About Us <https://scikit-learn.org/dev/about.html#authors>`_ page lists core contributors. A volunteer team maintains the project.

Support
-------

Documentation
~~~~~~~~~~~~~

- **Stable Release**: https://scikit-learn.org
- **Development Version**: https://scikit-learn.org/dev/
- **FAQ**: https://scikit-learn.org/stable/faq.html

Connect with Us
~~~~~~~~~~~~~~~

- **Website**: https://scikit-learn.org
- **Blog**: https://blog.scikit-learn.org
- **Mailing List**: https://mail.python.org/mailman/listinfo/scikit-learn
- **GitHub Discussions**: https://github.com/scikit-learn/scikit-learn/discussions
- **Stack Overflow**: https://stackoverflow.com/questions/tagged/scikit-learn
- **Discord**: https://discord.gg/h9qyrK8Jc8

Follow Us
~~~~~~~~~

- **LinkedIn**: https://www.linkedin.com/company/scikit-learn
- **YouTube**: https://www.youtube.com/channel/UCJosFjYm0ZYVUARxuOZqnnw/playlists
- **Facebook**: https://www.facebook.com/scikitlearnofficial/
- **Instagram**: https://www.instagram.com/scikitlearnofficial/
- **TikTok**: https://www.tiktok.com/@scikit.learn
- **Bluesky**: https://bsky.app/profile/scikit-learn.org
- **Mastodon**: https://mastodon.social/@sklearn@fosstodon.org

Resources
~~~~~~~~~

- **Calendar**: https://blog.scikit-learn.org/calendar/
- **Logos & Branding**: https://github.com/scikit-learn/scikit-learn/tree/main/doc/logos

Citation
~~~~~~~~

Using scikit-learn in a publication? Please cite it! Details at: https://scikit-learn.org/stable/about.html#citing-scikit-learn
