# Oil and Gas Data Analysis and Prediction

This repository contains a Python script designed for analyzing, training, and predicting data related to various business cases in the oil and gas industry. The script uses linear regression models to train on historical data, selects the best fit functions, and evaluates test data points against these models.

## Table of Contents

- [Overview](#overview)
- [Business Cases](#business-cases)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Overview

The script can be applied to various business cases such as predictive maintenance, production optimization, reservoir characterization, and environmental monitoring. It involves loading data, training models, selecting ideal functions, and predicting and evaluating test data points.

## Business Cases

### Predictive Maintenance for Equipment
Analyze historical sensor data to predict equipment failures before they occur.

### Production Optimization in Oil Wells
Optimize oil production by analyzing historical production data and adjusting input parameters.

### Reservoir Characterization and Simulation
Characterize reservoirs using geological data and production history to predict future behavior.

### Environmental Monitoring and Compliance
Ensure environmental compliance by analyzing data from environmental sensors and predicting pollution levels.

## Installation

To run the script, you'll need Python 3.x and the following libraries:

- pandas
- numpy
- sqlalchemy
- scikit-learn
- matplotlib
- bokeh

You can install these libraries using pip:

```bash
pip install pandas numpy sqlalchemy scikit-learn matplotlib bokeh
```

## Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/oil-and-gas-data-analysis.git
   cd oil-and-gas-data-analysis
   ```

2. **Create a new branch for development:**

   ```bash
   git checkout -b develop
   ```

3. **Run the main script:**

   Ensure you have your data files (`train.csv`, `ideal.csv`, and `test.csv`) in the same directory as the script.

   ```bash
   python main.py
   ```

4. **Run tests:**

   ```bash
   python -m unittest discover
   ```

## Project Structure

```
.
├── main.py                     # Main script for data analysis and prediction
├── DataProcessor.py            # Module for data processing
├── ModelTrainer.py             # Module for training models
├── Predictor.py                # Module for predicting and evaluating test data
├── Plotter.py                  # Module for plotting results
├── tests/                      # Unit tests
│   ├── test_DataProcessor.py
│   ├── test_ModelTrainer.py
│   ├── test_Predictor.py
│   └── test_Plotter.py
├── train.csv                   # Training data
├── ideal.csv                   # Ideal functions data
├── test.csv                    # Test data
└── README.md                   # This README file
```

## Contributing

1. **Fork the repository:**

   Click the "Fork" button at the top right of this repository.

2. **Clone your forked repository:**

   ```bash
   git clone https://github.com/yourusername/oil-and-gas-data-analysis.git
   cd oil-and-gas-data-analysis
   ```

3. **Create a new branch for your feature or bugfix:**

   ```bash
   git checkout -b feature-or-bugfix-branch-name
   ```

4. **Commit your changes:**

   ```bash
   git add .
   git commit -m "Description of your changes"
   ```

5. **Push your changes to GitHub:**

   ```bash
   git push origin feature-or-bugfix-branch-name
   ```

6. **Create a pull request:**

   Go to your forked repository on GitHub and click the "New pull request" button.

## License

This project was developed and submitted as an assignment at the International University of Applied Sciences, Germany.

---

Feel free to modify this `README.md` to better suit your project's specific details and requirements.
