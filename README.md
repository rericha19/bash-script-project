# bash-script-project
In directories specified via arguments it finds directores, in which the sum of the number of lines of all regular files is highest.

Only files directly in the directory count into the sum. 

If used with the -w argument, it considers sum of words, if used with the -c argument, it considers sum of characters. 

zadanie01 Samuel Rericha
Usage: z1.sh [-h] [-c] [-w] [path(s) (optional)]
The script finds (a) directory/directories, in which the sum
of the number of lines found in regular files is the highest.
It searches in directories provided as arguments,
or in the current directory if none are provided.

-h: print help (you're reading it now)
-c: when ran with this argument, instead of the number
    of lines it considers the number of characters
-w: when ran with this argument, instead of the number
    of lines it considers the number of words
