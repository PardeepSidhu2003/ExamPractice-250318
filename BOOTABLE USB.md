# Creating a BOOTABLE USB
 
[LINK 1](https://www.youtube.com/watch?v=TqTtt7ljUWQ)

[LINK 2](https://www.youtube.com/watch?v=R70GchcnWpA)
# For Windows:
You'll need a tool like Rufus to create a bootable USB drive. Here are the steps:
1. Download Rufus
2. Insert your USB drive into your computer.
3. Open Rufus. It should automatically detect your USB drive.
4. Under Device, select your USB drive.
5. Under Boot selection, click SELECT and choose the ISO file for the operating system you want to make bootable (e.g. Windows 10 or Ubuntu).
6. Choose the Partition scheme and File system. Generally, for most modern systems:
    Partition Scheme: GPT
    File System: FAT32  or NTFS .
7. Click START and wait for the process to complete.
    If you see a prompt about writing in ISO Image mode, click OK.
8. Once finished, your USB drive will be bootable.

# Booting from USB:
1.Insert the USB drive into the target computer.
2. Boot the computer and enter the BIOS/UEFI settings (usually by pressing F2, F12, DEL, or ESC during boot).
3. Change the boot order to prioritize the USB drive.
4. Save changes and exit. Your computer should boot from the USB drive.
