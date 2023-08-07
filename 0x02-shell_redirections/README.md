#This is the readme about shell I/O  redirection#
echo "Hello, World": prints "Hello, World"
 
echo "\ "(Ôo)'" : displays  confused smiley

echo cat /etc/passwd : displays the content of the /etc/passwd file 

cat /etc/passwd  /etc/hosts : displays the contents of both /etc/passwd and /etc/hosts files 

tail  /etc/passwd : the last ten lines of the file /etc/passwd  

head  /etc/passwd : the first ten lines of the file /etc/passwd

head -n 3 iacta |tail -n 1 : displays the third line of the file iacta

'\*\\'\''"Best School"\'\''\\*$\?\*\*\*\*\*:)': creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line. 

ls -la ls_cwd_content : writes into the file ls_cwd_content the result of the command ls -la.

tail -n 1 iacta | cat >> iacta: Duplicates the last line of iacta file 

find . -name "*.js" -type f -delete: deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

find . -mindepth 1 -type d | wc -l : counts the number of directories and sub-directories in the current directory.

The current and parent directories should not be taken into account,
Hidden directories should be counted

ls -t | head : displays the ten newest files il the current directory

sort | uniq -u :  takes a list of words as input and prints only words that appear exactly once.

egrep root /etc/passwd : Display lines containing the pattern “root” from the file /etc/passwd 
