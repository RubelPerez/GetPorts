# GetPorts
---
## Description
GetPorts is a tool developed in Python 3, intended to collect all the ports of an XML report after a NMAP scan.

Besides, it copies them to the clipboard making easier the task, when a machine has many ports open. just use **CTRL + V**

## Installation
1. Download the GetPorts script. 
2. Install require modules 
3. Save the file in a system path (I rather /usr/local/bin) 
4. make sure that the permissions are 754

## Use

if you just write GetPorts in a console, you will receive:

![Tux, the Linux mascot](/resources/GetPorts1.png)

Asking for a **XML File** as a parameter

If the XML file is valid, you will see the result
![Tux, the Linux mascot](/resources/GetPorts3.gif)

When is not a valid XML, you will see:
![Tux, the Linux mascot](/resources/GetPorts4.png)

**You MUST be SUDO to run this script.**