# SE-Assignment-5: Installation and Navigation of Visual Studio Code (VS Code)

## 1. Installation of VS Code:

### Steps to Download and Install Visual Studio Code on Windows 11:

1. **Download the Installer:**
   - Go to the [official Visual Studio Code website](https://code.visualstudio.com/).
   - Click on the "Download" button for Windows. This will download the VS Code installer (`VSCodeSetup.exe`).
   

2. **Run the Installer:**
   - Locate the downloaded `VSCodeSetup.exe` file in your Downloads folder and double-click it to start the installation process.

3. **Setup Wizard:**
   - Follow the prompts in the setup wizard.
   - Accept the license agreement.
   - Choose the installation location or accept the default.

4. **Additional Tasks:**
   - Select additional tasks such as creating a desktop icon, adding to PATH (important for command line usage), and associating certain file types with VS Code.
   - Click "Next" and then "Install" to begin the installation.

5. **Complete Installation:**
   - Once the installation is complete, click "Finish" to launch Visual Studio Code.

### Prerequisites:
- Ensure your Windows 11 system is updated.
- Administrative privileges to install software.

## 2. First-time Setup:

### Initial Configurations and Settings:

1. **Theme:**
   - Go to `File` > `Preferences` > `Color Theme` or press `Ctrl+K` then `Ctrl+T` to select a theme.

2. **Font Size:**
   - Navigate to `File` > `Preferences` > `Settings`, then search for "Font Size" and adjust as needed.

3. **Extensions:**
   - Click on the Extensions view icon on the Sidebar or press `Ctrl+Shift+X`.
   - Essential extensions:
     - Prettier - Code formatter
     - ESLint
     - Live Server
     - GitLens
     - Python (if working with Python)
     - Node.js (if working with JavaScript/Node.js)

4. **Settings Sync:**
   - Enable settings sync by going to `File` > `Preferences` > `Settings Sync`.

## 3. User Interface Overview:

### Main Components of the VS Code User Interface:

1. **Activity Bar:**
   - Located on the far left side.
   - Provides access to different views such as Explorer, Search, Source Control, Run and Debug, and Extensions.

2. **Side Bar:**
   - Displays different views and panels depending on the selected activity.
   - For example, in Explorer view, it shows the file and folder structure.

3. **Editor Group:**
   - The main area where files are opened and edited.
   - Supports multiple tabs and split views.

4. **Status Bar:**
   - Located at the bottom of the window.
   - Displays information such as the current file's encoding, line number, column, and the current branch if using Git.

## 4. Command Palette:

### What is the Command Palette and How to Access It:

- The Command Palette provides quick access to many commands and features in VS Code.
- Access it by pressing `Ctrl+Shift+P` or `F1`.

### Common Tasks:

- Changing the theme: Type `>Theme: Color Theme`.
- Installing extensions: Type `>Extensions: Install Extensions`.
- Opening settings: Type `>Preferences: Open Settings`.

## 5. Extensions in VS Code:

### Role of Extensions:

- Extensions add functionality to VS Code, allowing for a customized and enhanced development experience.

### Finding, Installing, and Managing Extensions:

1. **Finding Extensions:**
   - Click on the Extensions view icon on the Sidebar or press `Ctrl+Shift+X`.
   - Browse or search for extensions in the marketplace.

2. **Installing Extensions:**
   - Click the "Install" button for the desired extension.

3. **Managing Extensions:**
   - View installed extensions in the Extensions view.
   - Disable or uninstall extensions as needed.

### Essential Extensions for Web Development:

- **Prettier**: Code formatter.
- **ESLint**: Linting utility for JavaScript.
- **Live Server**: Launch a development local server with live reload.
- **GitLens**: Supercharges Git capabilities in VS Code.
- **Path Intellisense**: Autocompletes filenames.

## 6. Integrated Terminal:

### How to Open and Use the Integrated Terminal:

1. **Opening the Terminal:**
   - Go to `View` > `Terminal` or press `Ctrl+` `.

2. **Using the Terminal:**
   - Supports command-line operations directly within VS Code.
   - Allows running scripts, version control commands, and more without leaving the editor.

### Advantages:

- Integrated experience without switching contexts.
- Multiple terminal instances.
- Customizable shell and commands.

## 7. File and Folder Management:

### Creating, Opening, and Managing Files and Folders:

1. **Creating Files/Folders:**
   - Right-click in the Explorer view and select `New File` or `New Folder`.
   - Use `Ctrl+N` for a new file.

2. **Opening Files/Folders:**
   - Drag and drop files/folders into the editor.
   - Use `File` > `Open Folder` or `Ctrl+K Ctrl+O`.

3. **Navigating Files:**
   - Use `Ctrl+P` to quickly open files.
   - Use breadcrumbs (enabled in settings) for easier navigation.

## 8. Settings and Preferences:

### Finding and Customizing Settings:

1. **Accessing Settings:**
   - Go to `File` > `Preferences` > `Settings` or press `Ctrl+,`.

2. **Changing the Theme:**
   - Search for "Color Theme" and select from the available options.

3. **Adjusting Font Size:**
   - Search for "Font Size" and modify the value.

4. **Customizing Keybindings:**
   - Go to `File` > `Preferences` > `Keyboard Shortcuts` or press `Ctrl+K Ctrl+S`.

## 9. Debugging in VS Code:

### Steps to Set Up and Start Debugging:

1. **Open Debug View:**
   - Click on the Run and Debug icon in the Activity Bar or press `Ctrl+Shift+D`.

2. **Configure Debugging:**
   - Click on `create a launch.json file` to configure the debugger for your project.

3. **Set Breakpoints:**
   - Click in the gutter next to the line numbers to set breakpoints.

4. **Start Debugging:**
   - Press `F5` to start the debugging session.

### Key Debugging Features:

- Step over, step into, and step out of functions.
- Watch expressions.
- Variable inspection.
- Call stack navigation.

## 10. Using Source Control:

### Integrating Git with VS Code:

1. **Initializing a Repository:**
   - Open the Source Control view by clicking the icon in the Activity Bar or pressing `Ctrl+Shift+G`.
   - Click on `Initialize Repository`.

2. **Making Commits:**
   - Stage changes by clicking the `+` icon next to files.
   - Enter a commit message and click the checkmark icon to commit.

3. **Pushing Changes to GitHub:**
   - Click on the ellipsis (`...`) in the Source Control view and select `Push`.
   - Provide credentials if prompted.

