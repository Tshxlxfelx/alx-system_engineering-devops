ls='rm*' - creates an alias
echo "hello $(whoami)!" - prints hello user, where user is the current user
export PATH=$PATH:/action - making a certain directory the last directory shell looks into for a program
IFS=':' read -ra dirs <<< $PATH
printenv - list global variables
set - list local variables
