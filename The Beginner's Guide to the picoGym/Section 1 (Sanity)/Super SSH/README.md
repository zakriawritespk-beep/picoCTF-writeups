# PicoCTF2024 - Super SSH
## Problem Statement
### Before Launch Instance
Using a Secure Shell (SSH) is going to be pretty important.
Additional details will be available after launching your challenge instance.
### After Pressing Launch Instance
Using a Secure Shell (SSH) is going to be pretty important.
Can you ssh as ctf-player to titan.picoctf.net at port 64974 to get the flag?
You'll also need the password 1ad5be0d. If asked, accept the fingerprint with yes.
If your device doesn't have a shell, you can use: https://webshell.picoctf.org/
If you're not sure what a shell is, check out our Primer: https://primer.picoctf.com/#_the_shell
## Information
Category: 
Easy 
General Skills 
picoCTF2024
shell ssh
## Hints
* https://linux.die.net/man/1/ssh
* You can try logging in 'as' someone with <user>@titan.picoctf.net
* How could you specify the port?
* Remember, passwords are hidden when typed into the shell

## Solution
We will use command
* $ssh -p 64974 ctf-player@titan.picoctf
.net
<img width="494" height="32" alt="image" src="https://github.com/user-attachments/assets/7415e5a2-475e-4a1c-a578-e6e5c891c8c7" />

**What does it mean**

ssh (_secure shell program. it opens a encrypted remote session in another program_)

-p 64974 (_this tells to the shell to connect to this port_)

ctf-player (_its the username i will login as remote machine_)

titan.picoctf.net (_hostname or remote machine network address_)
* Now enter the password which is given 1ad5be0d
<img width="382" height="16" alt="image" src="https://github.com/user-attachments/assets/e3ee5a6a-71a3-437a-8bb0-a858821f90e0" />

* found the flag

<img width="491" height="42" alt="image" src="https://github.com/user-attachments/assets/b032a818-3bcd-497a-9951-ef15d08303a9" />



## Flag
picoCTF{s3cur3_cenn3ct10n_8306c99d}
