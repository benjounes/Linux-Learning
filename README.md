Welcome to my Linux learning repository!

I am a second-year Electronics Engineering student specializing in VLSI at PSG iTech. This repository documents my journey of learning Linux using Ubuntu on WSL 2, building a strong foundation for VLSI design and verification.

🎯 Objectives

- Learn Linux fundamentals and terminal commands.
- Understand file and directory management.
- Practice Linux commands through hands-on exercises.
- Build a foundation for Verilog and VLSI development tools.

- Day 1 - Commands Learnt

- System Information

Command| Purpose
"uname -a"| Displays system and kernel information
"whoami"| Displays the current username
"history"| Shows previously executed commands

Directory Navigation

Command| Purpose
"pwd"| Displays the current directory
"ls"| Lists files and directories
"cd"| Changes the current directory
"mkdir"| Creates a directory

File Management

Command| Purpose
"touch filename"| Creates an empty file
"cat filename"| Displays file contents
"echo "text" > filename"| Writes text to a file, replacing existing content
"mv old.txt new.txt"| Moves or renames a file
"rm filename"| Removes a file

Text Editors

Command| Purpose
"vi filename"| Opens a file in the Vi editor
"nano filename"| Opens a file in the Nano editor

Editor Shortcuts

Shortcut| Purpose
"Ctrl + Shift + C"| Copies selected text in a terminal
"Ctrl + Shift + V"| Pastes text into a terminal


- Day 2 — File Management and Command-Line Basics

Directory Navigation

- "cd ~" — Navigate to the home directory.
- "cd -" — Return to the previous working directory.
- "ls -la" — List files, including hidden files, with details.
- "ls .bash*" — List matching names beginning with ".bash".
- "ls *.py" — List files matching the ".py" pattern.

File Operations and Links

- "rm -r directory" — Remove a directory and its contents.
- "ln target linkname" — Create a hard link.
- "ln -s target linkname" — Create a symbolic link.
- "alias" — Create or display command shortcuts.

Text Processing

- "wc -l file.txt" — Count lines.
- "wc -w file.txt" — Count words.
- "wc -c file.txt" — Count bytes.
- "sort file.txt" — Sort lines.
- "sort -r file.txt" — Sort lines in reverse order.
- "sort -n file.txt" — Sort numerically.
- "head file.txt" — Display the first lines.
- "tail file.txt" — Display the last lines.
- "grep "word" file.txt" — Search for matching text.
- "grep -i "word" file.txt" — Search without case sensitivity.
- "grep -v "word" file.txt" — Display lines that do not match.

📅 Day 3 — Processes, Storage and Networking

Process Management

- "top" — Monitor running processes interactively.
- "ps" — Display process information.
- "ps aux" — List processes with detailed information.
- "nohup command &" — Run a command so it can continue after terminal logout, subject to its environment.

Storage and Memory

- "df -h" — Display filesystem disk space in readable units.
- "free -h" — Display memory usage in readable units.

Downloading and Compression

- "wget URL" — Download a file from a URL.
- "zip archive.zip file.txt" — Create a ZIP archive.
- "unzip archive.zip" — Extract a ZIP archive.
- "tar -czvf archive.tar.gz directory/" — Create a compressed tar archive.
- "tar -xzvf archive.tar.gz" — Extract a compressed tar archive.

Remote Connections

- "ssh user@host" — Connect to a remote computer securely.
- "scp file user@host:/path/" — Copy a file to a remote computer securely.
- "ifconfig" — Display or configure network interfaces on systems where the utility is available.

📚 Topics Covered

-  Basic Linux commands
-  Directory navigation
-  Creating and listing files
-  Reading and writing files
-  File permissions
-  Searching and filtering
-  Shell scripting
-  Linux tools for VLSI workflows


📁 Repository Contents

- "README.md" — Project overview and learning progress.
- "linux_notes.md" — Detailed notes and command examples.
- "practice/" — Hands-on exercises and practice files (to be added).

🚀 Future Goals

- Become comfortable with Linux.
- Learn Git and GitHub workflows.
- Start learning Verilog HDL.
- Practice digital design and VLSI-related projects.


Status: Learning in progress
