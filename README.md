[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15256492&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

**Answer**
My laptop says "the processor isn't supported for this version of Windows. It doesn't want to install windows 11.
<img src="images/Windows screenshot.png">

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

**Answer**
Already had installed VS code during class.
<img src="images/VS code screenshot.png">

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
**Answer**
Already had installed both git and github
<img src="images/git screenshot.png">
<img src="images/github screenshot.png">

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
**Answer**
Step 1:Go to the python website.
Step 2:Click on "download python", and click the latest version.
Step 3:Locate the downloaded file and click it.
Step 4:Click the check box that says "add python" to "path" at the bottom of the installer window.
Step 5:Wait for the installation to complete.
Step 6:Verify the installation by opening Gitbash and typing "python --version".

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
   **Answer**
   Pip is the package installer for Python.
   Step 1:Go the website and type PIP(get-pip.py)
   Step 2:Install PIP and run the python command "python get-pip.py"
   Step 3:Verify the installation by add  it to the "path" variable.
   Step 4:To test whether it was successful, type the command "python -m pip help".
   Step 5:Add it the PATH.
   Go to the "edit the system enviroment"
   Click the "Evironment Varibles"
   Double tap on the PATH varible to edit it
   Select new and add the directory where PIP is installed
   Click "OK" to save the changes
   Step 6:Configure by using the command "pip config -v list"


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
   **Answer**
Step 1:Go to the browser and type "dev.mysql.com/downloads/installer/" and install it.
Step 2:Locate the downloaded file and double-click to run the installer.
Step 3:Choose setup type: "Developer Default" which installs MySQLServer,Workbench and other tools.
Step 4:Click next the execute to download.
Step 5:Configure the MySQL Server.
Select port number (3306 is default)
Step 6:Set a root password and you can also create user accounts.
Step 7:Start the server after installation.
Step 8:Finish the config and close the installer.
Step 9:Verify installation by typing the command on gitbash "mysql -u root -p"

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
   **Answer**
   1.VSCode- Installed Dart and Python.
   2.Installed ESLint and PyLint.
   3.Installed Prettier,Beautify and Python Formatter.
   3.Installed Git Pull Requests and Issues.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
    **Answer**
    Step 1: Installed VSCode and configured by installing extensions.
    Step 2: Installed Git and used the following commands .
    (git config --global user.name "Thando Kheswa")(git config --global user.email"kheswathando22@gmail.com").
    Step 3: Installed Python and verified the version using ("python --version") and its extensions.
    Step 4: Installed MySQL and verified using the command (""mysql -u root -p"").
    Step 5:Installed Dart and verified using ("dart --version").
    Step 6:Installed Flutter, extracted the zip, updated the path and used the command ("flutter doctor")

**GitHub Link**
https://github.com/ThandoK03/Development-.git

**Challenges**
I did not experience any because mostly was done in class. Only had a problem with installing windows

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
