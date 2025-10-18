## nachos-4.0 for Linux 64bits(ubuntu 24.04.3)
1. sudo apt install git csh g++  
2. git clone https://github.com/yotrew/nachos.git  
3. change directory to nachos/
   sudo cp -r usr /
4. change directory to nachos/nachos-4.0/code  
5. make  
6. change directory to ./userprog  
7. ./nachos -e ../test/test1
   result:
```
Total threads number is 1
Thread ../test/test1 is executing.
Print integer:9
Print integer:8
Print integer:7
Print integer:6
return value:0
No threads ready or runnable, and no pending interrupts.
Assuming the program completed.
Machine halting!

Ticks: total 200, idle 66, system 40, user 94
Disk I/O: reads 0, writes 0
Console I/O: reads 0, writes 0
Paging: faults 0
Network I/O: packets received 0, sent 0
```
