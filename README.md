[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15283232&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

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


-- ANSWERS --

UBUNTU OPERATING SYSTEM

### Installation of VS Code:

**To install Visual Studio Code on Ubuntu using Command Line:**
Open Terminal: You can open the terminal either by pressing Ctrl + Alt + T or by searching for "Terminal" in the application launcher.

**Update Package Repository: Run the following command:**

sudo apt update

**Install Visual Studio Code: Use the following command to install VS Code:**

sudo apt install code

This command will prompt you to enter your administrative password. Type it in and press Enter.

Wait for Installation: The terminal will download and install Visual Studio Code along with any necessary dependencies.

Launch VS Code: Once installed, you can launch Visual Studio Code by typing code in the terminal and pressing Enter.

### First-time Setup:

After installing VS Code:

1. **Extensions**: Install extensions like "Live Server" for web development.
   
2. **Settings**: Adjust settings such as the default theme, font size, and keybindings through the `File > Preferences > Settings` menu.

### User Interface Overview:

- **Activity Bar**: Provides quick access to different views like Explorer and Source Control.
  
- **Side Bar**: Contains various panels like Explorer (file explorer), Search, and Extensions.

- **Editor Group**: Displays open editors in tabs within the editor area.

- **Status Bar**: Shows information such as line and column number, Git branch, and encoding.

### Command Palette:

The Command Palette in VS Code can be accessed via `View > Command Palette` or using the shortcut `Ctrl+Shift+P`.

Common tasks:
- Opening files (`Open File...`)
- Running tasks (`Run Task...`)
- Installing extensions (`Extensions: Install Extensions`)

### Extensions in VS Code:

Extensions enhance VS Code's functionality. They can be found and managed through the Extensions view (`Ctrl+Shift+X`). Essential extensions for web development include:
- **Live Server**: Provides a development local server with live reload feature.
- **ESLint**: JavaScript linter for identifying and fixing problems in your code.

### Integrated Terminal:

To open the integrated terminal in VS Code, use the shortcut ``Ctrl+` `` (backtick). Advantages include:
- Seamless integration with your development environment.
- Easy access to command line tools without switching windows.

### File and Folder Management:

- **Creating files/folders**: Use the Explorer sidebar or `File > New File` / `File > New Folder`.
  
- **Opening files/folders**: Double-click in Explorer or use `File > Open...`.

- **Navigating efficiently**: Utilize the Explorer sidebar for quick navigation between files and folders.

### Settings and Preferences:

Settings are found under `File > Preferences > Settings`. Examples:
- **Theme**: Search for "theme", choose a theme from the dropdown.
- **Font size**: Search for "font size", adjust the setting accordingly.
- **Keybindings**: Search for "keybindings", customize as needed.

### Debugging in VS Code:

1. **Setup**: Install a language-specific debugger extension like "Debugger for JavaScript".
   
2. **Start debugging**: Set breakpoints in your code and use `Run > Start Debugging` or `F5`.

### Using Source Control:

1. **Integrating Git**: Ensure Git is installed (`sudo apt-get install git`). Initialize a repository in VS Code (`View > Command Palette > Git: Initialize Repository`).

2. **Making commits**: Stage changes via the Source Control view and commit with a message.

3. **Pushing changes**: Use `Push` in the Source Control view to push commits to GitHub.


