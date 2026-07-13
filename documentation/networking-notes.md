LAB 01

Challenge questions

1. What is Hyper-V? Try explaining it in your own words.

Hyper-V  is a host that allows you to set up VMs and switches for them

Teacher notes: (The only thing I'd improve is that Hyper-V isn't the host itself—it's the virtualization platform running on your Windows computer.
A stronger explanation would be:

Hyper-V is Microsoft's virtualization platform that allows one physical computer to run multiple virtual computers (virtual machines). Each virtual machine has its own operating system, memory, storage, and networking, allowing them to operate independently from the host computer.)

2. Why do you think we created an External Virtual Switch?  What do you thing it does?

Answer: I believe we set up and external switch do direct network traffic to future VMs using an internet connection.

Teacher notes: (An External Switch lets the VM appear as another computer on your network.)

3. Why do you think we used Windows 11 Pro instead of Windows Home? (Hint: Think about what features Pro includes.)

Answer: Windows pro has more optional features like Hyper-V  that will be utilized for future lessons. 

Teacher notes: Windows Pro also includes enterprise-focused features such as:

Hyper-V
Remote Desktop Host
Group Policy
BitLocker management
Domain Join

4. What do you think a Virtual Machine actually is? Not the technical definition.

A virtual machine is a virtual computer used for testing and use of old software that may only work on old computers that are no longer available.

Teacher notes: Virtual machines are also used for:

software testing
malware analysis
server hosting
training
development environments

Bonus Question: What's the difference between an External, Internal, and Private Virtual Switch in Hyper-V?

Virtual switches in Hyper-V are used to direct network traffic between VMs and the host.  The 3 types of switches are internal, external, and private.
internal is not on a physical network and are connected to the Host and other VMs.  Private is also not on a physical network but are only connected to each other not the host.
Lastly external is connected to a physical network along with the host and other VMs

Teacher notes:
Instead of memorizing:

External = Internet
Think about who can communicate with whom.

Bonus question: Suppose you download a suspicious program from the Internet.  Would you run it on:

A. Your real Windows PC

B. A Virtual Machine

Why?

Answer: I would choose B.  I chose a virtual machine because it has a segregated space for the suspicious program to run and be tested without it having access to my person computer and person files.

LAB 02

1. What is ISO in your own words?

ANSWER: ISO is the copied version of the operating system that you chose.  This can be linux, windows, or MacOS.  The ISO contains everything you need for installation and can be used to mount an opperating system to a VMs.

2. why do you thing the virtual machine section is empty?

ANSWER:  Virtual machines need to be created first.  Hyper-V is just a manager not the actual VM.
