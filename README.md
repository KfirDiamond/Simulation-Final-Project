# 🔬 Simulation Pro: Stochastic Modeling & Queueing Systems

![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)
![Dependencies](https://img.shields.io/badge/dependencies-up%20to%20date-brightgreen.svg)
![Academic Project](https://img.shields.io/badge/course-Simulation%20Pro-orange.svg)

This repository contains the final project for the Simulation Pro course, developed as part of the Industrial Engineering and Management academic curriculum at Ariel University. 

It utilizes Python and the `butools` (version 2.0) library to analyze and simulate various stochastic models, including Phase-Type (PH) distributions, Markovian Arrival Processes (MAP), and advanced queueing networks.

## 📑 Table of Contents
- [Features](#-features)
- [Dependencies](#-dependencies)
- [Installation & Setup](#-installation--setup)
- [Usage](#-usage)

---

## 🚀 Features

- **Phase-Type (PH) Distributions:** Generation, moments calculation, and trace fitting using G-FIT EM algorithms.
- **Markovian Arrival Processes (MAP):** Creation from moments, correlation analysis, and data fitting.
- **Matrix-Analytic Methods (MAM):** Solving QBD, M/G/1, and G/M/1 type Markov chains, alongside canonical Markovian fluid models.
- **Random PH Generator:** Advanced sampling of Phase-Type distributions (e.g., mixtures of Erlangs) to generate robust data for feed-forward queueing networks and simulations.

## 🛠 Dependencies

The project requires **Python 3.x** and relies on the following core libraries for data analytics and simulation:

* `matplotlib` (3.7.1)
* `numpy` (1.26.4)
* `pandas` (3.0.1)
* `scipy` (1.17.1)
* `seaborn` (0.13.2)
* `simpy` (4.1.1)
* `statsmodels` (0.14.1)
* `tqdm` (4.66.1)

> **Note:** The `butools` package is included locally within the project structure and does not need to be installed via pip.

## ⚙️ Installation & Setup

1. **Clone this repository** to your local machine:
   ```bash
   git clone [https://github.com/YourUsername/YourRepository.git](https://github.com/YourUsername/YourRepository.git)
   cd YourRepository
