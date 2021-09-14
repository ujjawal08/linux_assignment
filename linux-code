#Exercise 1: Write a shell script that prints “Shell Scripting is Fun!” on the screen


echo "Shell Scripting is Fun!"

#Exercise 2:  Modify the shell script from exercise 1 to include a variable. The variable will hold the contents of the message “Shell Scripting is Fun!”


sentance=Shell Scripting is Fun!
echo $sentance

#Exercise 3: Store the output of the command “hostname” in a variable. Display “This script is running on _.” where “_” is the output of the “hostname” command.


h=$HOSTNAME
echo "This script is running on $h"

#Exercise 4: Write a shell script that displays “man”,”bear”,”pig”,”dog”,”cat”,and “sheep” on the screen with each appearing on a separate line. Try to do this in as few lines as possible.


A="human pig dog cat sheep deer bear"

for i in $A
do
       echo "$i"
done

#Exercise 5: Write a shell script that displays, “This script will exit with 0 exit status.” Be sure that the script does indeed exit with a 0 exit status.


echo "This script will exit with 0 status."

#Exercise 6: Write a shell script that consists of a function that displays the number of files in the present working directory. Name this function “file_count” and call it in your script. If you use variable in your function, remember to make it a local variable.

function count() {
    local NOF=$(ls -l | wc -l)
    echo The number of files are "$NOF"
}
count
exit 0
