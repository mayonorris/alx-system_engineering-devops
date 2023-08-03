The first line #!/bin/bash, tells the shell that this is a Bash shell script.
pwd, gets the absolute path of the current working directory 

ls Display the contents list of your current directory.

cd ~: bring to the home directory 

ls -l : Display current directory contents in a long forma

ls -la : Display current directory contents, including hidden files (starting with .). Use the long format.

ls -lna : Display current directory content: 
  Long format, 
  with user and group IDs displayed numerically, 
  And hidden files (starting with .)

mkdir /tmp/my_first_directory : reates a directory named my_first_directory in the /tmp/ directory.

mv /tmp/betty /tmp/my_first_directory : Move the file betty from /tmp/ to /tmp/my_first_directory. 

rm /tmp/my_first_directory/betty : delete the betty file from the /tmp/my_first_directory directory  

rm -r /tmp/my_first_directory: removing directory

cd - : back to the previous directory 

ls -al . .. /boot : Llists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

file /tmp/iamafile : prints the file  iamafile type 

ln -s /bin/ls __ls__ : Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.

cp -un *.html ../ : Copies HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

mv [[:upper:]]* /tmp/u : moves all files beginning with an uppercase letter to the directory /tmp/u.

rm *~:  Deletes all files in the current working directory that end with the character ~. 

mkdir -p welcome/to/school : creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.

ls -amvp : a command that lists all the files and directories of the current directory, separated by commas (,).


