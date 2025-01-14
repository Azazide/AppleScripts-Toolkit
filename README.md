# AppleScripts Toolkit

A powerful toolkit of AppleScripts and shell scripts designed to enhance productivity on macOS. This repository includes utilities for compressing files, previewing archive contents, and creating text documents directly from the Finder.

![Project Logo](assets/logo.png)

## Features

1. **Compress Files**  
   - Creates archives in `.zip` or `.rar` formats.  
   - Supports password protection for secure file storage.  
   - Provides a user-friendly dialog to customize archive name, format, and password.

2. **Preview Archive Contents**  
   - Opens the contents of `.zip`, `.rar`, `.tar`, `.tar.gz`, and `.tgz` files in Finder.  
   - Ensures a list view for easier navigation.  
   - Automatically cleans up temporary files after inspection.

3. **Create Text Document**  
   - Quickly creates a new text file in the current Finder directory or on the desktop.  
   - Automatically names files to avoid overwriting existing ones.

## Installation

1. Clone the repository or download the ZIP:
   ```bash
   git clone https://github.com/Azazide/AppleScripts-Toolkit.git
   cd AppleScripts-Toolkit
   ```

2. Copy the required scripts to the `~/Library/Services/` directory:
   - Navigate to `~/Library/Services/` in Finder (you can access it by pressing `Command + Shift + G` and entering the path).
   - Place the scripts in this folder to make them available in the Finder Services menu.

3. Add the scripts to the Finder Services menu:
   - Open **Automator** on macOS.
   - Create a new **Quick Action**.
   - Drag and drop the desired script file into the workflow area.
   - Save the Quick Action with a recognizable name.

4. Grant necessary permissions:
   - Ensure that `Finder`, `Terminal`, and `Automator` have full disk access in **System Preferences > Security & Privacy**.

## Usage

### Compress Files
- Run the script to open a dialog for archive customization.
- Choose the archive format (`.zip` or `.rar`), provide a password (optional), and confirm the archive name.

### Preview Archive Contents
- Select an archive file and run the script.
- The script will extract the contents to a temporary folder and display them in Finder.

### Create Text Document
- Run the script to create a new `.txt` file in the current Finder directory or desktop.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

Feel free to fork and contribute to the project!
