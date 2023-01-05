# BigFileSymbolicLinks
 Modify bmap() so that it implements a doubly-indirect block, in addition to direct blocks and a singly-indirect block and implement the symlink(char *target, char *path) system call, which creates a new symbolic link at linkpath that refers to file named by target.

# How to extract BigFileSymbolicLinks.tar
 1. Open the terminal
 2. Make the current directory to where BigFileSymbolicLinks.tar is
 3. Extract the tar
 ```
 tar -xvf BigFileSymbolicLinks.tar
 ```

# How to run Big File in xv6
 1. In the same terminal, make the current directory to ```\xv6```
 2. Run xv6 with ```make qemu```
 3. Once everything compiles, type ```bigfile```


# How to run Big File in xv6
 1. In the same terminal, make the current directory to ```\xv6```
 2. Run xv6 with ```make qemu```
 3. Once everything compiles, type ```symlinktest```