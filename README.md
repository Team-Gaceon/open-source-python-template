# Open Source Python Template
An advanced template for designing and developing Python projects with CI/CD.

## Initial Setup
Install PDM as package and dependency manager:

    pip install pdm

Install initial dependencie:

    pdm install --dev
To update dependencies, run the following:

    pdm update

## Using Features
To use mypy, run the following:

    pdm run mypy <filename>

To use ruff, run the following: 

    pdm run ruff <filename>

To use pytest, run the following:

    pdm run pytest tests/test_addition.py

To run the application, run the following: 

    pdm run src/main.py

## Contributors - Team Glaceon
- Yifei Zhuang
- Fan Yang
- Bowen Gong
- Yanglin Tao
- Winnie Zheng
- Kaining Mao
