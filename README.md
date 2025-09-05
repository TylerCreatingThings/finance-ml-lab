# Finance ML Lab

A clean Python environment for financial machine learning research and analysis.

## Setup Instructions

### Prerequisites
- Python 3.11 or higher
- pip (Python package installer)

### Installation

1. **Create a virtual environment (recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scriptsctivate
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

## Included Libraries

- **Data Science:** numpy, pandas, matplotlib, scikit-learn, statsmodels
- **Financial Data:** yfinance
- **Deep Learning:** torch
- **Visualization:** seaborn, plotly
- **Scientific Computing:** scipy
- **Development:** jupyter, notebook

## Project Structure

```
finance-ml-lab/
├── datasets/          # Store your datasets here
├── notes/            # Research notes and documentation
├── projects/         # Individual ML projects
├── requirements.txt  # Python dependencies
└── README.md        # This file
```

## Getting Started

1. Navigate to the `projects/` directory
2. Create a new Jupyter notebook for your analysis
3. Import the libraries you need and start exploring!

## Example Usage

```python
import yfinance as yf
import pandas as pd
import matplotlib.pyplot as plt

# Download stock data
data = yf.download('AAPL', start='2020-01-01', end='2023-01-01')
print(data.head())
```
