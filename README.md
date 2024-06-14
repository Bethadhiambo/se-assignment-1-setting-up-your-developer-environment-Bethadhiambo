![screenshot for windows download](https://github.com/Powerlearnproject/se-assignment-1-setting-up-your-developer-environment-Bethadhiambo/assets/171561999/98d3085f-d888-44eb-bb70-67e8a81698a2)![screenshot for windows download](https://github.com/Powerlearnproject/se-assignment-1-setting-up-your-developer-environment-Bethadhiambo/assets/171561999/4bc93d67-ef8c-4c53-bb76-1eae3e63db14)[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
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
![image](https://github.com/Powerlearnproject/se-assignment-1-setting-up-your-developer-environment-Bethadhiambo/assets/171561999/f53b00e0-eb8e-4188-aeaa-216a9bd65868)



3. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   ![image](https://github.com/Powerlearnproject/se-assignment-1-setting-up-your-developer-environment-Bethadhiambo/assets/171561999/f7cdb23b-7de2-47d4-9305-ecf89db86704)

   These are the steps for the download
   Click on the "Download for Windows" button if you are using a Windows computer. If you are using a Mac, click on the "Download for macOS" button.
Once the download is complete, open the downloaded file to start the installation process.
Follow the on-screen instructions to complete the installation. You may need to select your desired installation location and agree to the terms of service.
Once the installation is complete, you can open Visual Studio Code from your desktop or start menu.
You can now start using Visual Studio Code to write and edit your code for various programming languages.
Customize your settings, install extensions, and explore the features of Visual Studio Code to enhance your coding experience

5. Set Up Version Control System:
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


7. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
![image](https://github.com/Powerlearnproject/se-assignment-1-setting-up-your-developer-environment-Bethadhiambo/assets/171561999/b29016c0-6d9d-453c-a4df-6acd763ee00c)

These are the steps for python installation,
Go to the official Python website: https://www.python.org
Navigate to the Downloads section.
Choose the version of Python that you want to install. As of now, Python 3.12 is the recommended version.
Download the installer appropriate for your operating system (Windows, macOS, or Linux).
Run the installer and follow the installation instructions.
Make sure to check the box that says "Add Python to PATH" during the installation process. This will allow you to run Python from the command line.
Once the installation is complete, you can verify the installation by opening a command prompt or terminal and typing python --version or python3 --version.


9. Install Package Managers:
   If applicable, install package managers like pip (Python).
   To install pip, the following command is applicable,
   Download the get-pip.py script by running the following command in Command Prompt:
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
Install pip by running the get-pip.py script:
python get-pip.py

11. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
![image](https://github.com/Powerlearnproject/se-assignment-1-setting-up-your-developer-environment-Bethadhiambo/assets/171561999/f03a40f5-8537-4726-a44e-96dab7332382)
After the download

Run the installer and follow the on-screen instructions to install MySQL on your computer.

During the installation process, you will be prompted to set a root password for the MySQL server. Make sure to set a strong password and remember it as you will need it to access the database.

After the installation is complete, open the MySQL Command Line Client or MySQL Workbench to access the MySQL database.

Use the root username and the password you set during installation to log in to the MySQL server.

You can now start creating databases, tables, and managing data in MySQL.

13. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

 Here are some steps to set up development environments using virtualization:

Install Docker or a virtual machine software on your machine.
Create a new virtual environment for each project or application you are working on. This will allow you to isolate project dependencies and avoid conflicts with other projects.
Install the necessary dependencies and tools within the virtual environment. This could include things like programming languages, libraries, and databases.
Use version control tools like Git to manage your code and dependencies within the virtual environment.
Share the virtual environment configuration with other team members using Dockerfiles or virtual machine snapshots to ensure consistent setups across different machines.
Test the virtual environment to ensure that it works as expected and make any necessary adjustments.
Use the virtual environment for development, testing, and debugging of your project.

15. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

Visual Studio Code (VS Code):

ESLint: Provides real-time linting for your code to catch errors and improve code quality.
Bracket Pair Colorizer: Colors matching brackets in your code for easier navigation.
GitLens: Supercharges the Git capabilities built into VS Code to provide valuable insights and integration with version control.
Prettier: Code formatter that automatically formats your code to follow consistent styling rules.
Live Server: Launches a local development server with live reload capability for quick preview of web pages.
Sublime Text:

Package Control: Package manager for Sublime Text to easily install, manage, and discover plugins.
Sublime Linter: Inline linting functionality for various languages to spot errors and maintain code quality.
Emmet: Toolkit for web developers that greatly improves HTML and CSS workflow.
GitSavvy: Git integration within Sublime Text to perform version control operations.
Atom:

Atom-Beautify: Beautifies code in Atom by automatically formatting it.
PlatformIO IDE Terminal: Integrated terminal for Atom for executing commands directly within the editor.
linter-ui-default: Unified user interface for displaying linter messages in Atom.
Autocomplete+ Snippets: Enhanced autocomplete functionality with snippet support.
Eclipse:

Eclipse Code Recommenders: Provides intelligent code completion and recommendations based on context.
Eclim: Brings Eclipse functionality to Vim for those who prefer working within a Vim environment.
EGit: Powerful Git integration within Eclipse for version control.
FindBugs: Static code analysis tool for finding bugs in Java code.

17. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process.
    Setting Up Developer Environment

Operating System: I am using Windows 10 as my primary operating system for development.
Integrated Development Environment (IDE): I have installed Visual Studio Code for coding and debugging purposes.
Version Control: I am using Git with GitHub for version control and collaboration.
Programming Languages: I have installed Python 3.12.
Package Manager: I am using npm for managing packages and dependencies.
Database: I have set up MySQL for database development.
API Testing: I am using Postman for testing APIs.
Browser: I primarily use Google Chrome for testing web applications.
Plugins and Extensions: I have installed several extensions in Visual Studio Code to enhance productivity, such as ESLint, Prettier, GitLens, and Live Server.
Customizations: I have customized my Visual Studio Code settings to match my preferences, including keybindings, theme, and font size.
Troubleshooting:
I encountered issues with installing Python packages using pip. I had to set up a virtual environment and ensure that my PATH variable was correctly configured.
I faced challenges setting up MySQL on Windows. I had to troubleshoot permissions and configuration settings to get it working properly.
I encountered compatibility issues with certain npm packages. I had to update Node.js and npm to the latest versions to resolve these issues.
Additional Tools: I have installed additional tools such as Docker for containerization, Postgresql for database management, and VS Code extensions like Docker, GitGraph, and Bracket Pair Colorizer.
Project Setup: I have set up a folder structure for my projects, including separate directories for backend, frontend, and shared resources.
Security: I have implemented security best practices in my development environment, such as using strong passwords, enabling two-factor authentication, and keeping software up to date.


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
