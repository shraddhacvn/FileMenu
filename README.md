# FileMenu

This project is a simple file editor built using Python's Tkinter library. The editor allows users to open, edit, and save text files. 

## Features

- **Open File**: Open a text file from the file system.
- **Save As**: Save the current text in the editor to a new file.
- **Exit**: Exit the file editor.
- **Edit Menu**: Includes placeholder commands for common edit operations like Undo, Cut, Copy, Paste, Delete, and Select All.
- **Help Menu**: Placeholder commands for help options.

## Getting Started

### Prerequisites

- Python 3.x
- Tkinter (usually included with standard Python installations)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/shraddhacvn/file-menu.git
    cd file-editor
    ```

2. Run the file editor:
    ```sh
    python file_menu.py
    ```

## Usage

1. **Open File**: Click `File > Open` to open a text file. The contents of the file will be displayed in the editor.
2. **Save As**: Click `File > Save as...` to save the current text to a new file.
3. **Exit**: Click `File > Exit` to close the editor.
4. **Edit Menu**: Access edit commands from `Edit` menu. These commands currently do nothing but can be implemented as needed.
5. **Help Menu**: Access help options from `Help` menu. These commands currently do nothing but can be implemented as needed.

## Code Overview

### Functions

- `donothing()`: A placeholder function that does nothing.
- `open_file()`: Opens a file dialog to select a file and displays its contents in the text widget.
- `save_as_file()`: Opens a file dialog to save the current text in the text widget to a new file.
- `exit_editor()`: Closes the editor.

### Main Interface

- `root`: The main window of the application.
- `menubar`: The main menu bar containing File, Edit, and Help menus.
- `display_text`: A `Text` widget for displaying and editing text.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

---

