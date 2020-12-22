# FastVector

![Python](https://img.shields.io/badge/python-3.7%20%7C%203.8-blue)
![License](https://camo.githubusercontent.com/890acbdcb87868b382af9a4b1fac507b9659d9bf/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6c6963656e73652d4d49542d626c75652e737667)
[![Build](https://github.com/franneck94/Python-Project-Template/workflows/ci-test/badge.svg)](https://github.com/franneck94/Python-Project-Template/actions?query=workflow%3Aci-test)
[![codecov](https://codecov.io/gh/franneck94/python-project-template/branch/master/graph/badge.svg)](https://codecov.io/gh/franneck94/python-project-template)
[![Documentation](https://img.shields.io/badge/ref-Documentation-blue)](https://franneck94.github.io/Python-Project-Template/)

## Template For Python Projects

This is a template for Python projects. What you get:

- Source code and test code is seperated in different directories.
- Different tasks seperated by [Make](https://www.gnu.org/software/make/) tasks.
- External libraries installed and managed by [Pip](https://pypi.org/project/pip/).
- Setup for tests using [Pytest](https://docs.pytest.org/en/stable/).
- Bechmark tests using [Pytest-Benchmark](https://github.com/ionelmc/pytest-benchmark)
- Continuous testing with [Travis-CI](https://travis-ci.org/).
- Code coverage reports, including automatic upload to [Codecov](https://codecov.io).
- Code documentation with [Mkdocs](https://www.mkdocs.org/).
- Example of own Python package with the use of [Cython](https://cython.org/)
- Optional: Use of [VSCode](https://code.visualstudio.com/) with the Python and UnitTest extension.

## Structure

``` text
├── Makefile
├── setup.py
├── tests
│   ├── __init__.py
│   └── test_benchmark_computations.py
├── docs
│   └── build
│   │   └── html...
│   └── source
│   │   └── conf.py
├── fastvector
│   └── __init__.py
│   ├── vector.py
│   └── computations.py
└── tests
    ├── __init__.py
    ├── test_computations.py
    └── test_vector.py
```

The name of the example package is called fastvector.
Sources of the package go in [fastvector/](fastvector/),tests go in [tests/](tests/) and benchmarks go in [benchmarks/](benchmarks/).
