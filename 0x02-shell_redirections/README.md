0. echo 'Hello, World'
prints “Hello, World”, followed by a new line to the standard output.
1. echo "\"(Ôo)'" 
displays a confused smiley "(Ôo)'
2. cat /etc/passwd 
Display the content of the /etc/passwd file
3. cat /etc/passwd /etc/hosts
Display the content of /etc/passwd and /etc/hosts
4. tail -n 10 /etc/passwd
Display the last 10 lines of /etc/passwd
5. head -n 10 /etc/passwd
Display the first 10 lines of /etc/passwd
6. head -n 3 iacta | tail -n 1
Write a script that displays the third line of the file iacta.
7. echo 'Best School' > "\*\\\'\"Best School\"\'\\\*$\?\*\*\*\*\*:)"
creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
8. ls -al > ls_cwd_content
8-cwd_state
9. 9-duplicate_last_line
tail -1 < iacta >> iacta
duplicates the last line of the file iacta
10. find -name "*.js" -type f -delete
deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
11. find . -type d ! -path . -print | wc -l
counts the number of directories and sub-directories in the current directory.
12. ls -1t | head -10
displays the 10 newest files in the current directory.
