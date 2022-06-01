0. alias ls="rm *"

01. echo "hello $USER"

02. PATH=$PATH:/action

03. echo $PATH | tr ":" "\n" | wc -l

04. printenv

05. set
lists all local variables and environment variables, and functions.

06. BEST="School"
creates a new local variable.

07. export BEST="School"

echo $(($((TRUEKNOWLEDGE + 128))))
8.prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.

9. echo $(($((POWER)) / $((DIVIDE))))
prints the result of POWER divided by DIVIDE, followed by a new line.


10. echo $(($((BREATH)) ** $((LOVE))))
displays the result of BREATH to the power LOVE

11. echo $((2#$BINARY))
converts a number from base 2 to base 10.

12. echo {a..z}{a..} | tr ' ' '\n' | grep -v oo
prints all possible combinations of two letters, except oo
