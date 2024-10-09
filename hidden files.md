Navigate to the root directory and run the ls command with -a to allowing viewing files beginning with . 
Then read the hidden flag file with cat.
cd /
ls -a
we get the hiddenfile 
.   .dockerenv             bin   challenge  etc   lib    lib64   media  nix  proc  run   srv  tmp  var
..  .flag-253331873611714  boot  dev        home  lib32  libx32  mnt    opt  root  sbin  sys  usr
run command to read that file-  cat /.flag-253331873611714 
get the flag - pwn.college{g28ksuF-x5SfIsVMnOveec5L7XJ.dBTN4QDL3MTM1czW}


