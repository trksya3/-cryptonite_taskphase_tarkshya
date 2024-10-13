tee command basically stores the output and save it to  any given file of our choice , so that we can inspect it later(if needed).
run the command - /challenge/pwn | tee intercept | /challenge/college
run - cat intercept 
we get our secret code as - --secret IUtvZsA9
run - /challenge/pwn --secret IUtvZsA9 | /challenge/college
get the flag  as - pwn.college{IUtvZsA9F_Hcp1IRsNOQ0gUdoEx.dFjM5QDL3MTM1czW}
