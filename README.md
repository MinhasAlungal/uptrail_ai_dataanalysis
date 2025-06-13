
# Week 4 - Week 4 - AI-Powered Data Analysis & Automation

<b> Scenario </b>:
This project aims to apply AI-driven techniques for data cleaning, visualization, predictive modeling, and business strategy development. The dataset contains customer transactional and demographic information, including age, gender, income, spending habits, credit scores, marketing spend, and sales outcomes from a retail business. It covers the period from January 1, 2024, to April 29, 2024, capturing seasonal and behavioral insights during that timeframe.


## Set up your Environment

The added [requirements file](requirements.txt) contains all libraries and dependencies we need to execute the notebook.


### **`macOS`** type the following commands : 


- Install the virtual environment and the required packages by following commands:

    ```BASH
    pyenv local 3.11.3
    python3 -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
### **`WindowsOS`** type the following commands :

- Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    python -m pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-Bash` CLI :
    ```
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    python -m pip install --upgrade pip
    pip install -r requirements.txt
    ```

    **`Note:`**
    If you encounter an error when trying to run `pip install --upgrade pip`, try using the following command:

    ```Bash
    python.exe -m pip install --upgrade pip
    ```


## Data

The dataset for the notebook is stored in the `data` folder. 
