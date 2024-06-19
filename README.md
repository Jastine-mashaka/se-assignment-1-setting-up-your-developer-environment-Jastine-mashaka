[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15285890&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   To install Windows 11, follow these steps:

### i. Check System Requirements
Ensure your PC meets the minimum system requirements for Windows 11:
- Processor: 1 GHz or faster with at least 2 cores on a compatible 64-bit processor or System on a Chip (SoC).
- RAM: 4 GB or more.
- Storage: 64 GB or larger.
- System firmware: UEFI, Secure Boot capable.
- TPM: Trusted Platform Module (TPM) version 2.0.
- Graphics card: DirectX 12 compatible graphics / WDDM 2.x.
- Display: >9” with HD Resolution (720p).
- Internet connection: Internet connectivity is necessary to perform updates and to download and take advantage of some features.

### ii. Backup Your Data
Backup important files to an external drive or cloud storage to prevent data loss during installation.

### iii. Obtain Windows 11
You can get Windows 11 from the official Microsoft website or through the Windows 11 Installation Assistant.

#### Using Windows 11 Installation Assistant
i. **Download the Installation Assistant:**
   - Visit the [Windows 11 download page](https://www.microsoft.com/software-download/windows11).
   - Click on "Download Now" under the "Windows 11 Installation Assistant" section.
ii. **Run the Installation Assistant:**
   - Open the downloaded file and follow the on-screen instructions to upgrade your PC to Windows 11.

#### Using Installation Media (ISO)
i. **Download the Media Creation Tool:**
   - Visit the [Windows 11 download page](https://www.microsoft.com/software-download/windows11).
   - Click on "Download Now" under the "Create Windows 11 Installation Media" section.
ii. **Create Installation Media:**
   - Run the Media Creation Tool.
   - Choose "Create installation media (USB flash drive, DVD, or ISO file) for another PC."
   - Follow the prompts to create a bootable USB drive or save an ISO file.
iii. **Install from USB or DVD:**
   - Insert the USB drive or DVD into the PC where you want to install Windows 11.
   - Restart the PC and boot from the USB drive or DVD.
   - Follow the installation prompts to complete the process.

### vi. Install Windows 11
i. **Boot from Installation Media:**
   - Access the BIOS/UEFI settings (usually by pressing F2, F12, Delete, or Esc during boot).
   - Set the USB drive or DVD as the primary boot device.
ii. **Install Windows 11:**
   - Follow the on-screen instructions to install Windows 11.
   - Choose "Custom: Install Windows only (advanced)" if you are doing a clean install.
   - Select the partition where you want to install Windows 11.
   - Proceed with the installation, and the PC will restart several times.

### v. Set Up Windows 11
1. **Complete the Out-of-Box Experience (OOBE):**
   - Follow the setup prompts to select your region, keyboard layout, and sign in with a Microsoft account.
   - Configure privacy settings and choose your preferences.

### vi. Update Windows 11
1. **Check for Updates:**
   - Go to Settings > Windows Update.
   - Click "Check for updates" to ensure you have the latest updates and drivers installed.
### vii. Restore Your Data
Copy your backed-up files to your new Windows 11 installation.
By following these steps, you should be able to install Windows 11 smoothly on your compatible PC.



2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

Here is a step-by-step guide to install Visual Studio Code:
### Step i: Download Visual Studio Code

i. **Visit the Visual Studio Code website:**
   - Go to the [Visual Studio Code download page](https://code.visualstudio.com/Download).

ii. **Select your operating system:**
   - Choose the appropriate installer for your operating system (Windows, macOS, or Linux).

### Step ii: Install Visual Studio Co

i. **Run the installer:**
   - Open the downloaded `VSCodeSetup.exe` file.
   
ii. **Accept the License Agreement:**
   - Read and accept the license agreement by clicking "I accept the agreement" and then click "Next."

iii. **Choose Install Location:**
   - Select the destination folder for the installation and click "Next."

iv. **Select Additional Tasks:**
   - Choose additional tasks such as creating a desktop icon or adding "Open with Code" action to Windows Explorer. Click "Next."

v. **Install:**
   - Click "Install" to begin the installation.

vi. **Finish:**
   - After the installation is complete, click "Finish" to launch Visual Studio Code.


   
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com**Version Control System**: Git

i. **Install Git**
   - Go to the [Git download page](https://git-scm.com/downloads).
   - Download the Git installer for Windows.
   - Run the installer and follow the prompts to install Git.

ii. **Configure Git**
   - Open Git Bash (installed with Git) and run the following commands to set your username and email:
     ```bash
     git config --global user.name "justine-mashaka"
     git config --global user.email "justinmashaka354@gmail.com"
     ```
   
iii. **Create a GitHub Account**
   - Visit [GitHub](https://github.com) and sign up for an account if you don't already have one.
   
iv. **Initialize a Git Repository**
   - Create a new directory for your project:
     ```bash
     mkdir my-project
     cd my-project
     ```
   - Initialize a new Git repository:
     ```bash
     git init
     ```
   - Create a sample file and make your first commit:
     ```bash
     echo "# My Project" > README.md
     git add README.md
     git commit -m "Initial commit"
     ```
   
v. **Push to GitHub**
   - Create a new repository on GitHub.
  
   - Link your local repository to GitHub and push the changes:
     ```bash
     git remote add origin https://github.com/yourusername/my-project.git
     git branch -M main
     git push -u origin main
     ```


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

To install Python and ensure you have the necessary tools to build and execute your code on Windows 11, follow these steps:

### Step 1: Download Python

i. **Visit the Python website:**
   - Go to [python.org](https://www.python.org/downloads/).

ii. **Download the installer:**
   - Click the "Download Python" button. This will download the latest version of Python.

### Step 2: Install Python

i. **Run the installer:**
   - Open the downloaded Python installer (`python-*.exe`).

ii. **Customize installation:**
   - In the Python setup window, check the box that says "Add Python to PATH."
   - Click "Customize installation."

iii. **Optional features:**
   - Ensure that "pip" is selected (pip is the package installer for Python).
   - Optionally select "Documentation" and other features if needed.
   - Click "Next."

iv. **Advanced options:**
   - Leave the default settings as they are.
   - Optionally, you can select "Install for all users" if you want Python to be available for all user accounts on your PC.
   - Click "Install."

v. **Finish installation:**
   - After the installation completes, click "Close."

### Step 3: Verify the Installation

i. **Open Command Prompt or PowerShell:**
   - Press `Win + X` and select "Windows Terminal" or "Command Prompt." or "gitbash"

ii. **Verify Python installation:**
   ```sh
   python --version
   ```
   This should display the version of Python you installed.

iii. **Verify pip installation:**
   ```sh
   pip --version
   ```


5. Install Package Managers:
   If applicable, install package managers like pip (Python).
### Step 4: Install Necessary Python Packages

i. **Identify required packages:**
   - Determine which packages are needed for your project. Common packages include `numpy`, `django`, `requests`, etc.

ii. **Install packages using pip:**
   ```sh
   pip install package_name
   ```
   For example, to install `django`:
   ```sh
   pip install django
   ```

### Step 5: Install and Set Up IDE

You might want to install an Integrated Development Environment (IDE) like Visual Studio Code, PyCharm, or another text editor to write and run your Python code.

#### Install Visual Studio Code

i. **Download Visual Studio Code:**
   - Visit the [Visual Studio Code download page](https://code.visualstudio.com/Download).
   - Download the installer for Windows.

ii. **Run the installer:**
   - Open the downloaded installer and follow the setup instructions.
   - Optionally, check the boxes for creating a desktop icon and adding context menu options.

iii. **Install Python extension:**
   - Open Visual Studio Code.
   - Go to the Extensions view by clicking the Extensions icon on the Activity Bar or pressing `Ctrl+Shift+X`.
   - Search for "Python" and install the Python extension provided by Microsoft.

### Step 6: Verify Your Setup

i. **Create a Python file:**
   - Open Visual Studio Code.
   - Create a new file and save it with a `.py` extension (e.g., `test.py`).

ii. **Write a simple Python script:**
   ```python
   print("Hello, World!")
   ```

iii. **Run the script:**
   - Open the terminal in Visual Studio Code (`Ctrl+` ` `).
   - Run the script using the command:
     ```sh
     python test.py
     ```
   - You should see the output `Hello, World!` in the terminal.
By following these steps, you will have successfully installed Python, set up the necessary tools, and verified that everything is working correctly on Windows 11.

   

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

   ### Step 1: Download MySQL Installer

i. **Visit the MySQL website:**
   - Go to the [MySQL Downloads page](https://dev.mysql.com/downloads/installer/).

ii. **Download the MySQL Installer:**
   - Click on the "Download" button for the MySQL Installer for Windows.
   - Choose either the web installer (smaller file, downloads additional components as needed) or the full installer (larger file, contains all components).

### Step 2: Install MySQL

i. **Run the MySQL Installer:**
   - Open the downloaded `mysql-installer-community-*.exe` file.

ii. **Choose Setup Type:**
   - The installer will prompt you to choose a setup type. You can select "Developer Default" to install MySQL server, MySQL Workbench, and other tools, or customize the installation if you have specific requirements.

iii. **Check Requirements:**
   - The installer will check for any missing dependencies and prompt you to install them if necessary.

iv. **Installation Steps:**
   - Follow the prompts to install the necessary components. The installer will guide you through the installation process.

### Step 3: Configure MySQL Server

i. **Choose Configuration Type:**
   - Select "Standalone MySQL Server / Classic MySQL Replication" for a typical single-server installation.

ii. **Configure MySQL Server:**
   - **Connectivity:** Choose the default port (3306) or specify a different one if needed.
   - **Authentication Method:** You can use the recommended "Use Strong Password Encryption" method.
   - **Accounts and Roles:** Set up a root password and create additional MySQL user accounts if needed.
   - **Windows Service:** You can install MySQL as a Windows service and optionally set it to start automatically.

iii. **Apply Configuration:**
   - The installer will apply the configuration settings and start the MySQL server.

### Step 4: Complete Installation

i. **Finish Installation:**
   - After the configuration is complete, the installer will finish the installation process. You can optionally start MySQL Workbench to manage your databases.

### Step 5: Verify MySQL Installation

i. **Open MySQL Command Line Client:**
   - You can find the MySQL Command Line Client in the Start menu.

ii. **Connect to MySQL:**
   - Open the MySQL Command Line Client and log in using the root user and the password you set during installation.

iii. **Verify Installation:**
   ```sql
   SHOW DATABASES;
   ```
   This command should display a list of default databases, indicating that your MySQL installation is working correctly.


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
          i. **Download VirtualBox:**
   - Visit the [VirtualBox download page](https://www.virtualbox.org/wiki/Downloads) and download the installer suitable for Windows.

ii. **Install VirtualBox:**
   - Run the downloaded VirtualBox installer (`VirtualBox-*.exe`) and follow the installation instructions.
   - You may need to approve administrative permissions and driver installations during the process.

### Step 2: Create a Virtual Machine

Once VirtualBox is installed, you can create a virtual machine to host your development environment.

i. **Open VirtualBox:**
   - Launch VirtualBox from the Start menu or desktop shortcut.

ii. **Create a New Virtual Machine:**
   - Click on "New" to create a new virtual machine.
   - Enter a name for your virtual machine, choose the type of operating system (e.g., Linux, Windows), and select the version.

iii. **Allocate Memory (RAM):**
   - Assign an appropriate amount of RAM for your virtual machine. Ensure it meets the requirements of your development environment.

iv. **Create a Virtual Hard Disk:**
   - Choose to create a new virtual hard disk and follow the prompts. Allocate sufficient disk space based on your project requirements.

v. **Install an Operating System:**
   - Select your newly created virtual machine and click on "Start."
   - Follow the steps to install the operating system of your choice. You'll need an ISO file of the OS (e.g., Ubuntu, Windows) for installation.

vi. **Install Guest Additions (Optional):**
   - After installing the operating system on the virtual machine, install VirtualBox Guest Additions. This enhances the VM's performance and allows features like seamless window integration and shared folders.

### Step 3: Set Up Development Environment

i. **Install Development Tools:**
   - Within the virtual machine, install the necessary development tools and dependencies for your project. This can include programming languages (e.g., Python, Node.js), IDEs (e.g., Visual Studio Code), and databases (e.g., MySQL).

ii. **Configure Networking (Optional):**
   - Set up networking in VirtualBox to allow the virtual machine to access the internet or other machines on your network. Choose between NAT, Bridged, or Host-only networking depending on your requirements.

### Step 4: Use and Manage Your Virtual Machine

i. **Start and Stop Your VM:**
   - Launch VirtualBox and start your virtual machine whenever you need to work on your project.
   - Shut down the VM properly to avoid data corruption.

ii. **Snapshot and Clone VMs (Optional):**
   - VirtualBox allows you to take snapshots of your VM at different stages. This lets you revert to a previous state if needed.
   - You can also clone VMs to quickly create copies for testing or different configurations.

### Step 5: Maintain and Update

i. **Backup Your Virtual Machine:**
   - Regularly back up important data and configurations within your virtual machine.

ii. **Update VirtualBox and VMs:**
   - Keep VirtualBox updated to the latest version for security patches and new features.
   - Update the software and packages within your virtual machines to maintain functionality and security.

   

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

**Extensions for VS Code**:

i. **Python Extension**
   - Open VS Code.
   - Go to the Extensions view by clicking the Extensions icon in the Activity Bar or pressing `Ctrl+Shift+X`.
   - Search for "Python" and install the extension provided by Microsoft.
   
ii. **GitLens**
   - Search for "GitLens" in the Extensions view and install it. This extension provides enhanced Git capabilities.
   
iii. **Prettier - Code formatter**
   - Search for "Prettier" in the Extensions view and install it. This extension helps in formatting the code.
   

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process.
    **steps taken during setting my environment**
    #step1
    - choosing location where my environment may be stored by running cmd (cd e:/)
    #step2
   - create a folder to the location your choosen by running cmd (mkdir folder_name)
    #step3
   - installation of virtual environment by runing cmd (python -m pip install virtualenv)
    #step4
     - create name of project by running cmd (python -m virtualenv name_of_project)
    #step5
       - activate my environment by running cmd ( source name_of_project/scripts/activate
       #step6
    - install programming language eg Django by running cmd (python -m pip install django)
         
    

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
