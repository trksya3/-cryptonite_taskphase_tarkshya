First, read the man page for the man command by typing:
run -  man man
see various options for using the man command. 
One of the important ones for searching the man page database is the -k option, which allows you to search the "whatis" database for man pages containing specific keywords.
Use the man -k command to search for the hidden man page. Since the challenge is related to the /challenge/challenge program,
run -  man -k challenge
This will list all the man pages related to "challenge," including the hidden one , i.e. gdnovfyqzv
run - man gdnovfyqzv
we get --gdnovf NUM
              print the flag if NUM is 793
this reveal the option needed to retrieve the flag. Then, you can run /challenge/challenge with the correct option to get the flag
run - /challenge/challenge --gdnovf 793
we get the flag as - pwn.college{gTJ7Pdn9ovCBLDIIfyqzvtdBd37.dZTM4QDL3MTM1czW}
