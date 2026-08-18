# Bandit Level 12 -> Level 13

## Level Goal
The password for the next level is stored in the file data.txt, which is a hexdump of a file that has been repeatedly compressed. For this level it may be useful to create a directory under /tmp in which you can work. Use mkdir with a hard to guess directory name. Or better, use the command “mktemp -d”. Then copy the datafile using cp, and rename it using mv (read the manpages!)

## Key concepts learnt
1. `Hex dumps` show binary data in a readable hexadecimal format.`xxd -r` reverses a hex dump back into its original binary form.
2. `file` command tells you what kind of data a file contains.(text, binary, gzip, tar).
3. `mktemp -d` creates a temporary directory with a unique name.
4. `cp` copies files from one location to another.
5. `mv` moves or renames files.
6. `gzip` and `bzip2` are compression formats.
7. `tar` is an archiving tool that bundles multiple files into one .tar archive.
   
