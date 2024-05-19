# JavaTerminalEmulator

A basic terminal emulator written in Java that supports a variety of common shell commands. This project aims to simulate a Unix-like command-line interface with functionalities such as navigating directories, manipulating files, and maintaining command history.

## Features

- **pwd**: Prints the current working directory.
- **cd**: Changes the current directory.
- **mkdir**: Creates new directories.
- **rmdir**: Removes empty directories.
- **echo**: Prints a message to the console.
- **cat**: Concatenates and displays file content.
- **cp**: Copies files and directories.
- **ls**: Lists directory contents.
- **touch**: Creates an empty file or updates the access and modification times of an existing file.
- **rm**: Removes files.
- **history**: Displays the list of executed commands.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- Git (for cloning the repository)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/JavaTerminalEmulator.git
    cd JavaTerminalEmulator
    ```

2. Compile the Java files:

    ```bash
    javac *.java
    ```

3. Run the terminal emulator:

    ```bash
    java Terminal
    ```

## Usage

Once the emulator is running, you can use the following commands:

- **pwd**: Type `pwd` and press Enter to print the current working directory.

    ```bash
    > pwd
    ```

- **cd**: Change the current directory. Use `cd ..` to move up one directory, or `cd <directory>` to move into a specific directory.

    ```bash
    > cd ..
    > cd myFolder
    ```

- **mkdir**: Create one or more directories.

    ```bash
    > mkdir newFolder
    ```

- **rmdir**: Remove an empty directory or all empty directories if `*` is used.

    ```bash
    > rmdir emptyFolder
    > rmdir *
    ```

- **echo**: Print a message to the console.

    ```bash
    > echo "Hello, World!"
    ```

- **cat**: Display the contents of one or two files.

    ```bash
    > cat file1.txt
    > cat file1.txt file2.txt
    ```

- **cp**: Copy files or directories (use `cp r <sourceDir> <destDir>` for directories).

    ```bash
    > cp file1.txt copyOfFile1.txt
    > cp r sourceDir destinationDir
    ```

- **ls**: List the contents of the current directory. Use `ls r` for reversed order.

    ```bash
    > ls
    > ls r
    ```

- **touch**: Create a new empty file.

    ```bash
    > touch newFile.txt
    ```

- **rm**: Remove a file.

    ```bash
    > rm unwantedFile.txt
    ```

- **history**: Show the history of executed commands.

    ```bash
    > history
    ```

- **exit**: Exit the terminal emulator.

    ```bash
    > exit
    ```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements, bug fixes, or documentation improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

This project is inspired by the need to understand basic shell commands and file manipulation using Java.


