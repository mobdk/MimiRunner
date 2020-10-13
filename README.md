# MimiRunner
Run Mimikatz with ReactOS cmd.exe

Code execution with delay, this PoC shows how to run "Mimikatz", not using Windows cmd.exe but ReactOS cmd.exe (64 bit) and stay undetected by Defender. No change to the orginal "Mimikatz" compiled code.


The following syscall are used:

```
ZwOpenProcess
ZwAllocateVirtualMemory
ZwProtectVirtualMemory
ZwWriteVirtualMemory
ZwOpenThread
ZwQueueApcThread
ZwResumeThread
ZwClose
```



Poc vid: https://youtu.be/X_vJip6iLPQ
