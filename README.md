Project Description: Simple Shell

The objective of this project is to develop an intuitive shell that provides users with an interface to interact with a Unix-based operating system.

The shell is crafted using a high-level programming language and designed to offer a user-friendly experience.

Key Features:

The Simple Shell encompasses the following features:

- Simple Shell 0.1: An interpreter for Unix command lines.
- Simple Shell 0.2: Capability to manage command lines with arguments.
- Simple Shell 0.4: Introduction of the built-in exit command, facilitating shell exit.

  Usage: exit.

- Simple Shell 1.0: Integration of the built-in env command, which displays the current environment.
- Simple Shell 0.4.1: Handling of arguments for the exit built-in command.

  Usage: exit status, where status is an integer for shell exit. Additionally, implementation of setenv and unsetenv commands.

- setenv initializes or modifies environment variables. Command format: setenv VARIABLE VALUE.

- cd: Incorporation of the cd built-in command. This alters the current process directory. Command format: cd [DIRECTORY]. If no argument is supplied, cd interprets as cd $HOME. Handling of the command cd - is a requirement.

- alias: Implementation of the alias built-in command.

  Usage: alias [name[='value'] ...]. The command alias displays aliases in the form name='value', with the option to specify name or multiple names for more detailed information. It's also possible to define aliases using name='value' syntax.

- Comments: Management of comments (#).File Input: Usage: simple_shell [filename].

Using the Simple Shell:

To utilize the Simple Shell, adhere to these steps:

1. Clone the repository or download the source code.
2. Compile the program with the command: gcc -Wall -Werror -Wextra -pedantic *.c -o hsh.
3. Run the shell using: ./hsh.
4. To execute commands from a file, use: ./hsh filename.

Author:

This repository was established as part of the ALX Software Engineering program coursework.

Ohene Nana Kwame Akuffo: Ohenekakuffo@gmail.com
Morris Gborie Ampomah:gborieampomah@gmail.com
