# Udobn Shell

Udobn Shell is a custom interactive shell that provides various useful commands and features. It supports basic system information display, file manipulation, gaming (Snake and Tetris), autocompletion, and much more.

## Features

- **System Information**: View details like hostname, OS, kernel version, uptime, disk space, and memory usage.
- **File Operations**: Create, remove, and edit files with commands like `touch`, `rm`, `nano`, and `vim`.
- **Autocompletion**: Tab-based autocompletion for commands and directories.
- **Games**: Play games like Snake and Tetris within the shell.
- **Tutorials**: Open a local or online tutorial HTML page.
- **External Links**: Open useful websites like GitHub, YouTube, Telegram, and Notion.
- **Directory Navigation**: Simplified navigation to specific directories like a coding directory (`study` command).

## Commands

Here are the available commands in Udobn Shell:

- `help`: Show a list of available commands.
- `sysinfo`: Display system information (hostname, OS, kernel, uptime, etc.).
- `date`: Show the current date and time.
- `greet [name]`: Greet the user (optionally with a custom name).
- `clear`: Clear the terminal screen.
- `exit` or `quit`: Exit the shell.
- `cd [dir]`: Change the current directory.
- `ls`: List files and directories.
- `pwd`: Display the current working directory.
- `uptime`: Show system uptime.
- `whoami`: Display the current user.
- `hostname`: Show the system's hostname.
- `df`: Show disk space usage.
- `free`: Show memory usage.
- `study`: Navigate to the coding directory (`~/Documents/coding`).
- `snake`: Start the Snake game.
- `tetris`: Start the Tetris game (via Bastet).
- `github`: Open GitHub in the default browser.
- `youtube`: Open YouTube in the default browser.
- `telegram`: Open Telegram (if installed).
- `vscode`: Open Visual Studio Code (if installed).
- `notion`: Open Notion in the default browser.
- `asmemu`: Open Assembly Emulator in the browser.
- `nano [file]`: Open a file in the nano text editor.
- `vim [file]`: Open a file in the vim text editor.
- `touch [file]`: Create a new file.
- `rm [file]`: Delete a file.
- `tutorial`: Open the local or online tutorial (`main.html`).

## Installation

To use Udobn Shell, you can either clone the repository or copy the script into your system. Ensure that required commands (like `nsnake`, `bastet`, `brew`, and `apt-get`) are installed on your machine for the respective functionalities (games, package management, etc.).

### Dependencies

- `nsnake` for Snake game (Linux/macOS)
- `bastet` for Tetris game (Linux/macOS)
- `brew` (macOS package manager)
- `apt-get` (Linux package manager)

## Setup

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/udobn_shell.git
    cd udobn_shell
    ```

2. **Make the script executable**:

    ```bash
    chmod +x udobn_shell.sh
    ```

3. **Run the shell**:

    ```bash
    ./udobn_shell.sh
    ```

## Usage

Once the script is running, you can type commands interactively. Use tab autocompletion to quickly access available commands and directories.

For example:
- Type `cd` and press Tab to autocomplete directories.
- Type `nano` and press Tab to autocomplete filenames.
  
The shell also supports manual command autocompletion, providing suggestions based on what you've typed.
