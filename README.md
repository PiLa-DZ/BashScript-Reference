# BashScript-Reference
1.
	``` sh
	echo $SHELL
	```
	> Output: **/bin/bash**
1.
	``` sh
	bash app.sh
	```
1.
	``` sh
	#!/bin/bash
	```
1.
	``` sh
	chmod u+x app.sh
	```
--------------------------------------------------------------------
1.
	``` sh
	$VARIABLE_NAME
	```
1.
	``` sh
	read
	```
1.
	``` sh
	if   [ $X = $Y ]; then
       	    # Do Something
	elif [ $X = $Z ]; then
       	    # Do Something
	else
       	    # Do Something
	fi

	```
1.
	``` sh
	case $X in
	    $Y | $Z)
		# Do Somethisg
		;;
	    $A)
		# Do Somethisg
		;;
	    *)
		# Do Somethisg
		;;
	esac

	```
1.
	``` sh
	MY_ARRAY=(one two three)
	```
	``` sh
	echo ${MY_ARRAY[@]}
	```
	> Output: **one** **two** **three**
	``` sh
	echo ${MY_ARRAY[0]}
	```
	> Output: **one** 
	``` sh
	echo ${MY_ARRAY[1]}
	```
	> Output: **two**
	``` sh
	echo ${MY_ARRAY[2]}
	```
	> Output: **three**

---
### Learn From Youtube :blush:
[Bash Scripting Tutorial](https://www.youtube.com/watch?v=2733cRPudvI&list=PLT98CRl2KxKGj-VKtApD8-zCqSaN2mD4w)
