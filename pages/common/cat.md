# cat

> Print and concatenate files.

- Print the contents of a file to the standard output:

`cat {{file}}`

- Concatenate several files into the target file:

`cat {{file1}} {{file2}} > {{target_file}}`

- Append several files into the target file:

`cat {{file1}} {{file2}} >> {{target_file}}`

- Number all output lines:

`cat -n {{file}}`

- Display non-printable and whitespace characters (with `M-` prefix if non-ASCII):

`cat -vte {{file}}`

- If you only want to add line numbers to lines that have text, you can use the -b argument.

`cat -b {{file}}`