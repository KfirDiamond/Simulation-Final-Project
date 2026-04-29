# Simulation Final Project

This repository contains the final project for the Simulation Pro course. It utilizes Python and the `butools` (version 2.0) library to analyze and simulate various stochastic models, including Phase-Type (PH) distributions, Markovian Arrival Processes (MAP), and queueing systems.

## Features

- **Phase-Type (PH) Distributions**: Generation, moments calculation, and trace fitting (using G-FIT EM algorithms).
- **Markovian Arrival Processes (MAP)**: Creation from moments, correlation analysis, and data fitting.
- **Matrix-Analytic Methods (MAM)**: Solving QBD, M/G/1, and G/M/1 type Markov chains, as well as canonical Markovian fluid models.
- **Random PH Generator**: Advanced sampling of Phase-Type distributions (e.g., mixtures of Erlangs) to generate data for feed-forward queueing networks and simulations.

## Dependencies

The project requires Python 3.x and the following packages:
- matplotlib==3.7.1
- numpy==1.26.4
- pandas==3.0.1
- scipy==1.17.1
- seaborn==0.13.2
- simpy==4.1.1
- statsmodels==0.14.1
- tqdm==4.66.1

*Note: The `butools` package is included locally within the project structure.*

## Getting Started

1. Clone this repository.
2. Create a virtual environment and install the required dependencies: `pip install numpy scipy pandas matplotlib tqdm`.
3. Run your main simulation entry points (for example, `python sim_course_pycharm/sample_PH.py`).

## License

[Add your license information here, e.g., MIT, GPL, etc.]
