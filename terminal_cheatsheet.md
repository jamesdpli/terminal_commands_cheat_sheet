# Unix Command Line Tips and Tricks
 
 ### Terminals, also known as command lines or consoles, allow us to accomplish and automate tasks on a computer without the use of a graphical user interface.

 - `cd` allows you to change directory 
 - `cd ..` goes up a directory
 - `cd -` returns to the last directory you were in 
 - `mkdir` creates a directory with the name you specify, for example mkdir my_folder will create a foler called "my_folder"
 - `touch` creates a file with a specific name, for example touch my_file will create a file called "my_file"
 - `pwd` prints file path
 - `ls` lists the content of the current directory
 - `ls -a` lists all content including hidden files
 - `clear` clears the terminal, if you want to see what you have cleared you can scroll up
 - `mv` an interesting command with multiple uses: 
    1. `mv my_file.txt my_file_1.txt` this will rename my_file.txt to my_file_1.txt
    2. `mv my_file.txt ~/btna/coursework/week_01` will move the file from where it is to the specified file path in the second argument
 - `cp` will copy a file this is done like this `cp file_1.txt ~/bnta` this will copy the file "file_1.txt" into the bnta directory
 - `rm` will remove a named file or folder ... **BE CAREFUL WITH THIS ONE**
 ---
 ## Flags
 ### There are many different flags used in the unix command line, bellow you will find some commonly used ones.
 - `-a` means all for example ls -a lists all files and folders in you rcurrent folder **including the hidden ones**.
 - `-f` means to force an action ... **BE CARFUL WHEN FORCING `rm` ACTIONS**
 - `-m` means message, think about when you use `git commit -m"your message here"` the m allows you to write a message.
 
 *There are many more flags than listed, this is a brief introduction to some of the more common ones*

 ---
 
 *You can use tab to autocomplete a the line*

 *You can use the up and down arrows on the keyboard to* ***cycle through previous commands***