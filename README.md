[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15275725&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
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


ANSWERS:


I have managed to set up an Development Enviroment follow the next steps'

PYTHON:

1. I visited the official Python website at https://www.python.org

2. Click on the "Download Python" button to download the latest version of Python for Windows.

3. Once the download was complete,I locateed the downloaded installer a .exe file.

4. I double-clicked on the installer to run it.

5. I checked the box that says "Add Python to PATH" during the installation process.

6. I clicked "Install Now" to start the installation.

7. Verify Installation:

I opened a Command Prompt window.

Typed python --version and press Enter.

And I saw the information that said I successfully installed python

I installed the virtualenv package by running:

python -m pip install virtualenv

I created a new virtual environment by running:

python pip virtualenv myenv

I activated the virtual environment by running:

source myenv\Scripts\activate

VISUAL STUDIO CODE
Installing Visual Studio Code (VS Code) on a Windows 64-bit system involves the following steps:

1. Download the Installer:
   I opened the [Visual Studio Code website](https://code.visualstudio.com/).
   I clicked on the "Download for Windows" button to download the 64-bit installer.

2. To run the Installer:
   - Once the download was complete, I open the downloaded .exe file to start the installation process.

3.Accept the License Agreement:
-In the installer window, I read the license agreement and clicked on the checkbox to accept the terms. Then, clicked "Next".

4. Choose the Installation Location:

   - I selected the destination folder where I wanted to install VS Code, and clicked next,

5. Select Additional Tasks:

   - I chose additional options like creating a desktop icon, adding to PATH, and registering the code as an editor for supported file types. I selected "Add to PATH" to enable easy access from the command line. Clicked "Next".

6. Install:

   - I clicked the "Install" button to begin the installation.

7. Launch Visual Studio Code:
   - Once the installation was complete, I launched launch VS Code by checking the "Launch Visual Studio Code" option and then clicked "Finish".

DART:
To install Dart on a Windows 64-bit PC, I followed these steps:

1. - I visited the Dart SDK download page at https://dart.dev/get-dart.
   - Clicked on the Windows 64-bit option to download the Dart SDK for Windows 64-bit.

2. Install Dart SDK:

   - Once the download was complete,I located the downloaded file (it was a ZIP file).
   - I extracted the contents of the ZIP file to a location on your computer(C:Windows).

3. Set up Environment Variables:

   - I added the Dart SDK 'bin' directory to my system's PATH environment variable:
     - By right-click on "This PC" or "Computer" on my desktop.
     - I clicked on "Properties" and then click on "Advanced system settings".
     - In the System Properties window,I click on the "Environment Variables" button.
     - In the "System Variables" section,I selected the "Path" variable and click "Edit".
       -I clicked "New" and add the path to the bin directory of the Dart SDK ('C:\dart\dart-sdk\bin').
     - I clicked "OK" on all windows to save the changes.

4. Verify Installation:
   -I opened a new Command Prompt window.
   - Typed 'dart --version' and press Enter.
   - I saw the Dart version

FLUTTER:
To install Flutter on my Windows 64-bit PC:

1. I downloaded Flutter SDK for Windows from the page flutter.dev.
2. Extract the downloaded ZIP file to a folder like C:\flutter.
3. I added the Flutter bin directory to the system's PATH environment variable.
4. I ran flutter doctor in Command Prompt to install dependencies.
5. I verified the installation by running flutter --version.
![assignment 2024-06-18 132537](https://github.com/Tarirohope/se-assignment-1-setting-up-your-developer-environment-Tarirohope/assets/118693318/b5cf9151-49e8-4b94-927f-51cf4ad59073)
