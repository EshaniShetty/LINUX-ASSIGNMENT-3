# LINUX-ASSIGNMENT-3
Linux Programming Assignment 3: Advanced terminal utilities (tee, find, whatis), system administration, and a comprehensive guide to installing Ubuntu 25.04 LTS on VirtualBox.


Topics & Commands Covered


1. Manuals & Quick Reference

man: Displays the full, detailed manual page for a command, including syntax and examples.


whatis: Provides a concise, one-line summary of a command's purpose for quick reference.

2. Output Redirection & Logging

tee Command: Used to split output, allowing it to be displayed on the screen while simultaneously saving it to a file.



Logging: Essential for monitoring live scripts while maintaining a permanent record (e.g., ./script.sh | tee -a log.txt).


3. Virtualization (Ubuntu 25.04 LTS)
Detailed guide on installing Ubuntu on Oracle VirtualBox, covering:


Hardware Allocation: Recommended 4GB RAM and 25-30GB VDI storage.



System Settings: Enabling 3D acceleration and allocating multiple CPUs for performance.


Troubleshooting: Managing Kernel Panic Errors during installation by verifying ISO checksums or using boot parameters like nomodeset and acpi=off.



4. System Administration

Hostname Management: Checking the host with hostname and temporary changes using sysctl kernel.hostname=newname.




Calendar Utilities: Accessing specific historical dates (e.g., cal 8 1984).



Process Monitoring: Combining uptime and who using the && operator to view system load and active users together.


Advanced Search: Using find with flags like -type f and -name "*.c" to locate specific source files recursively.




Security: Implementing strict "Owner Only" access using chmod 600.
