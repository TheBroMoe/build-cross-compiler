## Introduction
A cross compiler is a compiler than runs on a parent platform (your current operating system), but generates executables for a target platform, which may differ in operating system, CPU, or executable format. 

Cross compilers are necessary if you are developing your own operating system, to avoid causing trouble from running your system compiler with your target OS executables.

This however can be a daunting task and requires a multitude of steps and setups.

## Description

build-cross-compiler.sh is meant to automatically set up all the steps required to build a cross-compiler using a desired prefix (currently set as 'i686-elf'). This script is a work in progress, and it will take more than a few minutes for everything to set up.

## How to verify it works

After everything finishes installing, try entering '1686-elf' and hit tab for auto completion and you should see the following results :

```
i686-elf-addr2line   i686-elf-c++filt     i686-elf-gcc         i686-elf-gcc-nm      i686-elf-gcov-dump   i686-elf-gprof       i686-elf-nm          i686-elf-ranlib      i686-elf-strings
i686-elf-ar          i686-elf-cpp         i686-elf-gcc-9.1.0   i686-elf-gcc-ranlib  i686-elf-gcov-tool   i686-elf-ld          i686-elf-objcopy     i686-elf-readelf     i686-elf-strip
i686-elf-as          i686-elf-elfedit     i686-elf-gcc-ar      i686-elf-gcov        i686-elf-gdb         i686-elf-ld.bfd      i686-elf-objdump     i686-elf-size 
```
