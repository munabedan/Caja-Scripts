
# Caja Scripts

Caja Scripts is a collection of custom scripts for the Caja file manager (the default file manager in the Mate desktop environment). These scripts extend the functionality of Caja, allowing you to perform various tasks on selected files and folders via the right-click context menu. This repository is an open-source project, and you're welcome to contribute, share, and improve these scripts.

## Hide Files Script

### Description

The "Hide Files" script is designed to hide selected files within the Caja file manager. This script creates or modifies a `.hidden` file within the selected directory, listing the names of files you want to hide. This is particularly useful for organizing and decluttering your file system.

### Usage

1. Select the file(s) or folder(s) you want to hide in Caja.
2. Right-click on your selection to open the context menu.
3. Navigate to the "Scripts" submenu.
4. Choose the "Hide Files" script from the submenu.


After running the script, the selected files will be hidden, and you'll receive a notification using Zenity. To view the changes, you may need to refresh your file manager by clicking the "Reload" button on the toolbar.

### Installation

To use the "Hide Files" script, follow these steps:

1. Copy the script content from `Hide files` and create a new file in your Caja scripts directory, typically located at `~/.config/caja/scripts/`. You can name the script file as you like, for example, `Hide files.sh`.

2. Make the script executable by running:

   ```shell
   chmod +x ~/.config/caja/scripts/'Hide files.sh'
   ```

3. Now, you can select files in Caja, right-click, and find the "Hide Files" script under the "Scripts" submenu.

### Contribute

This project is open to contributions. If you have additional scripts or improvements to existing ones, feel free to submit a pull request. Let's make the Caja file manager even more powerful together!

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

**Note:** Please make sure to have the required dependencies like Zenity and Bash installed on your system to use the scripts effectively.


Thank you for using and supporting Caja Scripts!
