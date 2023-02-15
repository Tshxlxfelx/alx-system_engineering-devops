ls='rm*' - creates an alias
echo "hello $(whoami)!" - prints hello user, where user is the current user
export PATH=$PATH:/action - making a certain directory the last directory shell looks into for a program
IFS=':' read -ra dirs <<< $PATH
printenv - list global variables
set - list local variables
BEST="School" - create local variable
exho $((128+ $TRUEKNOWLEDGE)) - prints number plus variable stored
echo $(($POWER/$DIVIDE)) - divided variables followed by a line
echo $(($BREATH**$LOVE)) - variable to the power variable followed by a new line
echo $((2#$BINARY)) - converts njumber from base 2 to 10
