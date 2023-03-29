# freqtrade_analysis_notebook

A Jupyter Notebook to make backtesting, analysis and plotting of freqtrade strategies easier

## Prerequisites

You will need to install jupyter to run this notebook. Please follow any Jupyter installation instructions for your OS or environment.

You will also need extra dependencies for running the notebook. If using an existing freqtrade install (setup.sh script), activate the environment and:

`pip install tqdm quantstats`

This has not been tested in any docker environments, so YMMV.

## Installation

Copy both files into your base freqtrade folder, **not** the user_data/notebooks folder.

## Running

With your venv activated, start your jupyter server in the freqtrade folder, and open the ipynb file. Run the cells as normal.

If using an IDE like vscode, install the jupyter extension and open the freqtrade folder. Then open the ipynb file and run the cells as normal.
