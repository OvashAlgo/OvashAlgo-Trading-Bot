<h1>OvashAlgo-Trading-Bot</h1>

Algorithmic Trading Bot using Python and MT4

Ovash Algo is an algorithmic trading project that brings together Python-based signal generation, which uses user input predictability, and an MT4 Expert Advisor for automated trade execution.

<h2>Overview</h2>

This project was built to explore how machine learning and rule-based trading logic can work together in a real workflow. The Python side handles data processing and signal generation, while the MT4 EA reads those signals and places trades.

<h2>Features</h2>

* Python-based signal generation
* MT4 Expert Advisor integration
* Machine learning model support
* Automated workflow using signal files
* Expandable structure for GUI, analytics, and risk controls

<h2>Project Structure</h2>

* EA/ - MetaTrader 4 Expert Advisor files
* python/ - training, prediction, and loop scripts
* models/ - saved machine learning models
* data/ - sample datasets
* docs/ - setup and architecture notes
* screenshots/ - images of the project interface or output

<h2>How It Works</h2>

1. Market data is processed in Python.
2. The prediction or signal logic generates a trading signal.
3. The signal is saved to a file such as signal.txt.
4. The MT4 Expert Advisor reads the signal.
5. The EA places or manages trades based on the strategy rules.

<h2>Technologies Used</h2>

* Python
* pandas
* NumPy
* scikit-learn
* MQL4
* MetaTrader 4

<h2>Goals of the Project</h2>

* Build a complete trading workflow.
* Connect Python and MetaTrader 4
* Experiment with model-based predictions
* Create a more polished trading product under the Ovash Algo name.

<h2>Future Improvements</h2>

* GUI for easier user interaction
* live analytics dashboard
* stronger risk management
* multi-model support
* cleaner deployment for customers

<h2>What I Learned</h2>

Through this project, I deepened my understanding of designing robust software architecture for trading systems, implementing machine learning models in a production environment, developing algorithmic trading logic, and integrating Python scripts with MetaTrader 4. I also improved my skills in data pipeline construction, interface design, and cross-platform communication between trading technologies.
