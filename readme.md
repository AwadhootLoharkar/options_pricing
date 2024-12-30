
## Project Overview
This project demonstrates the implementation of Fast Fourier Transform (FFT) techniques to efficiently price financial derivatives using three popular models:

- Black-Scholes Model
- Heston Stochastic Volatility Model
- Variance-Gamma Model

The approach leverages FFT's computational efficiency to quickly evaluate European-style option prices. It is designed for practitioners in quantitative finance, physics, or related fields who seek robust and adaptable methods for derivative valuation.

## Key Features
- Implements FFT-based option pricing for improved computational performance.
- Supports three major models:
    - Black-Scholes: Assumes constant volatility and log-normal asset price distribution.
    - Heston: Incorporates stochastic volatility with mean-reversion and volatility smiles.
    - Variance-Gamma: Captures skewness, kurtosis, and stochastic volatility for more realistic price movements.
- Includes tools for parameter sensitivity analysis.
- Facilitates comparison between numerical and analytical solutions.


## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/option-pricing-fourier-transform.git
    cd option-pricing-fourier-transform
    ```

2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

