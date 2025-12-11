# Rocky-Launcher
this is a Launcher thhat is meant to work on bazzite  while being super lightwight 
Let chat gpt expain the commands and libarys needed: REQUIRED PYTHON LIBRARY
PyQt6

Used for: GUI windows, buttons, lists, icons, layout management.

INSTALLATION METHODS (with descriptions)
1. pip (user install)

Installs PyQt6 only for your user account.
Recommended on Bazzite because it avoids system conflicts.

pip3 install --user PyQt6

2. pip (system-wide install)

Installs PyQt6 for all users.
Requires sudo. Not recommended on immutable/OSTree systems like Bazzite.

sudo pip3 install PyQt6

3. virtual environment (venv)

Creates isolated Python environment so your launcher has its own dependencies.

python3 -m venv rockyenv
source rockyenv/bin/activate
pip install PyQt6


To run the app later:

source rockyenv/bin/activate
python rocky_launcher_v4_0

4. pipx (recommended for CLI apps)

Installs the app into an isolated environment with automatic PATH handling.

Install pipx:

sudo dnf install pipx
pipx ensurepath


Install PyQt6 inside pipx environment:

pipx install PyQt6


This installs the Fedora-maintained Qt6 Python bindings.

SUMMARY OF WHAT YOU NEED TO RUN

The only required non-standard dependency:

PyQt6


Your safest method on Bazzite:

pip3 install --user PyQt6
