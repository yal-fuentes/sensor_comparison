# Sensor-comparison

## Ab test

This repository contains notebooks used especifically for analysing the AB test between sensors described in [Data Analyst Challenge](https://humanengineeeringhq.notion.site/Data-Analyst-Challenge-b8289a6eab6741a1a77577e07ad35f7c). The notebook can be found inside [sensor_comparison](./sensor_comparison/).

## Tests

By default Poetry creates a test folder, but for now there's no tests for this repository.

## Using poetry

1. Install [Poetry 1.1.14+](https://python-poetry.org/).
2. Initialise the project using `poetry init`.
3. Dependencies would be updated from `pyproject.toml`.
4. Create jupyter notebook kernel using `poetry run ipython kernel install --user --name sensor-comparison`.
5. Activate environment using `poetry shell`.
6. Use jupyter notebook as usual selecting the correct kernel.

## Using venv

1. Generate install script and requirements file using examples from other Skunkworks analytics repositories. Example [analytics.user-daily-metrics](https://github.com/Skunkworks-Games/analytics.user-daily-metrics)
2. Populate requirements file based on content in `pyproject.toml`.
3. To install all required python libraries, run `bash install.sh`
4. Activate the virtual environment using `source venv/bin/activate`
