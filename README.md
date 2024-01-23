# python learing
-----


# Project Setup Instructions

This README outlines the steps necessary to set up the Python environment for this project. 

## Prerequisites

- Ensure you have `brew` installed on your macOS. If not, you can install it from [here](https://brew.sh/).

## Python Environment Setup

1. **Install `pyenv` using `brew`:**
   ```bash
   brew install pyenv

2. **Set a Specific Python Version:**
   - To use a specific version of Python, run the following command:

   ```bash
    pyenv install 3.11.5
    pyenv shell 3.11.5

- This sets your shell to use the specified Python version.

3. Create a Virtual Environment:
   - Execute the following command to create a virtual environment named .python_learing (or any name you prefer):

   ```bash
   pyenv exec python -m venv .python_learing

4. Activate the Virtual Environment:

    - To activate the virtual environment, run the following command:
    
    ```bash
    source .python_learing/bin/activate

- To deactivate the virtual environment, simply type deactivate in the terminal.

# Dependency Management

1. Create a `requirements.txt` file in the root directory of the project.
- Include the following libraries that are essential for this project:
    ```bash
    jupyter
    numpy
    pandas
    Pyarrow
    matplotlib
    seaborn
    scikit-learn

2. Install the dependencies:
- After adding new libraries to requirements.txt, install them using:
    ```bash
    pip install -r requirements.txt

# Using Visual Studio Code

-If you are using Visual Studio Code, set up the Python interpreter to the virtual environment you created:

1. Open the Command Palette (⇧⌘P) and select the Python: Select Interpreter command:

2. Select the virtual environment you created in the previous section: .python_learing/bin/python


