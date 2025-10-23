# PicoCTF2019 - what's a net cat?
## Problem Statement
Using netcat (nc) is going to be pretty important. Can you connect to jupiter.challenges.picoctf.org at port 64287 to get the flag?
## Information
Category: 
Easy 
General Skills 
picoCTF2019

## Hints
* nc [tutorial](https://linux.die.net/man/1/nc)

## Solution

* Use command $ nc jupiter.challenges.picoctf.org 64287

<img width="499" height="28" alt="image" src="https://github.com/user-attachments/assets/2cc80f75-439c-4b35-bc52-f89966d1e168" />

netcat is lightweight TCP/UDP utility 

jupiter.challenges.picoctf.org is a remote host name

64287 the tcp port on that hostname 

What i did is just I opened a TCP connection to the port on that host name
## Flag
picoCTF{nEtCat_Mast3ry_284be8f7}

