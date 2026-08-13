# breezonto/faiss

This project is not maintained by the official Faiss team, and the maintainers and contributors of this repository are not affiliated with Faiss or the Faiss project. Any modifications, extensions, or experimental features introduced in this codebase are independently developed for research and exploratory purposes and should not be considered part of the official Faiss project.

This repository retains all applicable copyright and license notices from the upstream project in accordance with the Apache License 2.0.

## Features from This Repo

## Installation Guide

Refers to [official guide](./INSTALL.md). Briefly, below are necessary dependencies for building targets _faiss_, _swigfaiss_ and _python package_:

- **OpenBLAS**: an open-source implementation of the BLAS (Basic Linear Algebra Subprograms) and LAPACK APIs, which provide highly optimized low-level routines for numerical linear algebra operations.

- **Swig**: a tool that automatically generates language bindings between C/C++ code and high-level languages such as Python.

- **gflags**: a C++ library for defining and parsing command-line arguments.a C++ library for defining and parsing command-line arguments.

```
sudo apt update
sudo apt install libopenblas-dev # install openblas
sudo apt install swig

# inside the miniconda virtual environment, install gflags
conda install -c conda forge gflags

# if build with libuv
conda install -c rapidsai -c conda-forge -c nvidia \
    libcuvs=26.06 \
    'cuda-version=13.0'
```


