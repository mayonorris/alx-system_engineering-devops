su betty : switches the current user to the user betty

whoami   : prints the effective username of the current user.

groups   : prints all the groups the current user is part of

chown betty hello : change the owner of the file hello to betty

touch hello : creates an empty file named hello

chmod u+x hello  : adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

chmod ug+x,o+r hello  : a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

chmod ugo+x hello :  script that adds execution permission to the owner, the group owner and the other users, to the file hello

chmod 007  hello : sets the permission to the file hello as follows:

    Owner: no permission at all
    Group: no permission at all
    Other users: all the permissions

chmod 753 hello : script that sets the mode of the file hello to this:

    -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
   
