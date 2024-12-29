# Backdoor challenge

# ELF Golfing

- **ELF golfing** is a technique used to create extremely small or "minimal" ELF (Executable and Linkable Format) binaries by stripping away unnecessary parts and optimizing the code to reduce the overall file size.
- structure of a ELF File

![image.png](Backdoor%20challenge%20114ebce620a980c38a5fd4589632942f/image.png)

- ELF HEADER
    - magic number 0x7ELF
    - 32/64 bit
    - endianness
    - abi
    - offsets
- Programmer Header
    - defines segments(can contain sections)
    - used mostly by the loader
    - how segments are loaded into memory.
    - demand paging(mapping vs loading)