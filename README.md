# python-multitool-template
A light-weight tool for launching your apps directly from the terminal.
### How to use
No installation required. Put your files on the *files* directory, open the script and you're ready to go.

## FAQ (Frequently Asked Questions)
- Does it work on Linux/macOS?
Absolutely. At the start of the script, there is a Shebang that looks like this: `#!/usr/bin/env python3`
that makes the system recognize its a Python file, but the script includes a library called `os`, that is Windows-exclusive.
If you want to use this on Linux/macOS, you can download the Linux version of the .py file on the Releases page called "pymt-linux-macos.py".
- Do i need any additional libraries?
Nope. The script only makes use of the `os` library that comes pre-installed in Python. 
