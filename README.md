# Data-Driven Analysis of Fluid Flows

## Objective
This repository contains code for a data-driven analysis of fluid flows using Singular Value Decomposition (SVD) and various denoising techniques. The project aims to extract dominant modes from fluid flow data, perform denoising to enhance the signal-to-noise ratio, and evaluate the effectiveness of the denoising methods.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Documentation](#documentation)
- [License](#license)

## Introduction

Fluid flow analysis plays a crucial role in various fields such as engineering, meteorology, and environmental science. Traditional computational fluid dynamics (CFD) simulations can be computationally expensive, especially for large-scale systems. Data-driven approaches offer an alternative by leveraging observational data to analyze fluid behavior.

This project focuses on analyzing fluid flow data obtained from video recordings. By applying Singular Value Decomposition (SVD) and denoising techniques, we aim to identify dominant modes in the flow, remove noise, and improve the quality of the data for further analysis.

## Installation

To run the code in this repository, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/dhruvpsr/data-driven-fluid-flows.git

2. Navigate to the project directory:
`cd data-driven-fluid-flows`

3. Install the required dependencies:
`pip install -r requirements_.txt`

## Usage
1. Open the Jupyter Notebook Data_Driven_Analysis_Of_Fluid_Flows.ipynb.
2. Follow the instructions provided in the notebook to execute each cell sequentially.
3. Explore the results, including visualizations of dominant modes, denoised frames, and evaluation metrics.
4. Experiment with different parameters and denoising techniques to see their effects on the analysis.

## File Structure
The repository has the following structure:

- `Data_Driven_Analysis_Of_Fluid_Flows.ipynb`: Jupyter Notebook containing the main code for data analysis and denoising.
- `requirements.txt`: List of Python dependencies required to run the code.

## Documentation
Detailed documentation explaining the methodology, algorithms, and implementation details can be found in the notebook itself. Additionally, comments and docstrings are provided throughout the code to enhance readability and understanding.

## License
This project is licensed under the MIT License.
