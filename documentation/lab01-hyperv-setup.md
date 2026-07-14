# Lab 01 - Installing Hyper-V & Creating an External Virtual Switch

## Objective

Install Microsoft's Hyper-V virtualization platform and configure an External Virtual Switch to prepare a Windows 11 workstation for future virtual machines.

---

## Questions

### What is Hyper-V?

Hyper-V is a host that allows you to set up VMs and switches for them

Teacher notes: (The only thing I'd improve is that Hyper-V isn't the host itself—it's the virtualization platform running on your Windows computer. A stronger explanation would be: Hyper-V is Microsoft's virtualization platform that allows one physical computer to run multiple virtual computers (virtual machines). Each virtual machine has its own operating system, memory, storage, and networking, allowing them to operate independently from the host computer.)

### Why do you think we created an External Virtual Switch? What do you thing it does?

I believe we set up and external switch to direct network traffic to future VMs using an internet connection.

Teacher notes: (An External Switch lets the VM appear as another computer on your network.)

### Why do you think we used Windows 11 Pro instead of Windows Home?

Windows pro has more optional features like Hyper-V that will be utilized for future lessons.

### What is the difference between an External, Internal, and Private Virtual Switch?

Virtual switches in Hyper-V are used to direct network traffic between VMs and the host. The 3 types of switches are internal, external, and private. internal is not on a physical network and are connected to the Host and other VMs. Private is also not on a physical network but are only connected to each other not the host. Lastly external is connected to a physical network along with the host and other VMs.

---

## Configuration

Host Computer

CPU:
AMD Ryzen 9 7950X 16-Core Processor

RAM:
32 GB

Operating System:
Windows 11 Pro

Hyper-V:
Enabled

Virtual Switch:
External

Switch Name:
External Switch

Network Adapter:
(Enter the network adapter you selected.)

---

## Challenges

### Problem

No proplems encountered

### Troubleshooting

N/A

### Resolution

N/A

### What I Learned

N/A

**If no issues were encountered:**

No issues

---

## What I Learned

- I learned what Hyper-V is and why businesses use virtualization.
- I understand the difference between a Host and Guest operating system.
- I learned the purpose of an External Virtual Switch and how to create one.

---

## Screenshots

- Hyper-V Windows Feature Enabled
- Hyper-V Manager
- External Virtual Switch Configuration
