In this challenge, you need to run the /challenge/hack command and duplicate its output as input to both /challenge/the and /challenge/planet. 
we can achieve this by using tee, which allows us to send the output of a command to multiple locations.
run the command -  /challenge/hack | tee >( /challenge/the ) | /challenge/planet
Get the flag as - pwn.college{gfebrBl7e3JRQHVLEViBUkdXZJM.dBDO0UDL3MTM1czW}
