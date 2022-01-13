# Summary of Text Editor learnings
* Text editors are found on most computers. Common examples are Word and Google Docs. While some text editors are designed for sentence writing, others are designed for writing code.
* Code text editors have a few unique features that make them ideal for coding.
* Code Completion - this will help you complete lines of code based on what has already been typed in.
* Syntax highlighting - this highlights pieces of code you have typed in, which can make it easier to identify pieces of code. 
* Shorthand code - some text editors offer ways of writing code faster via shorthand languages.
* Windows by default comes with Notepad, while Mac comes with Text Edit. 
* There are many third party code editors that are free.

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
* A relative path is one that is dependent on current location. For example, running the command ``ls Documents`` will display different contents depending on current location. This will display contents of a folder titled "documents" located within our current location. 
* ``~`` is a shortcut for home directory. This might represent somethng like /Home/Bryce. Therefore, we could type ~/Documents to access the Documents folder within the directory.
* ``.`` is a shortcut for current directory.
* ``..`` is a shortcut for parent directory. This can be used several times in a row (e.g. ``../../documents)

## Commands
There are basic commands that serve as a foundation of using the terminal:
* ``pwd`` is a command that requires no argument. This will display the location you are accessing within the computer.
* ``ls`` also requires no argument. This command will display *what is in* the location you are accessing. 
> There are also some arguments we can use within the ls command.
>> ``ls -1`` is a single command with a space between the "ls" and "-1". This will display a *long listing* which includes information like normal file or directory, owner of the file, and group the file belongs to. 
>>> ``ls /etc`` is a line with both a command and an argument. The argument tells the computer to list the contents of a directory other than the current location, in this case ``/etc``.
* ``cd [location]`` will change directories. If followed up with an argument, it will navigate to that directory. If no argument is included, it will default to the home directory.
* ``Tab`` will autocomplete command lines when there is only one possibility to finish the command. 

## Other notes
* Linux doesn't require name extensions, Windows does
* Linux is Case-sensitive, Windows is not.
* If there is a space in the name you are trying to access, enclose the name using ``' '``. For example ``'My documents'.


[<===Back](README.md)
