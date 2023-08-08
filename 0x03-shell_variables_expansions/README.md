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

script that prints the result of POWER divided by DIVIDE, followed by a new line.

	#!/bin/bash
	echo $(($POWER/$DIVIDE))

script that displays the result of BREATH to the power LOVE
	#!/bin/bash
	echo $(($BREATH**$LOVE))

Convert binary to decimal : 

	#!/bin/bash
	echo $((2#$BINARY))

A  script that prints all possible combinations of two letters, except oo.
	#!/bin/bash
	echo {a..z}{a..z} | tr ' ' '\n' | grep -v oo

A script that prints float 
	
	#!/bin/bash
	printf "%0.2f\n" $NUM


 a script that converts a number from base 10 to base 16: 

	#!/bin/bash
	$(printf "%x" "$DECIMAL")

a script that encodes and decodes text using the rot13 encryption. Assume ASCII.

	#!/bin/bash
	tr 'A-Za-z' 'N-ZA-Mn-za-m'

