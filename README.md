# bootkits samples

password: infected

All samples are provided only for educational purposes. Don't run malware samples on your machine! Use a virtual machine environment (as an example: VMWare or VirtualBox) to research these malware samples. Good luck :-) 


# Supplement for the BOOK "ROOTKITS AND BOOTKITS"
Write additional explanations to help understanding the book.

## Chapter 8 STATIC ANALYSIS OF A BOOTKIT USING IDA PRO

- Sample 1 bootkit MBR which is similar to TDL4
  - File: MBR/infected_mbr.bin
  - Hash: 4de42cc58842cba8b73c1f8442805b438b2714adb41d1889789a597d5eb12de4
- Rewrote decr_mbr.py for Python3
  

## Chapter 9 BOOTKIT DYNAMIC ANALYSIS: EMULATION AND VIRTUALIZATION

- Using Bochs-win64-2.7
- Fix Listing 9-1 Sample Bochs configuration file
- Sample 1 malicious MBR (Need to be confirmed)
  - File: MBR/infected_mbr.bin
  - Hash: 4de42cc58842cba8b73c1f8442805b438b2714adb41d1889789a597d5eb12de4

- Sample 2 malicious VBR and IPL 
  - "partition0.data" described in the book
  - File: MBR/partition0.data (Need to be confirmed)
  - Hash: 65b400ccc7fbe46652dad2e7fe18ee53de8d1555c7df0ea61b71a77c822c5ab4

- Set breakpoint (lb 0x7c00) by bochsdbg.exe before debugging by IDA Pro
- 

