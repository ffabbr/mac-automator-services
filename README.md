# Mac Automator Services

This repository contains useful macOS Automator workflow services that can be accessed from the right-click context menu or assigned keyboard shortcuts.

## Available Services

- **Create New File Without Filetype.workflow** - Creates a new file without requiring a file extension
- **Open in IDE.workflow** - Opens files or folders in your preferred IDE

## Installation

1. Download the `.workflow` folders from this repository. The "folders" will be displayed as a single packed file in MacOS.
2. Copy the `.workflow` files to your Services folder:
   ```
   ~/Library/Services/
   ```
   
   You can access this folder by:
   - Opening Finder
   - Pressing `Cmd + Shift + G` (Go to Folder)
   - Typing `~/Library/Services/` and pressing Enter
   
   Alternatively, you can use Terminal:
   ```bash
   cp *.workflow ~/Library/Services/
   ```

3. The services will now appear in the menu bar when clicking on the application name, then services. 
4. If something doesn't work or you want to edit the files, open the folder as above and double click the Automator files. They will open in the editor automatically.

## Assigning Keyboard Shortcuts

To assign keyboard shortcuts to these services:

1. Open **System Settings** (or **System Preferences** on older macOS versions)
2. Navigate to **Keyboard** → **Keyboard Shortcuts** 
3. In the left sidebar, select **Services**
4. Find your installed services in the list on the right
5. Click on the service you want to assign a shortcut to
6. Click **Add Shortcut** and press your desired key combination
7. Click **Done** to save