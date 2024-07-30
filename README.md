# Fintelligence Fusion

Fintelligence Fusion is a stock analysis tool that utilizes candlestick patterns to identify potential buy and sell signals. This tool uses various Python libraries to download stock data, analyze it, and plot the results. It also includes a backtesting strategy to evaluate the effectiveness of the identified signals.

## Features

- Download historical stock data
- Identify specific candlestick patterns (rejection patterns)
- Plot the stock data with identified signals
- Backtest the strategy using the identified signals
- Interactive Gradio interface for user input and output visualization

## Requirements

- Python 3.7 or higher
- See `requirements.txt` for the list of required Python packages

## Installation

1. Clone the repository:
    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the script:
    ```bash
    python support.py
    ```

2. Open the Gradio interface in your browser.

3. Enter the stock symbol you want to analyze in the provided input field and visualize the results.

## Files

- `support.py`: Main script containing the code for data downloading, analysis, plotting, and backtesting.
- `README.md`: This file.
- `requirements.txt`: List of required Python packages.
