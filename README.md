# LinuxShellScripting
# --------------------------------------------------------------
Use '$#' to grab the number of arguments

Example:

if [ $# -ne 2 ]; then

   usage;
   
fi
# --------------------------------------------------------------
# --------------------------------------------------------------
$? provides return code of last executed command
0-if the last command is success
1-if the last command is fail
# ---------------------------------------------------------------
# Bash Shell Find Out If a Variable Is Empty Or Not

You can pass the -z option to the if command or conditional expression. If the length of STRING is zero, variable ($var) is empty. The test command is used to check file types and compare values. This page shows how to find out if a bash shell variable is empty or not using the test command.

To find out if a bash variable is empty:

Return true if a bash variable is unset or set to the empty string: if [ -z "$var" ];

Another option: [ -z "$var" ] && echo "Empty"

Determine if a bash variable is empty: [[ ! -z "$var" ]] && echo "Not empty" || echo "Empty"

Bash Shell Find Out If a Variable Is Empty Or Not

Let us see syntax and examples in details. The syntax is as follows for if command:


if [ -z "$var" ]

then

      echo "\$var is empty"
      
else

      echo "\$var is NOT empty"
      
fi

OR

if test -z "$var" 

then

      echo "\$var is empty"
      
else

      echo "\$var is NOT empty"
      
fi

