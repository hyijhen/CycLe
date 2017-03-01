# Analyzers for CycLe Project
## filetype.py
File module for getting input file type and some information. (General module for all analyzer)

## MD1
Get the start address from the hexdump file.

## MD2
Get the line number of the asm file.

## opcode
Get the frequency of the first 93 common opcode in malware.
- opcode.py  : main program
- opcode_list: the list of the first 93 common opcode in malware
- TWO VERSION:
  + MODE 0: objdump ver.  (Input: binary)
  + MODE 1: asm file ver. (Input: asm file)

## register
Get the frequency of x86 registers.
- register.py  : main program
- register_list: the list of x86 registers
- TWO VERSION:
  + MODE 0: objdump ver.  (Input: binary)
  + MODE 1: asm file ver. (Input: asm file)
