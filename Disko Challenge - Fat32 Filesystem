# Challenge Disko

## Important Terminologies

Commands Used

- wget → to download the file
- gunzip → to extract the file
- file → to check the filetype
- strings → to check the human-readable text strings from disk image
- strings filename | less → for paged view
- strings filename | grep → to get the flag

Terminologies Grasped

Fat32 Filesystem 

And how to extract human-readable from that particular disk image  

In this challenge we have been given a disk image in the challenge

Lets download this disk in the tmp directory in the webshell

![Step 1](Images/Disko_challenge/step1.png)

After download do the Gunzip to extract the disk image

![Step 2](Images/Disko_challenge/step2.png)

Lets see the type of the file this is 

Use the File command to check the file type

The `file` command in Linux is used to **determine the type of a file** based on its **content**, not its extension.

---

### 📘 **Basic Syntax**

```bash

file filename
```

---

![Step 3](Images/Disko_challenge/step3.png)

We see that this image is a FAT32 filesystem

### 📂 What is a FAT32 Filesystem?

**FAT32** stands for **File Allocation Table 32-bit**. It is a **legacy file system** created by Microsoft, widely used for removable drives and older operating systems.

Now we need to extract strings from the FAT32 Filesystem 

Extracting strings from a FAT32 filesystem typically means retrieving **human-readable text** from **binary files**, **disk images**, or **partitions**. This is often done in **digital forensics**, **malware analysis**, or **data recovery**.

Lets now extract 

![Step 4](Images/Disko_challenge/step4.png)

String command -

This command **extracts and views all human-readable text strings** from a **disk image file** called `disko-1.dd` using `strings`, and then pipes it through `less` for **paged viewing**.

Now lets search for the flag

![Step 5](Images/Disko_challenge/step5.png)

And Ta-da we found it
