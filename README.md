# Password Manager

A command-line password manager built in Python that stores account 
credentials locally using JSON file storage.

## Features
- Add passwords for any account or service
- Retrieve saved passwords by account name
- List all saved accounts
- Persistent storage across sessions using JSON
- Basic error handling and input validation

## How It Works
Passwords are stored locally in a `passwords.json` file. Each entry 
contains an account name, username, and password. The file is created 
automatically on first use if it doesn't exist.


## Security Notice
Passwords are currently stored in plain text. This project is intended 
as a demonstration of file handling, data persistence, and CLI design 
in Python — not for real-world secure storage.


## What I Learned
Building this taught me how to work with persistent file storage using 
JSON, which was a step up from projects that only store data while 
running. I learned how to handle files safely — checking if they exist 
before opening them and writing data back cleanly after changes.

I also became aware of the security limitations of plain text storage. 
Storing sensitive data without encryption is a significant vulnerability 
— something I explored further by building an encrypted version on a 
separate branch using a rotating XOR cipher. This made me think about 
the real-world responsibility developers have when handling user data, 
which connects directly to what I learned during CyberFirst Defenders.

## Author
HsBitCoder
