 The first line #!/bin/bash, tells the shell that this is a Bash shell script.
$(pwd), gets the absolute path of the current working directory and echo print the working directory.
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

ls -al . .. /boot : Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

file /tmp/iamafile : prints the file  iamafile type  
