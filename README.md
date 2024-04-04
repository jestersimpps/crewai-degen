# Setting up Project in Current Folder Using Venv and Included Requirements File

## Overview

This project is set up within the current directory, allowing for easy management and organization. To set up the project environment,
we use a virtual environment (venv) to isolate our Python dependencies from those of other projects or system-wide packages. We also
include a `requirements.txt` file that lists all the necessary dependencies for our project.

## Prerequisites

1. A local development environment with Python installed
2. Git installed and available in your system's PATH
3. Optionally, a code editor of your choice (e.g., Visual Studio Code, PyCharm)

## Steps to Set Up the Project Environment

1. **Creating the Virtual Environment** - Open your terminal or command prompt and navigate to the project directory where you want to create the virtual environment. - Run the following command to create a new virtual environment named "myenv":
   `bash
python3 -m venv myenv
`
   This command will create a new directory called `myenv` in the current directory. Inside this directory, you'll find a separate
   Python interpreter and its site-packages directory.

2. **Activating the Virtual Environment** - After creating the virtual environment, activate it by running one of these commands (choose the appropriate one based on your
   operating system): - For Windows:
   `bash
  myenv\Scripts\activate
  ` - For macOS or Linux:
   `bash
  source myenv/bin/activate
  `
   Your terminal prompt should now display the name of your virtual environment, indicating that it is active.

3. **Installing Dependencies**

   - Within your activated virtual environment, you can install the necessary Python packages by running:
     ```bash
     pip install -r requirements.txt
     ```
     This command will install all the dependencies listed in the `requirements.txt` file within your virtual environment.

4. **Deactivating the Virtual Environment (Optional)**

   - Once you've finished working on your project and want to deactivate the virtual environment, simply run this command:
     ```bash
     deactivate
     ```

5. Once activated, you can run your main script by using the following command:
   ```bash
   python3 main.py
   ```
6. Your project should now start running. The specific output and behavior will depend on the purpose of your code.

## Additional Resources

- [Venv documentation](https://docs.python.org/3/library/venv.html)
- [Pip documentation](https://pip.pypa.io/en/stable/)

Now you have a local Python environment with a separate set of installed packages, which can help prevent conflicts between different
projects or packages. Feel free to modify the `requirements.txt` file as needed for your specific project requirements.
