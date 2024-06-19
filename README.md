[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15220624&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

Prerequisites needed include:

Ensuring that your Windows 11 system meets the minimum requirements for running Visual Studio Code.
Making sure that you have a stable internet connection.
Steps to Download and Install:

Open a Web Browser:
Launch your preferred web browser (Microsoft Edge, Google Chrome, or Mozilla Firefox) on your Windows 11 computer.

![image](https://github.com/Powerlearnproject/se-assignment-5-Auraliah/assets/171556090/79ff6782-cb08-4817-a253-bb5e58c0f2ad)

Navigate to Visual Studio Code Download Page:
Go to the official Visual Studio Code website by typing "visual studio code download" into the search bar or by directly entering the URL: https://code.visualstudio.com/.

Download Visual Studio Code:
Once on the Visual Studio Code website, you will see a prominent download button. Execute it to initiate the download process.

Choose the Version:
Depending on your system architecture (32-bit or 64-bit), the website may automatically detect and provide you with the appropriate download link. Make sure to download the correct version for your system.

Run the Installer:
Once the download is complete, navigate to the location where the installer file was saved (usually the Downloads folder) and double-click on it to run the installer.

User Account Control (UAC) Prompt:
If prompted by User Account Control (UAC), click "Yes" to allow the installer to make changes to your system.

Install Visual Studio Code:
Follow the prompts in the installer window. You can choose the installation location and select additional tasks, such as adding VS Code to the PATH variable and creating a desktop shortcut. Click "Next" or "Install" to proceed with the installation. Wait for the installation to complete.


Launch Visual Studio Code:
Once the installation is complete, you can launch Visual Studio Code by double-clicking its icon on the desktop or searching for it in the Start menu.

Choose Development Environment:
On the welcome screen, select your development environment. For example, you can choose "Development Settings" based on your preferred coding style.
Start Coding:
You're now ready to start coding! Create a new project or open an existing one to begin your development work.
![image](https://github.com/Powerlearnproject/se-assignment-5-Auraliah/assets/171556090/2e816764-dc1d-44b0-b726-625bd5eecce5)



2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
Settings:
Font and Theme:
Set your preferred font family and size.
Identify a theme that suits your taste and improves readability.

Indentation and Formatting:
Adjust indentation settings and configure formatting options for languages you work with ("[language]".editor.formatOnSave).

File Associations:
Specify file associations ("files.associations") for languages not detected correctly by default.
Editor Behavior:

Customize editor behavior like word wrapping ("editor.wordWrap"), minimap visibility ("editor.minimap.enabled"), etc.
Workspace Settings:

Override global settings with workspace-specific settings (".vscode/settings.json").
Extensions:
Language Support:

Install extensions for the languages you primarily work with (e.g., Python, JavaScript, Java, etc.).
Debugger:

Debugger extensions for your programming languages to facilitate debugging.
Version Control:

Git integration (GitLens, Git History) for better version control experience.
Productivity:

Extensions like Bracket Pair Colorizer, Code Spell Checker, TODO Highlight, etc., to enhance productivity.
IntelliSense and Code Navigation:

Extensions like IntelliSense, Path Intellisense, Code Navigation, etc., for better code suggestions and navigation.
Formatting and Linting:

Install extensions for formatting and linting (e.g., Prettier, ESLint, Black for Python, TSLint, Rubocop for Ruby, etc.).
Theme and UI Enhancements:

Additional themes or UI enhancements (Material Theme, Peacock, Indent Rainbow, etc.).
Terminal Integration:

Extensions to integrate a terminal within VS Code (Terminal, Quokka).
Recommended Practices:
Regular Updates: Keep VS Code and extensions up to date for performance improvements and new features.

Keyboard Shortcuts: Learn and customize keyboard shortcuts for frequently used actions to speed up your workflow.

Workspace Setup: Set up a workspace with folders and configurations tailored to your projects.

Backup Settings: Backup your VS Code settings and configurations (settings.json, keybindings.json) for easy migration

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
   Visual Studio Code (VS Code) is a versatile code editor known for its user-friendly interface and powerful features. Here are the main components of its user interface:

 1. **Activity Bar**
The Activity Bar is located on the far left side of the window. It contains icons that allow you to switch between different views and functions. The default views include:

- **Explorer**: Shows the file and folder structure of your project.
- **Search**: Allows you to search for text within your files.
- **Source Control**: Integrates with version control systems like Git.
- **Run and Debug**: Helps in managing debugging sessions.
- **Extensions**: Lets you browse and install extensions to add new functionalities to VS Code.

 2. **Side Bar**
The Side Bar appears to the right of the Activity Bar. It displays contextual information and tools based on the selected view from the Activity Bar. For example:

- **Explorer View**: Shows the file and folder hierarchy of your workspace.
- **Search View**: Displays search results.
- **Source Control View**: Shows changes, branches, and other version control information.
- **Extensions View**: Lists installed and available extensions.

The Side Bar provides detailed functionality and options related to the current activity, making it easier to manage your project.

3. **Editor Group**
The Editor Group is the central part of the VS Code interface where you open and edit your files. It supports multiple editors side by side, allowing you to split your workspace into different groups. Key features include:

- **Tabs**: Each open file is represented by a tab, which makes it easy to switch between multiple files.
- **Split Editors**: You can split the editor horizontally or vertically to view and edit multiple files simultaneously.
- **Preview Mode**: Opens files in a temporary tab when you click them in the Explorer, saving memory and keeping the workspace clean.

 4. **Status Bar**
The Status Bar is located at the bottom of the window. It provides information about the current state of the editor and the file you are working on. Key elements include:

- **File Information**: Displays the current file's encoding, line ending, and language mode.
- **Git Branch and Status**: Shows the current branch and status of your Git repository.
- **Notifications**: Alerts you to errors, warnings, and other important information.
- **Background Processes**: Indicates running processes, such as linters or debuggers.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

