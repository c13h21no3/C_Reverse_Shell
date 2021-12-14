# C_Reverse_Shell

## Description

This is a simple reverse shell written in C for hacking Windows.

## Installation

0. Clone this repository

1. Compile server

> gcc server.c -o server
	
2. Compile backdoor.c for windows. 
 
> i686-w64-mingw32-gcc -o malware.exe backdoor.c -lwsock32 -lwininet

## Features

0. Shell

1. Persistence

> persist

2. Keylogger

> keylog_start

the keylog file will be in current directory as windows.txt
