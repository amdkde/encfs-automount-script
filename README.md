encfs-automount-script
======================

Bash script with a little C program for automount encfs encrypted devices

To use:

Assign the variables with your devices paths in the bash script file.

Write your encfs key, replacing the YourEncfsKey text, in pwd.c file as described: 

strcpy(pwd,"YourEncfsKey");

Define the long of your key in integers numbers replacing the YourEncfsKeyLongInIntegers text:

char pwd [YourEncfsKeyLongInIntegers];

Compile the program (with gcc, for example) creating the PWD program using in the bash script:

gcc pwd.c -o PWD

And now you can use the bash script
