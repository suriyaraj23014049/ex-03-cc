# 19CS416-CS-Ex-3-Linux-Commands

**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 
```bash
ls
```

**Output:**

![image](https://github.com/user-attachments/assets/0c9fce83-0c71-4db1-9dde-1fc7529c5c39)


### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:** 

![image](https://github.com/user-attachments/assets/c6dbfc45-2651-4759-a633-4bf4b6776f59)


### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/c2b36749-8b5b-41ab-aa0c-78d34ff7143d)


### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/438ec8b0-eaeb-4e6e-85ac-7adc879c090f)


### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/7baaa2cc-8901-436b-b962-e78a98f79bb0)


### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**
![image](https://github.com/user-attachments/assets/a428b1ba-1046-4555-acd0-2f7ea49834a8)


### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**

![image](https://github.com/user-attachments/assets/12b4679a-dd05-44f8-859c-0d0eacab23d2)


### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/f9edeffb-01be-4d62-8ead-c454459e59bd)


### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**

![image](https://github.com/user-attachments/assets/1c8a8722-3662-43af-844a-6eb5c1ae79a3)


### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**

![image](https://github.com/user-attachments/assets/a10a2f6a-aad9-4aec-8cfc-490d578317b4)


### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**

![image](https://github.com/user-attachments/assets/3c5c8f10-eb80-4d8f-943b-d65e0a2eb926)


### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/f1cac05a-1e2d-4c76-b7fb-359f903b2e2f)


### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**


![image](https://github.com/user-attachments/assets/6d707c60-96d3-47c8-b4ac-1ca5d52b512d)


### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**


![image](https://github.com/user-attachments/assets/d43f692a-db63-478d-a586-7d4b95e37336)


### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**


![image](https://github.com/user-attachments/assets/c241c14e-a16d-488a-a276-4f77f38a1e55)


### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**

![image](https://github.com/user-attachments/assets/4ce42d5d-c2ee-4998-b73e-4f8ed3fe6716)


### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/36031bfd-dd79-457a-82d5-badea076f5c7)


### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**


![image](https://github.com/user-attachments/assets/4bf413fd-2841-440c-90f9-3f86dade8f09)


### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**


![image](https://github.com/user-attachments/assets/64d1200a-c5e5-42cc-998d-6920310cdd0f)


### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**

![image](https://github.com/user-attachments/assets/aa3ba245-9e32-4981-81fc-153a1aa94b12)


### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**


![image](https://github.com/user-attachments/assets/e4cb8715-bb08-48be-8578-5dd3b563b89c)




### 22. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**


![image](https://github.com/user-attachments/assets/2ed4531e-4baa-4cde-8dee-bbc106c718eb)


### 23. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**

![image](https://github.com/user-attachments/assets/3b532fb0-d2b6-4522-8c17-5f982b039529)


### 24. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/e5fe4617-ecdc-4aeb-b862-fe96e8c357e4)


### 25. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**

![image](https://github.com/user-attachments/assets/a88b785e-80ed-47e5-a9c2-a66e79400193)


### 26. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**

![image](https://github.com/user-attachments/assets/c191525f-4425-414e-8fca-94b554ce7851)


### 27. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**

![image](https://github.com/user-attachments/assets/2cf22a3d-247e-403d-a0d1-9f12fd0b5312)


### 28. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**

![image](https://github.com/user-attachments/assets/c87a1662-2fec-428b-9586-d9ccb8cdf578)


### 29. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/19bada85-614f-4972-b0b3-641fc9194292)


## Result
All basic and advanced operations were successfully performed through appropriate Linux commands, with the system responding accurately to each, confirming correct execution and expected behavior, thereby demonstrating the effectiveness and reliability of the Linux command-line interface for comprehensive system management.
