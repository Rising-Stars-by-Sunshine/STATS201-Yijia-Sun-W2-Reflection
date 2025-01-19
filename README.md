# STATS201-Yijia-Sun-W2-Reflection

# Data Analysis Setup Guide

This guide provides the necessary steps to set up the environment for running the data analysis in the `load_and_exploratory_data_analysis.ipynb` Jupyter notebook file. It covers the setup for both **cloud** and **local** environments to ensure smooth execution of the analysis.

## Prerequisites

- **Python Version**: Python 3.11.11 or later
- **Required Libraries**:
  - `rasterio`: For reading `.tif` files.
  - `pandas`: For data manipulation.
  - `matplotlib`, `seaborn`: For data visualization.
  - `scikit-learn`: For machine learning models.

## 1. Setup for Cloud Environment (Google Colab)

1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the `load_and_exploratory_data_analysis.ipynb` file to Colab:
   - **Upload the notebook**: Click `File` > `Upload notebook` and select the file from your local machine.
   
3. **Install Required Libraries**:
   Run the following command in a Colab cell:
   ```python
   !pip install rasterio pandas matplotlib seaborn scikit-learn

## 2. Setup for Local Environment (Linux, macOS, or Windows)

### Local Environment Requirements
- **Operating System**: Linux, macOS, or Windows
- **Python Version**: 3.11.11 or later

### Steps for Local Setup
1. Install Python and Virtual Environment
   - Install Python 3.11.11 or later from [here](https://www.python.org/downloads/).
   - Create a virtual environment (optional):
     ```python
     python3 -m venv env
     source env/bin/activate  # macOS/Linux
     env\Scripts\activate  # Windows
2. Install Required Libraries:
   Install the required libraries by running the following:
   ```python
   pip install rasterio pandas matplotlib seaborn scikit-learn
3. Download the Dataset:
   Ensure the suit.tif file is stored locally and accessible in the correct path. For example:
    ```python
    /path/to/your/data/suit.tif
4. Run the Jupyter Notebook:
   - Install Jupyter Notebook (if not installed):
     ```python
     pip install notebook
   - Start Jupyter Notebook:
     ```python
     jupyter notebook
   - Open the load_and_exploratory_data_analysis.ipynb notebook and execute all cells.

