### **LPIC-101 Practice Test**

**Time Allowed: 90 minutes**  
**Maximum Marks: 100**

---

#### **Section 1: System Architecture** (20 Marks)

1. **[Multiple Choice]**  
   Which of the following commands will display detailed CPU information on a Linux system?  
   A. `cat /proc/meminfo`  
   B. `lscpu`  
   C. `top`  
   D. `uname -r`  
   *(2 Marks)*  

2. **[Short Answer]**  
   What is the difference between `BIOS` and `UEFI` in terms of boot process and functionality?  
   *(5 Marks)*  

3. **[Practical]**  
   Use a command to determine which kernel modules are loaded in the current system. Explain how to load a new module named `dummy`.  
   *(5 Marks)*  

4. **[Short Answer]**  
   Explain the purpose of the `/proc` and `/sys` directories in Linux.  
   *(8 Marks)*  

---

#### **Section 2: Linux Installation and Package Management** (20 Marks)

5. **[Multiple Choice]**  
   Which of the following commands installs a package using the APT package manager?  
   A. `yum install package`  
   B. `dpkg -i package.deb`  
   C. `apt install package`  
   D. `rpm -ivh package.rpm`  
   *(2 Marks)*  

6. **[Short Answer]**  
   Describe the difference between `apt` and `dpkg`.  
   *(5 Marks)*  

7. **[Practical]**  
   Write a command to find and remove orphaned packages in a Debian-based system.  
   *(3 Marks)*  

8. **[Practical]**  
   On a Red Hat-based system, explain how to configure a new YUM repository with the base URL `http://repo.example.com`. Provide a sample `.repo` file configuration.  
   *(10 Marks)*  

---

#### **Section 3: GNU and Unix Commands** (30 Marks)

9. **[Multiple Choice]**  
   Which command is used to display the last 10 lines of a file?  
   A. `head`  
   B. `tail`  
   C. `cat`  
   D. `less`  
   *(2 Marks)*  

10. **[Practical]**  
    Write a command to count the number of lines containing the word "error" in the file `/var/log/syslog`.  
    *(3 Marks)*  

11. **[Short Answer]**  
    Explain the difference between `hard links` and `soft links` in Linux. How do you create each?  
    *(10 Marks)*  

12. **[Practical]**  
    Use the `find` command to locate all `.conf` files in `/etc` that have been modified in the last 7 days.  
    *(5 Marks)*  

13. **[Short Answer]**  
    Explain the purpose of the `cron` daemon. Provide an example of a cron job that runs a script named `backup.sh` every day at midnight.  
    *(10 Marks)*  

---

#### **Section 4: Devices, Filesystems, and FHS** (30 Marks)

14. **[Multiple Choice]**  
    What does the command `df -h` display?  
    A. List of directories and files  
    B. Disk usage in human-readable format  
    C. Free memory  
    D. Filesystem errors  
    *(2 Marks)*  

15. **[Practical]**  
    Use a command to display the UUID of all mounted filesystems.  
    *(3 Marks)*  

16. **[Short Answer]**  
    Explain the difference between ext3 and ext4 filesystems. Mention at least two features of ext4 that make it better.  
    *(8 Marks)*  

17. **[Practical]**  
    You have added a new disk to the system. Write the steps to create a new partition, format it with an ext4 filesystem, and mount it permanently at `/data`. Include all commands.  
    *(10 Marks)*  

18. **[Short Answer]**  
    What is the purpose of the `/etc/fstab` file? Provide an example entry for mounting a filesystem.  
    *(7 Marks)*  

---

#### **Bonus Question** *(Optional - 10 Marks)*  
Explain the boot process in Linux from powering on the machine to a fully loaded OS, detailing the role of GRUB, the kernel, and system initialization.

---

### **Answer Key and Instructions for Scoring**
- Award marks based on accuracy, detail, and clarity in the answers.
- Practical questions should be tested on a Linux environment to validate the commands.
- Submit your answer under the submissions dir.
