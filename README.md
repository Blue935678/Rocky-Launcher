# Rocky-Launcher
this is a Launcher thhat is meant to work on bazzite  while being super lightwight 
Let chat gpt expain the commands and libarys needed: 

(note this will try to run any exe you give it not just games)

You can run this with chmod command then with ./(name of launcher )

REQUIRED PYTHON LIBRARY
PyQt6

Used for: GUI windows, buttons, lists, icons, layout management.

INSTALLATION METHODS 
1. pip (user install)

pip3 install --user PyQt6

3. virtual environment (venv)

Creates isolated Python environment so your launcher has its own dependencies.

python3 -m venv rockyenv
source rockyenv/bin/activate
pip install PyQt6

4. pipx (recommended for CLI apps)


Install PyQt6 inside pipx environment:

pipx install PyQt6

This installs the Fedora-maintained Qt6 Python bindings.

SUMMARY OF WHAT YOU NEED TO RUN

The only required non-standard dependency:

PyQt6


Your safest method on Bazzite:

pip3 install --user PyQt6
