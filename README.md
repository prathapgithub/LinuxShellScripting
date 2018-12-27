# LinuxShellScripting

Use '$#' to grab the number of arguments

Example:

if [ $# -ne 2 ]; then

   usage;
   
fi
# -----------------------------------------------------------------------------------------
$? provides return code of last executed command
0-if the last command is success
1-if the last command is fail
# ------------------------------------------------------------------------------------------
