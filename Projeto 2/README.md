# Portugal Wine Dataset Exploration

## Author

Rodrigo de Lima Florindo (Matrícula: 101809)

## Description

This project performs an exploratory analysis of Portugal's wines dataset.

**Python version:** 3.12.3

## Setup

Choose one of the following installation methods:

### (Recommended) Install Virtual Environment -- For Linux users

1. Ensure `venv` support is installed:

   ```bash
   sudo apt update
   sudo apt install python3-venv python3-full
   ```
2. Create a virtual environment:

   ```bash
   python3 -m venv .venv
   ```
3. Activate the environment:

   ```bash
   source .venv/bin/activate    # On Windows: .venv\Scripts\activate
   ```
4. Upgrade pip:

   ```bash
   pip install --upgrade pip
   ```
5. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### (Alternate) System-Wide Installation

6. Upgrade pip system-wide:

   ```bash
   pip install --upgrade pip
   ```
7. Install dependencies globally:

   ```bash
   pip install -r requirements.txt
   ```

### (Recommended) Install Virtual Environment -- For Windows users
1) (If needed) Install Python 3.x
winget install Python.Python.3.12   # or download from python.org

2) Create a virtual environment
python -m venv .venv

3) Activate it
.\.venv\Scripts\Activate.ps1
If activation is blocked, run once:
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned

4) Upgrade pip
python -m pip install --upgrade pip

5) Install dependencies
python -m pip install -r requirements.txt

## Running the Analysis

Continue with the following steps:

8. (If using venv) Activate the environment:

   ```bash
   source .venv/bin/activate
   ```
9. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
10. Open and run `exploratory_analysis.ipynb` to explore the dataset.
