[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15292843&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11 Answer :Step 1: Check System Requirements
Before downloading Windows 11, ensure your PC meets the minimum system requirements:
Processor: 1 gigahertz (GHz) or faster with 2 or more cores on a compatible 64-bit processor or System on a Chip (SoC).
RAM: 4 gigabytes (GB) or more.
Storage: 64 GB or larger storage device.
System Firmware: UEFI, Secure Boot capable.
TPM: Trusted Platform Module (TPM) version 2.0.
Step 2: Download Windows 11
Go to the Microsoft Windows 11 download page.
Click on the "Download now" button.
Step 3: Create a Bootable USB Drive (Optional)
If you want to perform a clean installation or upgrade from a USB drive:
Download the Media Creation Tool from the same Microsoft page.
Run the tool and follow the on-screen instructions to create a bootable USB drive.
Step 4: Install Windows 11
Insert the bootable USB drive into your PC.
Restart your PC.
Press the key (like F12, ESC, etc.) to access the boot menu (this varies by manufacturer).
Select the USB drive as the boot device.
Follow the prompts to install Windows 11.
Step 5: Set Up Windows 11
Once Windows 11 is installed, you’ll need to go through the initial setup:
Choose your region and language preferences.
Connect to a network (if required).
Sign in with your Microsoft account or create a local account.
Complete the setup process.
Step 6: Install Drivers and Updates
After installation, make sure to:
Install necessary drivers for your hardware (graphics card, network adapter, etc.).
Check for and install Windows updates to ensure your system is up-to-date and secure.

3. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download ANSWER:Step-by-Step Guide to Install Visual Studio Code
Download Visual Studio Code:
Go to the Visual Studio Code download page.
Depending on your operating system (Windows, macOS, or Linux), click on the respective download button.
Install Visual Studio Code:
Windows:
Once the download is complete, run the installer (.exe file).
Follow the prompts in the installer (you can leave most settings as default).
VS Code will be installed in your Program Files directory by default.
Optionally, you can add VS Code to your PATH environment variable during installation

5. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com ANSWER: Setting Up Git
Download and Install Git:

Go to the Git download page.
Download the installer suitable for your operating system (Windows, macOS, Linux).
Run the installer and follow the prompts to complete the installation. During installation, you can leave most settings as default unless you have specific preferences.
Configure Git:

Open a terminal (Command Prompt on Windows, Terminal on macOS/Linux).
Set your name and email address, which will be used for your Git commits:
arduino
Copy code
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Optionally, you can configure other settings such as your preferred text editor:
css
Copy code
git config --global core.editor "code --wait"  // Use VS Code as the editor
Creating a GitHub Account
Create a GitHub Account:
Go to GitHub and sign up for a new account if you don’t already have one.
Follow the instructions to verify your email address and set up your profile.
Initializing a Git Repository
Initialize a Git Repository:
Navigate to the root directory of your project in the terminal.
Initialize a new Git repository:
csharp
Copy code
git init
Making Your First Commit
Add and Commit Your Files:
Create or add your project files into the Git repository directory.
Stage your files for commit (replace <filename> with actual file names or use . to stage all files):
csharp
Copy code
git add <filename>
Commit your changes with a commit message:
sql
Copy code
git commit -m "Initial commit"
Connecting Git Repository to GitHub
Create a Repository on GitHub:
Log in to your GitHub account.
Click on the "+" sign in the top right corner and select "New repository".
Give your repository a name and optionally add a description. Keep it public or private as per your preference.
Click on "Create repository".
Link Local Repository to GitHub:

Follow the instructions on the GitHub repository page to add the remote repository as origin:
csharp
Copy code
git remote add origin https://github.com/your-username/repository-name.git
Push your local commits to GitHub (replace main with master if you're using an older Git version):
css
Copy code
git push -u origin main
Enter your GitHub credentials if prompted.

6. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
Download Python:

Go to the official Python website.
Download the latest version of Python by clicking on the "Download Python X.X.X" button. As of now, Python 3.x is the recommended version.
Choose the installer suitable for your operating system (Windows, macOS, Linux).
Install Python:

Windows:

Run the downloaded installer (.exe file).
Make sure to check the option "Add Python X.X to PATH" during installation.
Click "Install Now" and follow the prompts to complete the installation.

7. Install Package Managers:
   If applicable, install package managers like pip (Python).
   Installing pip (Python Package Manager)
Check Python Installation:

Before installing pip, ensure Python is installed on your system. You can verify this by running:
css
Copy code
python --version
or
css
Copy code
python3 --version
Install pip (if not already installed):

pip usually comes pre-installed with Python distributions from Python 3.4 onwards. However, it's a good practice to ensure it's up-to-date. Here’s how to install pip:

Windows:

Python installer usually adds pip to the system PATH during installation. To upgrade pip to the latest version, open Command Prompt and run:
css
Copy code
python -m pip install --upgrade pip

9. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
   Installing MySQL Database Server on Windows
Download MySQL Installer:

Go to the MySQL Community Downloads page.
Scroll down to find the MySQL Installer for Windows.
Click on the "Download" button for the MySQL Installer appropriate for your system (typically the web community installer is recommended).
Run the MySQL Installer:

Once the installer is downloaded, run the .exe file to start the installation process.
MySQL Installer Setup:

Choosing Setup Type: Select "Developer Default" setup type for a typical installation including MySQL Server, MySQL Workbench (GUI tool), connectors, and documentation.
Product Selection: Make sure "MySQL Server" is selected. Optionally, select other components like MySQL Workbench for GUI management.
Installation Process: Follow the prompts and accept the license agreement.
Configuration: During the installation, you may be prompted to configure MySQL Server. Choose a strong root password for MySQL Administrator.
Complete the Installation:

Allow the installer to complete the installation process. It will install MySQL Server and other selected components.
Start MySQL Server:

After installation, MySQL Server should start automatically as a Windows service. If not, you can manually start it:
Open the Services Manager (services.msc) from the Start menu.
Look for "MySQL" in the list of services, right-click, and select "Start".
Verify MySQL Installation:

Open MySQL Workbench (if installed) or use the MySQL command-line client to connect to MySQL Server:
css
Copy code
mysql -u root -p
Enter the root password you set during installation.
Create a Database and User (optional):

Once connected, you can create databases and manage users using SQL commands. For example:
sql
Copy code
CREATE DATABASE mydatabase;
CREATE USER 'myuser'@'localhost' IDENTIFIED BY 'mypassword';
GRANT ALL PRIVILEGES ON mydatabase.* TO 'myuser'@'localhost';

11. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.Docker
Install Docker:

Docker provides a unified platform for developers and IT admins to build, ship, and run distributed applications. Here’s how you can install Docker:

Go to the Docker Desktop download page.
Download and run the installer suitable for your operating system (Windows/macOS).
Follow the prompts to complete the installation. Docker Desktop includes Docker Engine, Docker CLI client, Docker Compose, Docker Content Trust, Kubernetes, and Credential Helper.
Verify Docker Installation:

After installation, Docker should be running as a service. You can verify it by checking the Docker icon in the system tray (Windows) or menu bar (macOS).
Pulling Docker Images:

Docker images are the basis of containers. You can pull images from Docker Hub (public repository) or private repositories to create containers. For example, to pull a MySQL container:
Copy code
docker pull mysql:latest
Running Containers:

You can run containers based on pulled images:
perl
Copy code
docker run --name my-mysql -e MYSQL_ROOT_PASSWORD=my-secret-pw -d mysql:latest
This command starts a MySQL container named my-mysql with a specified root password (my-secret-pw).
Managing Containers:

Use commands like docker ps to list running containers, docker exec to execute commands inside containers, and docker stop to stop containers.
Virtual Machines (Optional)
Install Virtualization Software:

For virtual machines, you’ll need virtualization software like VMware Workstation, VirtualBox, or Hyper-V (Windows feature).
Create a Virtual Machine:

Using the installed virtualization software, create a new virtual machine. You can typically specify the operating system and configure hardware resources like CPU, RAM, and storage.
Install Operating System:

Install the desired operating system (e.g., Ubuntu, CentOS) on the virtual machine as you would on a physical machine.
Set Up Development Environment:

Install necessary software and tools within the virtual machine environment. You can mimic production or specific development environments here.

12. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.Visual Studio Code (VS Code)
VS Code has a rich ecosystem of extensions available through the Visual Studio Code Marketplace. Here are some essential extensions to consider:

Python:

Python: Provides support for syntax highlighting, IntelliSense, code formatting, linting (using tools like pylint or flake8), debugging, and more.
Version Control:

GitLens: Enhances Git integration with features like current line blame information, commit details, and more.
GitHub Pull Requests and Issues: Allows you to review and manage GitHub pull requests directly within VS Code.
General Productivity:

Live Share: Collaborative editing and debugging in real-time.
Bracket Pair Colorizer: Colorizes matching brackets to help distinguish nested code blocks.
Code Spell Checker: Provides basic spell checking for your source code.
Language Support:

ESLint: Integrates ESLint for JavaScript and TypeScript projects, helping enforce coding styles and catching errors.
JetBrains IDEs (e.g., IntelliJ IDEA, PyCharm)
JetBrains IDEs provide comprehensive support for various programming languages with plugins tailored for specific needs:

Python (PyCharm):

Built-in support for Python development, including syntax highlighting, code completion, debugging, and testing.
Version Control:

Integrated Git support with features like history view, commit management, and branch operations.
Database Tools:

Database tools and SQL support for managing databases directly within the IDE.
Sublime Text
Sublime Text supports a wide range of plugins that enhance its functionality:

Package Control: Manage and install plugins directly from within Sublime Text.

Syntax Highlighting and Linting: Plugins like SublimeLinter provide real-time linting for various programming languages.

Git Integration: Plugins for Git integration, though not as extensive as VS Code or JetBrains IDEs, are available for basic version control operations.

Atom
Atom is known for its flexibility with a wide array of plugins:

Language Support: Extensions for syntax highlighting, code completion, and linting across many programming languages.

Git and GitHub Integration: Plugins like GitHub package for managing pull requests, issues, and more directly within Atom.

Eclipse
Eclipse plugins are typically focused on Java development but extend to other languages and tools through the Eclipse Marketplace:

Java Development Tools: Built-in support for Java with plugins available for additional features like Maven, Gradle, and more.

Version Control: Plugins for Git and SVN integration.

Choosing Extensions and Plugins
When selecting extensions and plugins, consider your specific project needs, programming languages, and workflow preferences. Always check reviews, ratings, and compatibility with your IDE or text editor version before installing. Experiment with different extensions to find the ones that best suit your development style and productivity goals.

By exploring and leveraging extensions and plugins, you can significantly enhance your development environment’s capabilities, streamline workflows, and improve code quality across your projects.


14. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

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
