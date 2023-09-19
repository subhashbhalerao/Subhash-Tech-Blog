How can you get access to a Linux system?

1. You can have a Linux system at your place
2. You can access a Linux system through internet
3. On windows systems, install Cygwin, MinGW
4. On Windows 10 and Windows 11, install Windows Subsystem for Linux (WSL)
5. On Windows, install Oracle Virtualbox to install Linux as virtual machine

How to start practicing Linux commands?

Answer: For entering Linux commands on Linux systems, you have a program called Terminal. Open the Terminal program by searching it in graphical Linux environment or press 'Ctrl + Alt + T' keys.

Where to start Linux commands?

Answer: After you opened Terminal program, you see $ prompt, you start typing your Linux commands there and to press enter key to execute the command. 
e.g. subhash@my-linux-pc:~$ ls

List file and folders - 

ls - show lising of files and folders in the current directory

common arguments to ls command- 
    -l long listing
    -a shows all files and folders including hidden, (starting with .)
    -C shows files and folders in columns view
    -m shows all files and folders in comma seperated form
    --group-directories-first   shows folders first, then files
    -h show file sizes in MB, GB etc
    -i show inode of each file and folder
    -r shows files and folder in reverse order
    -R shows contents of all files and folder
    -t show files and folders as newest first
    -1 show files and folders as one line per entry
    
    e.g. ls -l, ls -lt, ls -1, ls -r, ls -R, ls -t etc