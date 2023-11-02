# Deploy CI Platform for a Python Module

[![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/nps5696/cmpsc487-refactor-ci/CI)](https://github.com/nps5696/cmpsc487-refactor-ci/actions)

### Github action is used as CI, it runs these checks

- Doctest
- Pytest 
- Pytest Coverage > 80%
- Pylint > 8.0 rating
- Poetry - package manager and builder

### Prerequisites

- Python 3.x
- Poetry (for dependency management)
- Pytest
- Pytest-cov
- Pylint

### Installation for End User

1. Clone the repository:
2. Run poetry build, this will build dist directory where you can find tarball package
