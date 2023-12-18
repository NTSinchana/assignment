# Data Pipeline

## Overview

This project implements a scalable data pipeline using PySpark. The pipeline includes plugable transformation functions, connectors for reading/writing data from/to various sources, and supports multiple data formats.

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Connectors](#connectors)
- [Transformations](#transformations)
- [Testing](#testing)
- [Deployment](#deployment)
- [CICD](#cicd)
- [Contributing](#contributing)
- [License](#license)

## Project Structure

The project follows the structure below:

```plaintext
data_pipeline/
|-- src/
|   |-- main.py
    |-- s3_connector.py

|   |-- group_by_measure.py
|   |-- join_datasets.py
|   |-- test_transformations.py
|-- requirements.txt
|-- setup.py
|-- README.md
|-- .gitignore
