Learned about Linus OS and how it is UNIX based and how it was first launced in '91.
Ubuntu is another form.
Very lightweight.
No GUI.

Some important commands:
ls - list folders and files in current directory
cd - change directory; know path and know that path always starts with root in this filesystem (/)
echo - bscly output
cat - concatenate
whoami - shows whos logged on
pwd - print working directory
find - command to find any file with a file type or filename. SYNTAX: find name *.txt (* lists all file with file type .txt)
grep - used to search content we're looking for within files. SYNTAX: grep "ABADA" /etc/ (Use -R to find recursively if information might be in multiple files)

Operators:
- & - execute command in the background
- && - execute two commands i.e 'command1 && command2' (command2 will only run if 1 succeeds)
- > - output redirectory i.e write to file (echo Hi > file)
- >> - same but appends (echo wassup >> file)

Output w. above > and >> commands:
cat file
Hi
wassup
