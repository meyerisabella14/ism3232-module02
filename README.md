# ISM3232 - Module 2: zsh Navigation and File Operations

## Commands Practiced

| Command | What it does |
|---|---|
| pwd | Prints the current working directory |
| ls | Lists visible files and folders |
| ls -la | Lists all files, including hidden ones |
| cd | Changes directories |
| cd .. | Moves up one directory |
| mkdir | Creates a new folder |
| tree -L 2 | Shows the folder structure two levels deep |
| touch | Creates an empty file |
| echo | Writes text to a file |
| cat | Displays the contents of a file |
| head -1 | Displays the first line of a file |
| cp | Copies a file |
| mv | Moves or renames a file |
| rm | Permanently deletes a file |
| python3 | Runs a Python file |
| code . | Opens the current folder in VS Code |

## AI Use Statement
I used AI to help me understand the steps for this lab.
## Week 3: Virtual Environments and .zshrc

- python3 -m venv .venv — creates a virtual environment
- source .venv/bin/activate — activates the virtual environment
- which python3 — shows which Python is being used
- pip install pytest ruff — installs packages in the venv
- pip freeze > requirements.txt — saves installed package 
versions
- deactivate — exits the virtual environment
- ll — shortcut for ls -la
- gs — shortcut for git status
- mkcd — creates a directory and enters it

