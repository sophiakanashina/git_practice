# Practice Project

A small Python project used to practice **Git workflows, modular code structure, testing, and documentation with Sphinx**.

## Project Structure

```
project/
├── src/
│   ├── main.py
│   ├── utils.py
│   └── models/
│       └── model.py
├── tests/
│   └── test_main.py
├── docs/
│   ├── source/
│   │   ├── conf.py
│   │   ├── index.rst
│   │   └── api.rst
│   └── Makefile
├── environment.yml
└── README.md
```

## Features

* Modular Python code (`main`, `utils`, `models`)
* Docstrings for functions and classes
* Automatic documentation generation with **Sphinx**
* Basic test structure with `tests/`
* Continuous integration setup

## Installation

Clone the repository:

```bash
git clone https://github.com/sophiakanashina/git_practice.git
cd git_practice
```

Create the environment:

```bash
micromamba env create -f environment.yml
micromamba activate spreadinterp
```

Install the package:

```bash
pip install -e .
```

## Running the Code

Example:

```bash
python src/main.py
```

## Running Tests

```bash
pytest
```

## Building Documentation

Go to the documentation directory:

```bash
cd docs
```

Build the HTML documentation:

```bash
make html
```

Open the generated docs:

```
docs/build/html/index.html
```

## Documentation

Documentation is generated automatically from **Python docstrings** using Sphinx.

Main documentation components:

* API documentation via `autodoc`
* Project structure overview
* Function and module descriptions

## Technologies Used

* Python
* Sphinx
* pytest
* Git & GitHub
* micromamba / conda environments

## Purpose

This repository is primarily for practicing:

* Git branching and merging
* Pull requests
* Documentation workflows
* Continuous integration

## Author

Sophia
