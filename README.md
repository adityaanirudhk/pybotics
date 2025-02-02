<br />
<p align="center">
  <a href="https://github.com/nnadeau/pybotics">
    <img src="https://raw.githubusercontent.com/nnadeau/pybotics/master/media/robotic-arm.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">pybotics</h3>

  <p align="center">
    The Python Toolbox for Robotics
    <br />
    <a href="https://pybotics.readthedocs.io/"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/nnadeau/pybotics/tree/master/examples">View Demo</a>
    ·
    <a href="https://github.com/nnadeau/pybotics/issues">Report Bug</a>
    ·
    <a href="https://github.com/nnadeau/pybotics/issues">Request Feature</a>
  </p>
</p>

[![GitHub issues](https://img.shields.io/github/issues/nnadeau/pybotics.svg)](https://github.com/nnadeau/pybotics/issues)
[![GitHub forks](https://img.shields.io/github/forks/nnadeau/pybotics.svg)](https://github.com/nnadeau/pybotics/network)
[![GitHub stars](https://img.shields.io/github/stars/nnadeau/pybotics.svg)](https://github.com/nnadeau/pybotics/stargazers)
[![GitHub tag](https://img.shields.io/github/tag/nnadeau/pybotics.svg?maxAge=2592000?style=flat-square)](https://github.com/nnadeau/pybotics/releases)

[![PyPI Version](https://img.shields.io/pypi/v/pybotics.svg)](https://pypi.python.org/pypi/pybotics)
[![PyPI License](https://img.shields.io/pypi/l/pybotics.svg)](https://pypi.python.org/pypi/pybotics)
[![PyPI Wheel](https://img.shields.io/pypi/wheel/pybotics.svg)](https://pypi.python.org/pypi/pybotics)
[![PyPI Format](https://img.shields.io/pypi/format/pybotics.svg)](https://pypi.python.org/pypi/pybotics)
[![PyPI Pythons](https://img.shields.io/pypi/pyversions/pybotics.svg)](https://pypi.python.org/pypi/pybotics)
[![PyPI Implementation](https://img.shields.io/pypi/implementation/pybotics.svg)](https://pypi.python.org/pypi/pybotics)

[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)
[![Test](https://github.com/nnadeau/pybotics/workflows/Test/badge.svg)](https://github.com/nnadeau/pybotics/actions)
[![Release](https://github.com/nnadeau/pybotics/workflows/Release/badge.svg)](https://github.com/nnadeau/pybotics/actions)
[![Publish](https://github.com/nnadeau/pybotics/workflows/Publish/badge.svg)](https://github.com/nnadeau/pybotics/actions)

[![Documentation Status](https://readthedocs.org/projects/pybotics/badge/?version=latest)](https://pybotics.readthedocs.io/en/latest/?badge=latest)
[![DOI](https://joss.theoj.org/papers/10.21105/joss.01738/status.svg)](https://doi.org/10.21105/joss.01738)
[![DOI](https://zenodo.org/badge/66797360.svg)](https://zenodo.org/badge/latestdoi/66797360)

[![Twitter](https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Fgithub.com%2Fnnadeau%2Fpybotics)](https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2Fnnadeau%2Fpybotics)

## Contents

- [Contents](#contents)
- [Overview](#overview)
- [Usage](#usage)
  - [Documentation](#documentation)
  - [Installation](#installation)
  - [Applications & Examples](#applications--examples)
- [Featured In](#featured-in)
- [Citing](#citing)
- [Development and Community Guidelines](#development-and-community-guidelines)
  - [Local Development](#local-development)
  - [Submit an Issue](#submit-an-issue)
  - [Contributing](#contributing)
  - [Testing](#testing)

## Overview

`Pybotics` is an open-source Python toolbox for robot kinematics and calibration.
It was designed to provide a simple, clear, and concise interface to quickly simulate and evaluate common robot concepts, such as kinematics, dynamics, trajectory generations, and calibration.
The toolbox is specifically designed for use with the [Modified Denavit–Hartenberg parameters convention](https://en.wikipedia.org/wiki/Denavit%E2%80%93Hartenberg_parameters#Modified_DH_parameters).

## Usage

### Documentation

Please visit https://pybotics.readthedocs.io/

### Installation

```bash
# python3 is mapped to pip or inside a venv
pip install pybotics

# python3-pip
pip3 install pybotics

# https://github.com/pypa/pipenv
pipenv install pybotics

# https://github.com/sdispater/poetry
poetry add pybotics
```

### Applications & Examples

- [Basic Usage](examples/basic_usage.py)
- [Kinematics](examples/kinematics.ipynb)
- [Calibration](examples/calibration.ipynb)
- [Trajectory and Path Planning](examples/trajectory_generation.ipynb)
- [Machine Learning](examples/machine_learning.ipynb)
- [Dynamics](examples/dynamics.ipynb)

## Featured In

- [Impedance Control Self-Calibration of a Collaborative Robot Using Kinematic Coupling](https://www.mdpi.com/2218-6581/8/2/33/htm)
- [PyCon Canada 2017](https://2017.pycon.ca/schedule/53/)
  - [Talk Photos](https://500px.com/nicholasnadeau/galleries/pycon-canada-2017)
  - [Slides](https://github.com/nnadeau/pycon-canada-2017)
- [Montreal-Python 2017](https://www.youtube.com/watch?v=wgKoGA69YXQ)

## Citing

Please cite the following articles if you use `pybotics` in your research:

> Nadeau, (2019). Pybotics: Python Toolbox for Robotics. Journal of Open Source Software, 4(41), 1738, https://doi.org/10.21105/joss.01738

```
@article{nadeau2019pybotics,
  doi = {10.21105/joss.01738},
  url = {https://doi.org/10.21105/joss.01738},
  year = {2019},
  month = sep,
  publisher = {The Open Journal},
  volume = {4},
  number = {41},
  pages = {1738},
  author = {Nicholas Nadeau},
  title = {Pybotics: Python Toolbox for Robotics},
  journal = {Journal of Open Source Software}
}
```

> Nadeau, Nicholas A., Ilian A. Bonev, and Ahmed Joubair. "Impedance Control Self-Calibration of a Collaborative Robot Using Kinematic Coupling." Robotics 8.2 (2019): 33.

```
@article{nadeau2019impedance,
  title={Impedance Control Self-Calibration of a Collaborative Robot Using Kinematic Coupling},
  volume={8},
  ISSN={2218-6581},
  url={http://dx.doi.org/10.3390/robotics8020033},
  DOI={10.3390/robotics8020033},
  number={2},
  journal={Robotics},
  publisher={MDPI AG},
  author={Nadeau, Nicholas A. and Bonev, Ilian A. and Joubair, Ahmed},
  year={2019},
  month={Apr},
  pages={33}
}
```

## Development and Community Guidelines

### Local Development

- Install the dev virtual environment:

```bash
poetry install
```

### Submit an Issue

- Navigate to the repository's [issue tab](https://github.com/nnadeau/pybotics/issues)
- Search for related existing issues
- If necessary, create a new issue using the provided templates

### Contributing

- Please see [`CONTRIBUTING.md`](.github/CONTRIBUTING.md) and the [Code of Conduct](CODE_OF_CONDUCT.md) for how to contribute to the project

### Testing

- Please review the [`Makefile`](Makefile) for an overview of all available tests
- The most important tests and `make` commands are highlighted below:

```bash
# auto-format code
make format

# perform all static tests
make check

# run all python tests
make test
```

### GitHub Actions

- This repo uses [`semantic-releases`](https://github.com/semantic-release/) to generate releases and release notes automatically from commits
  - A [`PERSONAL_TOKEN` Actions secret](https://github.com/nnadeau/pybotics/settings/secrets/actions) from a [Personal Token](https://github.com/settings/tokens) with a [`public_repo` scope](https://github.com/semantic-release/github#github-authentication) is needed for CI releases

---

Icons made by <a href="https://icon54.com/" title="Pixel perfect">Pixel perfect</a> from <a href="https://www.flaticon.com/" title="Flaticon"> www.flaticon.com</a>
