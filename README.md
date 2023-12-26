# movie-industry-analysis

### Purpose of this Project

This purpose of this project is to see what movie stars, directors and genres have been successful in the past 5 years (2018 - 2022).  This project can help predict who may be successful in the film industry in the near future and what genres people like seeing in movies.  

### Tools Used in this Project

The tools in this project include:

- Python
- Pandas
- CSV Files
- SQLite 
- Jupyter Notebook
- Matplotlib

This project makes use of the Python programming language and used a Python Virtual Environment.  It uses the Pandas library by inserting the data from csv files into DataFrames.  A SQLite database is created using Python and the data from the DataFrames were inserted into the corresponding tables.  This project also uses SQL Views to create complex queries from the data.  This project used Matplotlib plots to visualize the results of the SQL queries.  

# Project Setup Instructions

## Cloning the Repository

Follow these steps to clone the repository to your local machine.

## Prerequisites

- Ensure you have Git installed on your computer. If you do not have Git installed, you can download it from [Git's official site](https://git-scm.com/downloads).

## Cloning the Repository

1. Open your terminal or command prompt.

2. Navigate to the directory where you want to clone the repository.

3. Run the following command:

   ```bash
   git clone https://github.com/ZacharyCK/movie-industry-analysis
   ```

4. Once the cloning process is complete, navigate to the cloned repository's directory:

   ```bash
   cd movie-industry-analysis
   ```

## Setting Up a Python Virtual Environment

Creating a virtual environment is a best practice for Python development. It allows you to manage project dependencies separately from your global Python installation. Here's how to set it up:

### Prerequisites

- Ensure you have Python installed on your system. You can download it from [python.org](https://www.python.org/downloads/).
- Check your Python version by running `python --version` or `python3 --version` in your terminal.

### Creating the Virtual Environment

1. **Navigate to the Project Directory**:

   Open your terminal and navigate to the root of your project directory.

   ```sh
   cd path/to/your/project

2. **Create Virtual Environment**:

    - For Windows
    ```
    python -m venv venv
    ```

    - For macOS/Linux:
    ```
    python3 -m venv venv
    ```
    This command creates a directory named venv in your project folder, containing the virtual environment.

3. **Activate Virtual Environment**:

    - For Windows
    ```
    .\venv\Scripts\activate
    ```

    - For macOS/Linux:
    ```
    source venv/bin/activate
    ```
    Once activated, your terminal prompt will be prefixed with (venv).

### Installing Dependencies

With the virtual environment active, you can install project dependencies.

1. **Ensure pip is Up-to-Date:**:
    ```
    pip install --upgrade pip
    ```
2. **Install Dependencies from requirements.txt:**
Make sure you have a requirements.txt file in your project directory. Run the following command to install the listed dependencies:
    ```
    pip install -r requirements.txt
    ```

### Deactivating the Virtual Environment
When you're done working in the virtual environment, you can deactivate it by running:
```
deactivate
```
This command will return you to your global Python environment.

## Starting a Jupyter Notebook Server and Running the Files

1. **Start the Notebook**

    To use Jupyter Notebook files (.ipynb) you need to start a Jupyter Notebook server
    You start the server by running this command in the terminal
    ```
    jupyter notebook
    ```
2. **Run Files that Process Data**

    You should now be able to run the files with the server created.
    Go to each file listed, in no particular order, and hit 'Run All'
      - imdb_data_processing.ipynb
      - bo_data_processing.ipynb
      - reviews_data_processing.ipynb
    
    Each could take up to 30 seconds to run all the way through
    This will process all the datasets and insert them into the SQLite database.

4. **Run Joining Data File**

    Run the finalize_data.ipynb file and observe the results of the data queries in visualizations.

# Forking the Repository

This guide will help you fork the repository, allowing you to make your own changes and propose improvements.

## Step-by-Step Guide

1. **Navigate to the Repository:**  
   Go to the GitHub page of this repository.

2. **Fork the Repository:**  
   Click on the "Fork" button at the top right corner of the page. This creates a copy of the repository in your GitHub account.

3. **Clone Your Fork:**  
   - On your fork's GitHub page, click the "Clone or download" button and copy the URL.
   - Open your terminal (or Git Bash if you are on Windows).
   - Use the command `git clone https://github.com/ZacharyCK/movie-industry-analysis`. This will download your fork to your local machine.

4. **Create a New Branch:**  
   - Navigate to the cloned directory (if you are not already there).
   - Use `git checkout -b [branch-name]` to create and switch to a new branch, replacing `[branch-name]` with a name relevant to the changes you plan to make.

5. **Make Your Changes:**  
   Open the project in your preferred editor, make your changes, and save them.

6. **Commit and Push Your Changes:**  
   - Stage your changes with `git add .`.
   - Commit your changes with `git commit -m "Your commit message"`.
   - Push the changes to your fork with `git push origin [branch-name]`.

7. **Create a Pull Request:**  
   - Go back to this repository on GitHub.
   - Click on "Pull requests" and then the "New pull request" button.
   - Select your fork and branch, then click on "Create pull request".
   - Add a title and description to your pull request, then submit it.

Congratulations, you have successfully forked and made a change to a repository!

## Need Help?

If you encounter any issues or have questions, feel free to open an issue in the repository or contact the repository maintainers.

