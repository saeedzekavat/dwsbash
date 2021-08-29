Bash script to handle a command with argument options and argument values.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
Instruction:
please put the dwsapp bash file to your /usr/local/bin which helps you to execute it as a bash terminal command.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
Argument Options (flag)
-i  time interval
-n  number of retry
-c  command

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
Examples
dwsapp -i 15 -n 10 -c "ping -c 2 4.2.2.4"    ;it will return you true exit code, break the loob and print  "Congrate, Internet UP&Running, 100% packet recived"
dwsapp -i 15 -n 10 -c "ping -c 2 4.2.2.23"    ;it will return you false exit code and print "Poor You, No Internet Connection, Packet lost" it will retry 10 times and there is an 15 seconds interval between exch effort,

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
Articles
Reading about the structure of 'While getops' to informing handling options with value

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
Tools
bash scripts,
while loop
if 

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
Get Feedback
It is my pleasure so let me know your comments,
Email: zekavat@outlook.com
github: https://github.com/saeedzekavat

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
Contribute
Contributions are always welcome! Please read the contribution guidelines first.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------License
GNU GPL v3

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
To the extent possible under law, 'Saeed Zekavat' has waived all copyright and related or neighboring rights to this work.
Aug, 2021

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
[@dwsclass](https://github.com/dwsclass) dws-dev-009-bash
