# NASM
NASM Assembler 


How to install NASM And DOSBOX(16 Bit Machine) in Ubuntu/Linux

First step to download nasm Assembler

https://github.com/whiz-coder/NASM



Then install dosbox in ubuntu 

sudo apt install dosbox 



Then Extract ZIP File (NASM) which u download from github

Copy that nasm folder and paste in home directory 

after that open dosbox and mount that nasm folder in dosbox 

mount c /home/(username)/NASM

now to go in C 

C:

For Compiling Assembly code u need to write assembly code and paste in that NASM folder which u paste in home directory


nasm (filename.asm) -o (filename.out)

then open it in Advance Debbuger by

afd (filename.out)

And You are done !
