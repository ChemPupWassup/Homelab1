# Lab 02 - Creating My First Virtual Machine

## Objective

Learn how to create and configure a virtual machine using Hyper-V.

## Questions

### What is an ISO file?

*(ISO is a digital copied version of the operating system installation disk. This can be linux, windows, or MacOS. The ISO contains everything you need for installation and can be used to mount an operating system to a VMs.)*

### Why do virtual machines need RAM?

*(RAM provides temporary working memory for the operating system and applications.  Virtual machines need dedicated RAM so that is can run properly while completing tasks.)*

### Why do we use Generation 2?

*(Generation 1 can be used for older versions of Hyper-V and simulate older 32-bit and 64-bit systems. Generation 2 is for newest Hyper-V for 64-bit systems..)*

### Why do we use a virtual hard disk?

*(If something goes wrong and the VM is connected to your hosts drive then your host files are at risk. We want to keep the VM completely Isolated..)*

## Configuration

VM Name:
Ubuntu-26.04

Generation:
2

Memory:
4096 MB

Network:
External Switch

Virtual Hard Disk:
127 GB (default)

## Challenges

### Problem

Ubuntu would not boot from the ISO and displayed a Secure Boot error.

### Troubleshooting

-Verified boot order.
-Confirmed the ISO was attached to the virtual DVD drive.
-Reviewed Secure Boot settings.
-Read and interpreted the error message instead of guessing.

### Resolution

After reviewing the VM configuration and Secure Boot settings, the installation completed successfully.

### What I Learned

I learned that boot order isn't the only reason a VM can fail to boot. Error messages often provide the most valuable troubleshooting information, so it's important to read and understand them before making configuration changes.

**If no issues were encountered:**

N/A

---

## What I Learned

- I learend how to properly set up my first Virtual machine in Hyper-V
- I no understand the boot sequences of a computer
- I know how to troubleshoot boot errors whith setting navigation.

---

## Screenshots

- VM configuration
- Ubuntu installer
- Ubuntu desktop
- Secure boot error
