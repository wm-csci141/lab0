# Lab 0: Setup Your Programming Environment

This is your first lab and the goal is to help you setup the programming environment that you will use this semester. Note that everyone's computer is slightly different, so if the instruction does not work for you, please ask the TA for help. They will help you identify alternative solutions. 

There is no submission requirement for this lab and it will not be graded. Your first lab assignment will be given next week. 

### Objective:
By the end of this lab, students will be able to:
1. Install and verify Python 3.11 on their respective operating system (Mac, Linux, or Windows).
2. Install Visual Studio Code and its Python extension.
3. Write and execute a "Hello World!" program using three methods: command line, Python file in Visual Studio Code, and Jupyter Notebook.

### Prerequisites:
1. Internet connection.
2. Administrative rights on the computer for installation.

### Part 1: Installing and Verifying Python 3.11

#### 1. Mac:
1. It is very likely that you already have Python as part of your operating system. You can first try the last step and see if Python is installed or not. If not, we can install Python with the following steps. 
2. Visit the official Python website at https://www.python.org/downloads/
3. Find the download link for Python 3.11 and select the macOS installer.
4. Once downloaded, open the installer package and follow the on-screen instructions. Ensure that the “Add Python to PATH” option is checked.
5. After installation, open Terminal and type `python3 --version` to verify. You should see "Python 3.11.x".

#### 2. Linux:
1. Open the terminal.
2. Depending on your distribution, use one of the following commands:

   - For Debian-based distributions: 
     ```bash
     sudo apt update
     sudo apt install python3.11
     ```

   - For Red Hat-based distributions:
     ```bash
     sudo yum install python3.11
     ```

3. Once installed, verify the installation with: `python --version`.

#### 3. Windows:
1. Visit the official Python website at https://www.python.org/downloads/windows/
2. Find the download link for Python 3.11 and select the executable installer for Windows.
3. Run the installer, follow the on-screen instructions, and ensure to check the box that says “Add Python to PATH” during installation.
4. After installation, open Command Prompt and type `python3 --version` to verify. You should see "Python 3.11.x".

### Part 2: Installing Visual Studio Code and Python Extension

1. Visit the official Visual Studio Code website at https://code.visualstudio.com/ and download and install it for your respective operating system.
2. Once installed, open Visual Studio Code.
3. Navigate to the Extensions view by clicking on the square icon on the sidebar or pressing `Ctrl+Shift+X`.
4. Search for "Python" and install the Python extension provided by Microsoft.

### Part 3: "Hello World!" Program

#### 1. Command Line:
1. Open your terminal or command prompt.
2. Type `python3`.
3. You should be in the Python shell now. Type the following command and press enter:
   ```python
   print("Hello World!")
   ```

#### 2. Python File in Visual Studio Code:
1. Open Visual Studio Code.
2. Create a new file and save it as `hello.py`.
3. Type the following line in the file: `print("Hello World!")`
4. Save the file.
5. In the build-in terminal of Visual Studio Code, cd into the directory, and run the program with `python3 hello.py`.

#### 3. Jupyter Notebook:
1. If you haven't installed Jupyter, do it using pip:
   ```bash
   pip3 install jupyter
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Once Jupyter opens in your browser, create a new Python 3.11 notebook.
4. In the first cell, type: `print("Hello World!")` and press `Shift + Enter` to run.

### Conclusion:
Congratulations! You've successfully installed and verified Python 3.11, set up Visual Studio Code, and executed the iconic "Hello World!" program using three different methods. You're now well-prepared for your Python programming journey.
