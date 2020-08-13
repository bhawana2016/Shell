#This file contains the some key points for shell scripting.
#!/bin/sh -> path to interpreter
  Interpreter can be sh, bash, ksh etc.
NAME="Bhawana"  # There should be no space in both sides of '=' sign
readonly var cannot be changed.
Newly created file doesn't have executable permission. It can be made executable by "chmod +x FILENAME"
Various Permissions:
    0 : Nothing
    1 : Execute (x)
    2 : Write (w)
    3 : 1 + 2 : xw
    4 : Read (r)
    5 : 4 + 1 : xr
    6 : 4 + 2 : wr
    7 : 4 + 2 + 1 : xwr
 
