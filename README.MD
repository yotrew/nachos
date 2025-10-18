## nachos-4.0 for Linux 64bits(Ubuntu 24.04.3)
### It also works on Windows WSL2 (Ubuntu 24.04.1 LTS).
1. sudo apt install git csh g++ make  
2. sudo apt-get install gcc-multilib g++-multilib  
3. git clone https://github.com/yotrew/nachos.git  
4. change directory to nachos/  
   sudo cp -r usr /  
5. change directory to nachos/nachos-4.0/code  
6. make  
7. change directory to ./userprog  
8. ./nachos -e ../test/test1  
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

Ref:
1. [在Windows 10中使用WSL2安裝NachOS](https://hackmd.io/@seanpeng12/HkrEHYsu5)
2. [OS_HW1-2019](https://blog.nekowu.net/2019/10/10/2019-10-10-OS_HW1-2019/)
