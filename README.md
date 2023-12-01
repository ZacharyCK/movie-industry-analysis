# movie-industry-analysis

# Project Setup Instructions

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
