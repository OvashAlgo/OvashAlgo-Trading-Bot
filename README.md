# OvashAlgo-Trading-Bot
Algorithmic Trading Bot using Python and MT4

Ovash Algo is an Algorithmic Trading project that combines Python-based signal generation that uses user input predictability with an MT4 Expert Advisor for automated trade execution.

## Overview

This project was built to explore how machine learning and rule-based trading logic can work together in a real workflow. The Python side handles data processing and signal generation, while the MT4 EA reads those signals and places trades.

## Features

- Python-based signal generation
- MT4 Expert Advisor integration
- Machine learning model support
- Automated workflow using signal files
- Expandable structure for GUI, analytics, and risk controls

## Project Structure

- `EA/` - MetaTrader 4 Expert Advisor files
- `python/` - training, prediction, and loop scripts
- `models/` - saved machine learning models
- `data/` - sample datasets
- `docs/` - setup and architecture notes
- `screenshots/` - images of the project interface or output

## How It Works

1. Market data is processed in Python
2. The prediction or signal logic generates a trading signal
3. The signal is saved to a file such as `signal.txt.`
4. The MT4 Expert Advisor reads the signal
5. The EA places or manages trades based on the strategy rules

## Technologies Used

- Python
- pandas
- NumPy
- scikit-learn
- MQL4
- MetaTrader 4

## Goals of the Project

- Build a complete trading workflow
- Connect Python and MetaTrader 4
- Experiment with model-based predictions
- Create a more polished trading product under the Ovash Algo name

## Future Improvements

- GUI for easier user interaction
- live analytics dashboard
- stronger risk management
- multi-model support
- cleaner deployment for customers

## What I Learned

This project helped me learn more about software architecture, machine learning workflows, algorithmic trading logic, and integrating multiple tools into a single system.

## Disclaimer

This project is for educational and experimental purposes. It is not financial advice.
