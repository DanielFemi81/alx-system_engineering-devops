0. alias ls="rm *"
creates an alias 

01. echo "hello $USER"
prints hello user, where user is the current Linux user.

02. PATH=$PATH:/action
Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.

03. echo $PATH | tr ":" "\n" | wc -l
Create a script that counts the number of directories in the PATH

04. printenv
Create a script that lists environment variables

05. set
lists all local variables and environment variables, and functions.

06. BEST="School"
creates a new local variable.

07. export BEST="School"
Create a script that creates a new global variable.

08. echo $(($((TRUEKNOWLEDGE + 128))))
prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.

9. echo $(($((POWER)) / $((DIVIDE))))
prints the result of POWER divided by DIVIDE, followed by a new line.


10. echo $(($((BREATH)) ** $((LOVE))))
displays the result of BREATH to the power LOVE

11. echo $((2#$BINARY))
converts a number from base 2 to base 10.

12. echo {a..z}{a..} | tr ' ' '\n' | grep -v oo
prints all possible combinations of two letters, except oo

13. printf "%0.2f\n" $NUM
prints a number with two decimal places, followed by a new line.

14. printf "%x\n" $DECIMAL
converts a number from base 10 to base 16.

13. tr 'A-Za-z' 'N-ZA-Mn-za-m'
encodes and decodes text using the rot13 encryption. Assume ASCII
16. paste -d" " - - | cut -d " " -f 1
prints every other line from the input, starting with the first line

13. printf "%o\n" $(($((5#$(echo $WATER | tr water 01234))) $((5#$(echo $STIR | tr stir 01234))))) | tr 01234567 bestchol
