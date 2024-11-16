# Icon2DLL - v1.0 Release

## Release Information
- **Version**: v1.0
- **Author**: GraveDigger7863
- **Date**: *(Insert Release Date)*
- **Description**: Icon2DLL is a simple tool to convert `.ico` files in a folder into a single `.dll` containing the icons as resources. This is perfect for developers and designers needing to bundle multiple icons into a single resource file.

## Features
- Intuitive graphical interface to select the source and destination folders.
- Converts all `.ico` files in the source folder into a `.dll`.
- Clean and efficient design with no console interface.

## Download
[Download Icon2DLL v1.0](https://github.com/gravedigger7863/Icon2dll/raw/refs/heads/main/ICO2DLL.exe)

---

# How to Use

### Step 1: Download and Launch
1. Download the `.exe` file from the link above.
2. Place it in a convenient location on your computer.
3. Double-click the `.exe` file to launch the application.

### Step 2: Select Folders
1. Click **Browse** next to the **Source Folder** field to select the folder containing your `.ico` files.
2. Click **Browse** next to the **Destination Folder** field to select the folder where the generated `.dll` file will be saved.

### Step 3: Build the DLL
1. After selecting the folders, click the **Build DLL** button.
2. The application will process the `.ico` files and generate a `icons.dll` in the destination folder.
3. A success message will appear upon completion.

---

# System Requirements
- Windows 10 or higher
- Python runtime not required (standalone executable)
- Required tools (included internally): `windres`, `gcc`

---

# Known Issues
- Ensure the source folder contains only `.ico` files to avoid errors.
- Make sure the destination folder is writable.

---

# Contributing
Feel free to fork the repository, report issues, or submit pull requests. Contributions are welcome!

---

# License
This project is licensed under the MIT License. See the LICENSE file for details.

---

# Contact
- **Author**: GraveDigger7863
- **GitHub**: [GraveDigger7863](https://github.com/GraveDigger7863)
- **Email**: *(Insert Email Address)*

