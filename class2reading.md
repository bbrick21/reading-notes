# Summary of learnings about using a terminal
-----
## What is a terminal? 
A terminal is an interface to your computer that is controlled via text, rather than a point and click experience like your Graphical User Interface (Windows or MacOS). 

## How it works
* When you first open a terminal, you are presented with a prompt. Generally, you will follow a prompt with 2 things: a command and a command line argument. 
* An examples is ``ls /etc``, where ls is the command, and /etc is the argument
* After entering both a command and a command line argument on line 1, the next few lines are usually output from running the command. Some commands do not display any text, instead just running their commands and only displaying text upon error. 
* After the terminal has run a command and is ready for you to run another command, a prompt will be presented beneath the output from the previous command. 
* Within each terminal is a **shell**. The shell is the program where text is output from the terminal. One common shell is Bash.

## Paths
When referring to a specific file or directory, you are actually referring to the path it takes to get there. 
* File systems are hierarchical structures. At the core is a **root directory** which is shown through a single forward slash ``/``.
* An absolute path is a path displayed by the terminal that will be the same no matter which directory you are currenty in, such as ``/home/bryce/documents``. This means that running ``ls /home/bryce/documents`` will display the same results regardles of current location.
* A relative path is one that is dependent on current location. For example, running the command ``ls Documents`` will 

## Commands
There are basic commands that serve as a foundation of using the terminal:
* ``pwd`` is a command that requires no argument. This will display the location you are accessing within the computer.
* ``ls`` also requires no argument. This command will display *what is in* the location you are accessing. 
> There are also some arguments we can use within the ls command.
> ``ls -1`` is a single command with a space between the "ls" and "-1". This will display a *long listing* which includes information like normal file or directory, owner of the file, and group the file belongs to. 
> ``ls /etc`` is a line with both a command and an argument. The argument tells the computer to list the current directory's *contents* instead of the current directory.
> 
