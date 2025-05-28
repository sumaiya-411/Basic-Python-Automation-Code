# File Renamer Automation Script

This Python script automatically renames all files in a specified folder to a sequential format like `file_1`, `file_2`, etc., while preserving their original file extensions. It is useful for organizing large sets of files quickly and efficiently.

## 📁 How It Works

- Scans all files in the given folder
- Extracts each file’s extension
- Renames the file to `file_<number>.<extension>`

## 🛠 Requirements

- Python 3.x

No external libraries are required.

## ▶️ Usage

1. Open the script in your Python editor.
2. Change the `folder_path` variable to the folder you want to process.
3. Run the script:

```bash
python rename_files.py
