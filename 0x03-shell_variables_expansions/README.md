This is a README file about the shell expansion project

Script that creates an alias : name ls; valus rm *

	#!/bin/bash
	alias ls="rm *"

 script that prints hello user, where user is the current Linux user.

	#!/bin/bash 
	echo "hello $USE"

Add /action to the PATH:
	#!/bin/bash
	PATH=$PATH:/action 

Counting directories in the path :

	#!/bin/bash
	echo $PATH | tr ":" "\n" | wc -l

printing all variables in the environnement 

	#!/bin/bash
	printenv


