#  SetlX for Sublime Text 3

SetlX Syntax Highlighting and Build System for Sublime Text 3.
- Sublime Text 3: http://www.sublimetext.com/3
- SetlX: http://randoom.org/Software/SetlX

# Installation
1. In Sublime Text 3 click ``Preferences -> Browse Packages...`` to open the packages directory
2. Clone the repository or click `` Download ZIP `` and extract the folder into this directory
3. Edit ``setlx.sublime-build`` and replace ``SETLX_BINARY_PATH_HERE`` with an absolute path to the directory containing the SetlX jar-files;
	Make sure to use backslashes to escape backslashes in Windows filesystem paths (It's a JSON file)!
	``C:\SetlX`` --> ``"working_dir": "C:\\SetlX"``
4. Done!