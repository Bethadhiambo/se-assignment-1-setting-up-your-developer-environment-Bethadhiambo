[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15264896&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   Microsoft windows
   ![alt text](image.png)

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   ![alt text](image-1.png)
   To install Visual Studio Code, below are the steps:

Visit the Visual Studio Code download page at https://code.visualstudio.com/Download.
Choose the version appropriate for your operating system (Windows)
Download the installer file.
Once the download is complete, run the installer file and follow the on-screen instructions to install Visual Studio Code on your system.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

 Git is a distributed, open-source version control system. It enables developers and data scientists to track code, merge changes and revert to older versions. It allows you to sync changes with a remote server. Due to its flexibility and popularity, Git has become an industry standard as it supports almost all development environments, command-line tools, and operating systems.
Git stores your files and their development history in a local repository. Whenever you save changes you have made, Git creates a commit. A commit is a snapshot of current files. These commits are linked with each other, forming a development history graph. It allows us to revert back to the previous commit, compare changes, and view the progress of the development project. The commits are identified by a unique hash which is used to compare and revert the changes made. 

Benefits of git
•	Track changes: It allows developers to view historical changes. Development history makes it easy to identify and fix bugs.
•	IDE Integration: Due to its popularity, Git integration is available in all development environments, for example VSCode and JupyterLab.
•	Team collaboration: A developer team can view their progress, and by using branches, they can work individually on a task and merge changes with the main version. Pull requests, resolving merge conflicts, and code review promote team collaboration. 
•	Distributed VSC: In a distributed system, there is no centralized file storage. There are multiple backups for the same project. This approach allows developers to work offline and commit changes. 

The basic commands include initializing the Git repository, saving changes, checking logs, pushing the changes to the remote server, and merging. 
•	git init creates a Git repository in a local directory.
•	git clone <remote-repo-address>: copy the entire repository from a remote server to remote directory. You can also use it to copy local repositories.
•	git add <file.txt>: adds a single file or multiple files and folders to the staging area.
•	git commit –m “Message”: creates a snapshot of changes and save it in the repository. 
•	git config used to set user-specific configurations like email, username, and file format. 
•	git status shows the list of changed files or files that have yet to be staged and committed.  
•	git push <remote-name> <branch-name>: send local commits to remote branch of repository.  
•	git checkout -b <branch-name>: creates a new branch and switches to a new branch.
•	git remote –v: view all remote repositories.
•	git remote add <remote-name> <host-or-remoteURL>: add remote server to local repository. 
•	git branch –d <branch-name>: delete the branch.
•	git pull merge commits to a local directory from a remote repository. 
•	git merge <branch-name>: after resolving merge conflicts the command blends selected branch into the current branch.
•	git log show a detailed list of commits for the current branch.



4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

   These are the steps for the installation
1.Visit the official Python website at http://www.python.org.
2.Navigate to the Downloads section.
3.Choose the version of Python that you want to install (preferably the latest stable version).
4.Download the installer for your operating system (Windows, macOS, or Linux).
5.Run the installer and follow the on-screen instructions to install Python on your system.
6.Make sure to check the box that adds Python to your system's PATH during the installation process. This will 7.allow you to run Python from the command line.
8.Once Python is installed, you can verify the installation by opening a command prompt or terminal and typing python --version or python3 --version. This should display the version of Python installed on your system.

Additionally, one will also need a code editor or an Integrated Development Environment (IDE) to write and execute Python code. Some popular choices include Visual Studio Code which I have installed, PyCharm, and Jupyter Notebook.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

   To install pip, you can follow these general steps depending on the operating system:
Download get-pip.py script from https://bootstrap.pypa.io/get-pip.py
Open a command prompt and navigate to the directory where you saved get-pip.py.
Run the following command: python get-pip.py

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

   These are the steps for mysql installation
   Go to the MySQL Community Downloads page: https://dev.mysql.com/downloads/windows/installer/5.7.html

Scroll down to the "MySQL Installer" section and click on the "Download" button for the MySQL Installer for Windows.

On the next page, you will be asked to log in or sign up for a MySQL account. You can choose to skip the login by clicking on "No thanks, just start my download."

Once the download is complete, locate the downloaded installer file (typically named something like mysql-installer-web-community-5.7.x.x.msi) and double-click on it to start the installation process.

Follow the on-screen instructions provided by the MySQL Installer to configure and install MySQL database on your Windows machine. You can choose the desired setup type (typical, complete, custom) based on your requirements.

During the installation process, you will be prompted to choose various configuration options such as setting up the MySQL server, configuring server instances, and selecting the MySQL products to be installed. Follow the instructions accordingly.

Once the installation is complete, you can launch the MySQL Workbench or MySQL Command Line Client to start working with your MySQL database.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

   Here's a brief overview of how you can utilize Docker or virtual machines for your development projects:

Docker:

Docker is a popular containerization platform that allows you to package applications and their dependencies into standardized units called containers. These containers can then be run on any system that supports Docker, ensuring consistent behavior across different environments.
To get started with Docker, you'll need to install Docker Engine on your machine. You can create a Dockerfile that specifies the setup and configuration of your project, build a Docker image from it, and then run containers based on that image.
Docker Compose is a tool that simplifies the management of multi-container Docker applications. It allows you to define your application's services in a YAML file and then spin up the entire environment with a single command.

Virtual Machines:

Virtual machines (VMs) enable you to run multiple operating systems on a single physical machine. This is particularly useful if you need to test your applications on different OS environments or if you require a specific setup that differs from your host machine.
Popular virtualization platforms like VirtualBox, VMware, or Hyper-V allow you to create and manage virtual machines easily. You can install different operating systems and configure them as needed for your projects.
VM snapshots are a handy feature that lets you save the current state of a virtual machine and revert back to it at any point. This can be useful for testing or quickly rolling back changes.


8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

   For text editors and IDEs, there are several extensions, plugins, and add-ons available to enhance functionality. Here are some common ones,

Visual Studio Code:

ESLint: For JavaScript linting.
Prettier: For code formatting.
GitLens: For Git version control integration.
Bracket Pair Colorizer: For better bracket matching.
Path Intellisense: For autocompleting filenames.
Sublime Text:

Package Control: To easily manage and install plugins.
SublimeLinter: For code linting.
GitGutter: To see Git diffs in the gutter.
AutoFileName: For autocompleting filenames.
Atom:

Atom-Beautify: For code formatting.
Linter-eslint: For JavaScript linting.
Git-Plus: For Git integration.
File-Icons: For visually distinguishing file types.
Vim:

Vundle: A plugin manager for Vim.
YouCompleteMe: For code completion.
vim-gitgutter: For Git status in the gutter.
NERDTree: A file system explorer.


9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

    Developer Environment Setup Documentation
This document is a guide through the steps to set up a developer environment on a Windows system. Follow the instructions below to configure system for development tasks.

Step 1: Install Visual Studio Code
Download Visual Studio Code from the official website: https://code.visualstudio.com/
Run the installer and follow the on-screen instructions to complete the installation.
Once installed, open Visual Studio Code.

Step 2: Install Git
Download Git for Windows from the official website: https://git-scm.com/
Run the installer and follow the installation wizard instructions.
During installation, select the following options:
Use Git from the Windows Command Prompt
Use the OpenSSL library
Checkout Windows-style, commit Unix-style line endings
Complete the installation and open Git Bash to verify the installation by running git --version.

Step 3: Set Up Node.js and npm
Download Node.js from the official website: https://nodejs.org/
Run the installer and follow the installation instructions.
Open a command prompt and verify the Node.js and npm installation by running node -v and npm -v.

Step 4: Configure Environment Variables
Right-click on 'This PC' or 'My Computer' on your desktop and select 'Properties'.
Click on 'Advanced system settings' and then click on 'Environment Variables'.
Under 'System variables', click on 'New' and add the following variables if not already present:
Variable Name: NODE_PATH Variable Value: C:\Users\{YourUsername}\AppData\Roaming\npm\node_modules
Variable Name: PATH Variable Value: Append C:\Users\{YourUsername}\AppData\Roaming\npm to the existing values, separating with a semicolon.
Click 'OK' to save the changes.

Step 5: Install Required Extensions in Visual Studio Code
Open Visual Studio Code and go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window.
Search for and install the following extensions:
Bracket Pair Colorizer
ESLint
Prettier - Code formatter
Live Server
GitLens
Step 6: Configure Git in Visual Studio Code
Open Visual Studio Code and press Ctrl + Shift + P to open the Command Palette.
Type Git: Clone and enter the repository URL to clone a Git repository.
To commit changes, stage files, and push to a remote repository, use the Git icon in the Activity Bar in Visual Studio Code.
Troubleshooting
Node.js and npm Installation Issues
If Node.js/npm installation fails, check your system environment variables and try reinstalling Node.js using an LTS version.

Git Configuration Issues
If Git commands are not recognized, ensure that Git is correctly installed and the path is added to the system environment variables.

Visual Studio Code Extensions
If extensions fail to install or work properly, check your internet connection, Visual Studio Code version compatibility, and consider re-installing the problematic extension.

This documentation provides a basic setup for a developer environment on a Windows system. Customize the configurations based on your specific requirements and project needs

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
