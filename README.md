[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15220624&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. **Installation of VS Code:**
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

**Prerequisites needed include:**

Ensuring that your Windows 11 system meets the minimum requirements for running Visual Studio Code.
Making sure that you have a stable internet connection.
Steps to Download and Install:

**Open a Web Browser:**
Launch your preferred web browser (Microsoft Edge, Google Chrome, or Mozilla Firefox) on your Windows 11 computer.

![image](https://github.com/Powerlearnproject/se-assignment-5-Auraliah/assets/171556090/79ff6782-cb08-4817-a253-bb5e58c0f2ad)

**Navigate to Visual Studio Code Download Page:**
Go to the official Visual Studio Code website by typing "visual studio code download" into the search bar or by directly entering the URL: https://code.visualstudio.com/.

**Download Visual Studio Code:**
Once on the Visual Studio Code website, you will see a prominent download button. Execute it to initiate the download process.

**Choose the Version:**
Depending on your system architecture (32-bit or 64-bit), the website may automatically detect and provide you with the appropriate download link. Make sure to download the correct version for your system.

**Run the Installer:**
Once the download is complete, navigate to the location where the installer file was saved (usually the Downloads folder) and double-click on it to run the installer.

**User Account Control (UAC) Prompt:**
If prompted by User Account Control (UAC), click "Yes" to allow the installer to make changes to your system.

**Install Visual Studio Code:**
Follow the prompts in the installer window. You can choose the installation location and select additional tasks, such as adding VS Code to the PATH variable and creating a desktop shortcut. Click "Next" or "Install" to proceed with the installation. Wait for the installation to complete.

**Launch Visual Studio Code:**
Once the installation is complete, you can launch Visual Studio Code by double-clicking its icon on the desktop or searching for it in the Start menu.

**Choose Development Environment:**
On the welcome screen, select your development environment. For example, you can choose "Development Settings" based on your preferred coding style.
Start Coding:
You're now ready to start coding! Create a new project or open an existing one to begin your development work.
![image](https://github.com/Powerlearnproject/se-assignment-5-Auraliah/assets/171556090/2e816764-dc1d-44b0-b726-625bd5eecce5)



2. **First-time Setup:**
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
Settings:
**Font and Theme:**
Set your preferred font family and size.
Identify a theme that suits your taste and improves readability.

**Indentation and Formatting:**
Adjust indentation settings and configure formatting options for languages you work with ("[language]".editor.formatOnSave).

**File Associations:**
Specify file associations ("files.associations") for languages not detected correctly by default.

**Editor Behavior:**
Customize editor behavior like word wrapping ("editor.wordWrap"), minimap visibility ("editor.minimap.enabled"), etc.

**Workspace Settings:**
Override global settings with workspace-specific settings (".vscode/settings.json").
Extensions:

**Language Support:**
Install extensions for the languages you primarily work with (e.g., Python, JavaScript, Java, etc.).

**Debugger:**
Debugger extensions for your programming languages to facilitate debugging.

**Version Control:**
Git integration (GitLens, Git History) for better version control experience.

**Productivity:**
Extensions like Bracket Pair Colorizer, Code Spell Checker, TODO Highlight, etc., to enhance productivity.
IntelliSense and Code Navigation:

Extensions like IntelliSense, Path Intellisense, Code Navigation, etc., for better code suggestions and navigation.
Formatting and Linting:

Install extensions for formatting and linting (e.g., Prettier, ESLint, Black for Python, TSLint, Rubocop for Ruby, etc.).
Theme and UI Enhancements:

Additional themes or UI enhancements (Material Theme, Peacock, Indent Rainbow, etc.).

**Terminal Integration:**
Extensions to integrate a terminal within VS Code (Terminal, Quokka).
Recommended Practices:
Regular Updates: Keep VS Code and extensions up to date for performance improvements and new features.

Keyboard Shortcuts: Learn and customize keyboard shortcuts for frequently used actions to speed up your workflow.

Workspace Setup: Set up a workspace with folders and configurations tailored to your projects.

Backup Settings: Backup your VS Code settings and configurations (settings.json, keybindings.json) for easy migration

3. **User Interface Overview:**
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
   Visual Studio Code (VS Code) is a versatile code editor known for its user-friendly interface and powerful features. Here are the main components of its user interface:

 1. **Activity Bar**
The Activity Bar is located on the far left side of the window. It contains icons that allow you to switch between different views and functions. The default views include:

- Explorer: Shows the file and folder structure of your project.
- Search: Allows you to search for text within your files.
- Source Control: Integrates with version control systems like Git.
- Run and Debug: Helps in managing debugging sessions.
- Extensions: Lets you browse and install extensions to add new functionalities to VS Code.

 2. **Side Bar**
The Side Bar appears to the right of the Activity Bar. It displays contextual information and tools based on the selected view from the Activity Bar. For example:

- Explorer View: Shows the file and folder hierarchy of your workspace.
- Search View: Displays search results.
- Source Control View: Shows changes, branches, and other version control information.
- Extensions View: Lists installed and available extensions.

The Side Bar provides detailed functionality and options related to the current activity, making it easier to manage your project.

3. **Editor Group**
The Editor Group is the central part of the VS Code interface where you open and edit your files. It supports multiple editors side by side, allowing you to split your workspace into different groups. Key features include:

- Tabs: Each open file is represented by a tab, which makes it easy to switch between multiple files.
- Split Editors: You can split the editor horizontally or vertically to view and edit multiple files simultaneously.
- Preview Mode: Opens files in a temporary tab when you click them in the Explorer, saving memory and keeping the workspace clean.

 4. **Status Bar**
The Status Bar is located at the bottom of the window. It provides information about the current state of the editor and the file you are working on. Key elements include:

- File Information: Displays the current file's encoding, line ending, and language mode.
- Git Branch and Status: Shows the current branch and status of your Git repository.
- Notifications: Alerts you to errors, warnings, and other important information.
- Background Processes: Indicates running processes, such as linters or debuggers.

4. **Command Palette:**
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
The Command Palette in Visual Studio Code (VS Code) is a powerful tool that allows you to access and execute various commands quickly without navigating through menus or remembering keyboard shortcuts. It's a central feature for enhancing productivity and workflow efficiency in VS Code.

Accessing the Command Palette
You can access the Command Palette in a few different ways:

Keyboard Shortcut: Press Ctrl+Shift+P (Windows/Linux) 
Menu Bar: Go to View > Command Palette.
Common Tasks Performed Using the Command Palette
Here are some examples of what you can do with the Command Palette:

Opening and Managing Files:

Open a file: Type Open File.
Quick Open: Type part of a file name to quickly open it.
Git Integration:

Git: Clone: Clone a repository by typing Git: Clone.
Git: Commit: Stage changes and commit them.
Extensions:

Install Extensions: Type Extensions: Install and search for the desired extension.
Disable/Enable Extensions: Type Extensions: Disable or Extensions: Enable.
Editor Operations:

Format Document: Type Format Document to format your code according to the configured style.
Change Language Mode: Type Change Language Mode to switch the syntax highlighting mode.
Search and Navigation:

Go to Line: Type Go to Line followed by a line number to jump to a specific line.
Go to Symbol: Type @ followed by a symbol name to navigate to a function, class, or variable in the file.
Terminal Commands:

Create New Terminal: Type Create New Integrated Terminal to open a new terminal instance.
Run Task: Type Run Task to execute a predefined task from your tasks.json file.
View and Layout Management:

Toggle Sidebar Visibility: Type View: Toggle Sidebar Visibility to show or hide the sidebar.
Split Editor: Type View: Split Editor to split the editor into multiple views.

5. **Extensions in VS Code:**
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

Extensions play a crucial role in Visual Studio Code (VS Code) by enhancing its functionality and allowing users to tailor the editor to their specific needs. Extensions can provide additional language support, debugging tools, linting, themes, and more, making VS Code a highly customizable and powerful development environment.
![image](https://github.com/Powerlearnproject/se-assignment-5-Auraliah/assets/171556090/c005e137-bc28-4f6f-9e1c-d7f12860e68e)

Finding, Installing, and Managing Extensions
Finding Extensions
Marketplace: Access the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or by using the keyboard shortcut Ctrl+Shift+X.
![image](https://github.com/Powerlearnproject/se-assignment-5-Auraliah/assets/171556090/f6fb4674-11cd-46bb-8900-fe07d89caf54)
From there, you can browse and search for extensions in the Visual Studio Code Marketplace.
Installing Extensions
Extensions View: In the Extensions view, type the name of the extension you want to install. Click the Install button next to the extension in the search results.
![image](https://github.com/Powerlearnproject/se-assignment-5-Auraliah/assets/171556090/c2ff7362-2cdc-4c08-a18a-2c5cc17d14d2)

Managing Extensions
Enable/Disable Extensions: In the Extensions view, click on the installed extension and then click Disable or Enable.
Uninstall Extensions: In the Extensions view, find the installed extension and click the Uninstall button.
Update Extensions: When updates are available, you will see an update button next to the extension in the Extensions view.
![image](https://github.com/Powerlearnproject/se-assignment-5-Auraliah/assets/171556090/c4d7dfd9-7e24-4fc5-88a3-5c746e6550b6)

Essential Extensions for Web Development
Live Server: Launch a local development server with live reload feature for static and dynamic pages.

Features: Real-time updates in the browser as you edit your code.
Prettier - Code Formatter: An opinionated code formatter that enforces a consistent style.
![image](https://github.com/Powerlearnproject/se-assignment-5-Auraliah/assets/171556090/736610c3-cdc7-4bbc-a7d1-2ec0b7143d0f)

Features: Enhances CSS navigation and editing efficiency.

6. **Integrated Terminal:**
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
  
Opening and Using the Integrated Terminal in VS Code
Opening the Integrated Terminal
Keyboard Shortcut:

Press Ctrl + (backtick) on Windows/Linux orCmd + (backtick) on macOS.
Menu Bar:

Go to View > Terminal.
Command Palette:

Open the Command Palette (Ctrl+Shift+P), then type and select View: Toggle Terminal.
Using the Integrated Terminal

Basic Commands:

Once the terminal is open, you can use it just like any other terminal. You can run commands, execute scripts, use version control tools like Git, and more.
Multiple Terminals:

You can create multiple terminal instances by clicking the + icon in the terminal tab or using the shortcut Ctrl+Shift+ (backtick) orCmd+Shift+ (backtick).
Switch between terminals using the dropdown menu in the terminal tab.
Split Terminal:

To split the terminal view, click the split terminal icon (two overlapping rectangles) or use the command Ctrl+\ or Cmd+\.
Customizing Terminal:

You can customize the terminal settings, such as font size, font family, and cursor style, through the settings (File > Preferences > Settings or Cmd+,).
Advantages of Using the Integrated Terminal
Convenience and Efficiency:

Having the terminal integrated within VS Code allows you to avoid switching between windows or applications, which streamlines the workflow and saves time.
Context Awareness:

The integrated terminal opens with the context of the current project directory, making it easier to run commands that are specific to the project without needing to navigate to the correct directory manually.
Better Integration with Editor:

Features like linking errors from the terminal output directly to the code in the editor enhance debugging and error resolution.
You can easily drag and drop files from the explorer to the terminal to get their paths.
Consistent Environment:

The integrated terminal uses the same shell environment as your external terminal (Bash, PowerShell, Command Prompt, etc.), ensuring consistency in the commands and scripts you run.
Customizable Layout:

You can adjust the layout of the terminal alongside your editor, splitting views, and arranging your workspace according to your preferences.
Integrated Version Control:

With built-in Git support, you can perform Git operations directly from the terminal while viewing changes, commits, and branches within the editor.
Extension Support:


7. **File and Folder Management:**
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
Creating Files and Folders
Creating a New File:

Keyboard Shortcut: Press Ctrl+N (Windows/Linux) or Cmd+N (macOS) to create a new untitled file.
File Explorer: Right-click on the folder in the Explorer panel where you want to create the file and select New File. Type the name of the file and press Enter.
Creating a New Folder:

File Explorer: Right-click on the folder where you want to create the new folder and select New Folder. Type the name of the folder and press Enter.
Opening Files and Folders
Opening a File:

Keyboard Shortcut: Press Ctrl+O (Windows/Linux) or Cmd+O (macOS) and use the dialog box to navigate to and open a file.
File Explorer: Double-click on the file in the Explorer panel to open it.
Opening a Folder/Workspace:

Keyboard Shortcut: Press Ctrl+K followed by Ctrl+O (Windows/Linux) or Cmd+K followed by Cmd+O (macOS) to open a folder or workspace.
Menu Bar: Go to File > Open Folder and use the dialog box to select and open the folder.
Managing Files and Folders
Renaming Files/Folders:

File Explorer: Right-click on the file or folder and select Rename, then type the new name and press Enter.
Deleting Files/Folders:

File Explorer: Right-click on the file or folder and select Delete, then confirm the deletion.
Moving Files/Folders:

File Explorer: Drag and drop the file or folder to the desired location within the Explorer panel.
Navigating Between Files and Directories Efficiently
Quick Open:

Keyboard Shortcut: Press Ctrl+P. Type the name of the file you want to open. This provides a quick search through your workspace.
File Explorer:

Use the File Explorer panel on the left side to browse and open files and folders by clicking on them.
Breadcrumbs:

Breadcrumbs show the current file's location in the folder structure. You can click on parts of the breadcrumb to navigate to parent folders or sibling files.
To enable breadcrumbs, go to View > Show Breadcrumbs.
Tab Management:

Opened files appear as tabs at the top of the editor. Click on tabs to switch between files.
Close tabs by clicking the X on the tab or using the keyboard shortcut Ctrl+W.
Go to Symbol:

Keyboard Shortcut: Press Ctrl+Shift+O to open the list of symbols in the current file. This allows for quick navigation within a file.
Go to Line:

Keyboard Shortcut: Press Ctrl+G and enter the line number to jump to a specific line in the current file.
Search Across Files:

Keyboard Shortcut: Press Ctrl+Shift+F to open the search panel. This allows you to search for text across all files in your workspace.
Integrated Terminal:

Use the integrated terminal to navigate your project’s directory structure and open files with commands like code filename to open filename in VS Code from the terminal.

8. **Settings and Preferences:**
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
  VS Code settings can be customized to tailor the development environment to your preferences. Users can access and modify settings through the graphical interface or by editing the settings JSON file directly.

Accessing Settings
Graphical Interface:

Menu Bar: Go to File > Preferences > Settings.
Keyboard Shortcut: Press Ctrl+Shift+P
![image](https://github.com/Powerlearnproject/se-assignment-5-Auraliah/assets/171556090/892dcf0f-417b-4630-8c29-dc4df802ea02)

Settings JSON:
Graphical Interface: In the Settings tab, click the {} icon in the top right corner to open the settings.json file for direct editing.

Changing the Theme
Graphical Interface:
Command Palette: Open the Command Palette with Ctrl+Shift+P, then type Preferences: Color Theme and select it. Choose from the list of available themes.
Settings: Go to File > Preferences > Color Theme. 
Graphical Interface:

Menu Bar: Go to File > Preferences > Keyboard Shortcuts.
Keyboard Shortcut: Press Ctrl+K Ctrl+S.
Editing Keybindings JSON:
In the Keyboard Shortcuts tab, click the {} icon in the top right corner to open the keybindings.json file for direct editing.
Add or modify keybinding entries. For example, to change the keybinding for saving all files:

9. **Debugging in VS Code:**

10. **Using Source Control:**
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
Integrating Git with VS Code for Version Control
VS Code offers robust Git integration, making it easy to manage version control directly from the editor. Here's how users can initialize a repository, make commits, and push changes to GitHub.

Initializing a Repository
Open VS Code:

Open the project folder in VS Code.
Initialize Git Repository:

Source Control View: Click on the Source Control icon in the Activity Bar on the side of the window.
Initialize Repository: Click the Initialize Repository button. This will create a .git folder in your project directory.
Command Palette:

Open the Command Palette with Ctrl+Shift+P.
Type Git: Initialize Repository and select it.
Making Commits
Staging Changes:

Source Control View: The Source Control panel shows all the changes made to the files in your project.
To stage a file, click the + icon next to the file name. To stage all changes, click the + icon in the Changes header.
Committing Changes:

Source Control View: Once the changes are staged, enter a commit message in the message box at the top of the Source Control panel.
Click the checkmark icon to commit the changes.
Command Palette:

Open the Command Palette with Ctrl+Shift+P.
Type Git: Commit Staged to commit staged changes or Git: Commit All to commit all changes.
Pushing Changes to GitHub
Add Remote Repository:

Command Palette: Open the Command Palette with Ctrl+Shift+P.
Type Git: Add Remote and select it.
Enter the remote name (usually origin) and the GitHub repository URL.
Push Changes:

Source Control View: Click the ellipsis (...) in the Source Control panel and select Push or Push to....
Command Palette: Open the Command Palette, type Git: Push and select it.
Using Terminal:

Open the integrated terminal in VS Code with Ctrl+ (backtick) or from the menuView>Terminal`.
git push -u origin main
Example Workflow
Initialize a Repository:

Open your project folder in VS Code.
Click the Source Control icon and click Initialize Repository.
Make Changes:

Edit your files as needed.
Stage Changes:

Go to the Source Control panel.
Click the + icon next to the files you want to stage.
Commit Changes:

Enter a commit message in the message box at the top of the Source Control panel.
Click the checkmark icon to commit the changes.
Push to GitHub:

Ensure you have added the remote repository.
Click the ellipsis in the Source Control panel and select Push.


