This is a program to look through directories to find magic words. It will look until I tell it to stop with a keyboard interrupt, it will search within a file directory we are creating and then going from there.

This program is specifically set to run on python3 with the signal handler, so when you are testing it please run python3.

The way to run the program is as follows:

python3 dirwatcher.py DIRECTORY MAGICWORD


DIRECTORY can be any directory to be input and it should scan through any files. If the directory has a .txt file or files in it, the program will go through those files and look for the MAGIC WORD

The MAGICWORD is any file which is input for the user.