# Helpful Terminal Commands

## Table of Contents
- [Windows Commands](#windows-commands)
  - [General Commands](#general-commands)
  - [System Information](#system-information)
  - [File and Text Manipulation](#file-and-text-manipulation)
  - [Developer-Specific Commands](#developer-specific-commands)
    - [Git Commands](#git-commands)
    - [Node.js & NPM Commands](#nodejs--npm-commands)
    - [Python Commands](#python-commands)
    - [Docker Commands](#docker-commands)
  - [Package Managers](#package-managers)
    - [Chocolatey](#chocolatey)
    - [Windows Package Manager (winget)](#windows-package-manager-winget)
  - [Miscellaneous](#miscellaneous)
- [Bash Terminal Commands](#bash-terminal-commands)
  - [General Commands](#general-commands-1)
  - [System Information](#system-information-1)
  - [File and Text Manipulation](#file-and-text-manipulation-1)
  - [Developer-Specific Commands](#developer-specific-commands-1)
    - [Git Commands](#git-commands-1)
    - [Node.js & NPM Commands](#nodejs--npm-commands-1)
    - [Python Commands](#python-commands-1)
    - [Docker Commands](#docker-commands-1)

## Windows Commands

### General Commands
```sh
cls       # Clear the terminal screen
dir       # List files and directories in the current directory
tree      # Show directory structure
cd <dir>  # Change directory
cd ..     # Move up one directory level
mkdir <name> # Create a new directory
del <file> # Delete a file
rmdir /s <dir> # Delete a directory and its contents
copy <src> <dest> # Copy files
move <src> <dest> # Move files
```

### System Information
```sh
systeminfo  # Display system details
ipconfig    # Show network configuration
ipconfig /flushdns  # Clear DNS cache
tasklist    # List running processes
taskkill /PID <pid> /F  # Kill a process by its ID
```

### File and Text Manipulation
```sh
type <file>  # Display file contents
find "text" <file>  # Search for text in a file
```

### Developer-Specific Commands
#### Git Commands
```sh
git init           # Initialize a new Git repository
git clone <repo>  # Clone a repository
git status        # Check the status of the repository
git add <file>    # Stage a file
git commit -m "message"  # Commit changes
git push origin main  # Push changes to remote repo
git pull origin main  # Pull latest changes
```

#### Node.js & NPM Commands
```sh
node -v       # Check Node.js version
npm -v        # Check npm version
npm install   # Install dependencies
npm start     # Start the application
npm run build # Build the application
```

#### Python Commands
```sh
python --version  # Check Python version
python script.py  # Run a Python script
pip install <package>  # Install a Python package
```

#### Docker Commands
```sh
docker ps         # List running containers
docker images     # List available images
docker build -t <name> .  # Build an image
docker run -d -p 8080:80 <image>  # Run a container
```

### Package Managers
#### Chocolatey
```sh
choco install <package>  # Install a package
choco upgrade <package>  # Upgrade a package
```

#### Windows Package Manager (winget)
```sh
winget install <package>  # Install a package
winget upgrade --all      # Upgrade all installed packages
```

### Miscellaneous
```sh
time /t  # Show current time
date /t  # Show current date
shutdown /s /t 60  # Shutdown PC in 60 seconds
echo "Hello, World!"  # Print text to terminal
```

## Bash Terminal Commands

### General Commands
```sh
clear     # Clear the terminal screen
ls        # List files and directories
pwd       # Print working directory
cd <dir>  # Change directory
cd ..     # Move up one directory level
mkdir <name> # Create a new directory
rm <file> # Delete a file
rm -r <dir> # Delete a directory and its contents
cp <src> <dest> # Copy files
mv <src> <dest> # Move files
```

### System Information
```sh
uname -a  # Show system details
ifconfig  # Show network configuration
ps aux    # List running processes
kill <pid>  # Kill a process by its ID
```

### File and Text Manipulation
```sh
cat <file>  # Display file contents
grep "text" <file>  # Search for text in a file
```

### Developer-Specific Commands
#### Git Commands
```sh
git init           # Initialize a new Git repository
git clone <repo>  # Clone a repository
git status        # Check the status of the repository
git add <file>    # Stage a file
git commit -m "message"  # Commit changes
git push origin master  # Push changes to remote repo
git pull origin master  # Pull latest changes
```

#### Node.js & NPM Commands
```sh
node -v       # Check Node.js version
npm -v        # Check npm version
npm install   # Install dependencies
npm start     # Start the application
npm run build # Build the application
```

#### Python Commands
```sh
python3 --version  # Check Python version
python3 script.py  # Run a Python script
pip3 install <package>  # Install a Python package
```

#### Docker Commands
```sh
docker ps         # List running containers
docker images     # List available images
docker build -t <name> .  # Build an image
docker run -d -p 8080:80 <image>  # Run a container
```

