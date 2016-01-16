echo
===
This is a rewrite of Linux's 'echo' program in Assembly that is 98% smaller (751 bytes vs 31296 bytes).
There are two small things that are different, but by and large they should function the same:
* There is no "-e" argument.
* echo firstword secondword will only echo 'firstword', to print more than one word you must use speech marks like so: echo "firstword secondword". I'm not fixing this because you should be enclosing your string arguments in speech marks anyways, if you're not following good practice it's not my problem.