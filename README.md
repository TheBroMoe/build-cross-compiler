## Introduction
A cross compiler is a compiler than runs on a parent platform (your current operating system), but generates executables for a target platform, which may differ in operating system, CPU, or executable format. 

Cross compilers are necessary if you are developing your own operating system, to avoid causing trouble from running your system compiler with your target OS executables.

This however can be a daunting task and requires a multitude of steps and setups.

## Description

build-cross-compiler.sh is meant to automatically set up all the steps required to build a cross-compiler using a desired prefix (currently set as 'i686-elf'). This script is a work in progress, and it will take more than a few minutes for everything to set up.

## How to verify it works

After everything finishes installing, try entering '1686-elf' and hit tab for auto completion and you should see the following results :
![alt text](https://github.com/TheBroMoe/build-cross-compiler/result.png "result")
