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

Printing local variables : 
	
	#!/bin/bash
	set 

Create local variable :

	#!/bin/bash
	BEST =School

Here is the script to Create global variable 

	#!/bin/bash
	export BEST=School


script that prints the result of the addition of 128 with the value stored in the environment variable:

	#!/bin/bash
	echo $(($TRUEKNOWLEDGE+128)) 



