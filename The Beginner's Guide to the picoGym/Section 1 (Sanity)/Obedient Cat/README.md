# PicoCTF2021 - Obedient Cat
## Problem Statement
This file has a flag in plain sight (aka "in-the-clear"). [Download flag](https://mercury.picoctf.net/static/33996e32dce022205a6a36f69aba56f0/flag).
## Information
Category: 
Easy 
General Skills 
picoCTF2021
## Hints
* Any hints about entering a command into the Terminal (such as the next one), will start with a '$'... everything after the dollar sign will be typed (or copy and pasted) into your Terminal.
* To get the file accessible in your shell, enter the following in the Terminal prompt: $ wget https://mercury.picoctf.net/static/33996e32dce022205a6a36f69aba56f0/flag
* $ man cat
## Solution
Download file named "flag" and copy and paste the flag.
* open the terminal https://webshell.picoctf.org/
* $wget https://mercury.picoctf.net/static/33996e32dce022205a6a36f69aba56f0/flag
<img width="422" height="14" alt="image" src="https://github.com/user-attachments/assets/1ec0bf1c-0ba4-4943-a828-fad6d245bb65" />

* Use ls command 
<img width="191" height="26" alt="image" src="https://github.com/user-attachments/assets/9933dc44-5fdc-43ba-9bbd-467915890142" />

* use cat command to get the output of flag file
<img width="271" height="29" alt="image" src="https://github.com/user-attachments/assets/e4239a45-8940-4a54-8bf9-01a23115c613" />

## Flag
picoCTF{s4n1ty_v3r1f13d_2aa22101}

