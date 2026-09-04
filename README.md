# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls
<img width="680" height="149" alt="image" src="https://github.com/user-attachments/assets/66531835-49be-49ce-b819-1293523f1f77" />


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd


<img width="612" height="45" alt="image" src="https://github.com/user-attachments/assets/920cc698-f460-467a-8266-5d133dfcc914" />

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>


<img width="603" height="39" alt="image" src="https://github.com/user-attachments/assets/37536757-e880-4b21-b029-5a43de2778fd" />


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>


<img width="608" height="41" alt="image" src="https://github.com/user-attachments/assets/e90e3c17-e3f7-4d3e-9ace-971d35b8dd56" />


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>


<img width="610" height="45" alt="image" src="https://github.com/user-attachments/assets/5d558c2b-685f-46ea-81d0-245399cd162b" />


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..


<img width="624" height="75" alt="image" src="https://github.com/user-attachments/assets/1c45de0f-1e25-4363-b8e6-82b6f47c8570" />

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="607" height="44" alt="image" src="https://github.com/user-attachments/assets/e1d19626-13a3-4484-b9a2-6f9e617e248b" />


### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="645" height="21" alt="image" src="https://github.com/user-attachments/assets/a3180bd8-9783-44aa-b402-0ac71f3c896b" />


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

<img width="622" height="67" alt="image" src="https://github.com/user-attachments/assets/336a46df-a4d3-4e4d-b2de-167c4cad7ebd" />



### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>


<img width="600" height="21" alt="image" src="https://github.com/user-attachments/assets/6d4c0740-26ba-42e2-8256-f4d55698fbf6" />

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files


<img width="684" height="166" alt="image" src="https://github.com/user-attachments/assets/d461113b-587c-455a-993c-faf6197d4577" />


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>


<img width="612" height="201" alt="image" src="https://github.com/user-attachments/assets/e073cfbb-f3e8-4b26-b3e8-1df3768c6109" />


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>


<img width="474" height="202" alt="image" src="https://github.com/user-attachments/assets/8738d9d2-6837-4278-9e75-27047d850157" />

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id


<img width="726" height="78" alt="image" src="https://github.com/user-attachments/assets/97bb8f5f-28ac-483f-a645-ca96a9d47654" />


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="622" height="41" alt="image" src="https://github.com/user-attachments/assets/1fd3fb0c-d59f-46c0-bdb6-069d6835a22d" />

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>


<img width="707" height="128" alt="image" src="https://github.com/user-attachments/assets/8381135c-fee4-4750-bcdb-a0d58681f756" />

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name


<img width="579" height="199" alt="image" src="https://github.com/user-attachments/assets/5d1ad3ef-a45b-4f4f-accd-7d0f5f468637" />

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
<img width="679" height="59" alt="image" src="https://github.com/user-attachments/assets/1721a10f-c613-4edc-a0ff-8634c706468e" />


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]


<img width="874" height="178" alt="image" src="https://github.com/user-attachments/assets/8a095a2a-3350-48ed-967f-c8679727a2d1" />

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>


<img width="647" height="38" alt="image" src="https://github.com/user-attachments/assets/39bbf46d-6acf-465e-9e07-2b4ad0e11b1e" />


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..


<img width="696" height="187" alt="image" src="https://github.com/user-attachments/assets/57818956-6a65-4528-b52a-cb59403149a9" />


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

 <img width="692" height="131" alt="image" src="https://github.com/user-attachments/assets/69bedaf9-4ce9-4c37-b656-788ae634ebd8" />

### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

<img width="627" height="161" alt="image" src="https://github.com/user-attachments/assets/be768e36-5390-475d-b05a-52e413bf4f7a" />


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear


<img width="704" height="186" alt="image" src="https://github.com/user-attachments/assets/55ad0b5e-0ea0-498e-b181-ae087e6916cc" />


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

 <img width="858" height="81" alt="image" src="https://github.com/user-attachments/assets/6ae43f40-3d57-4818-b3a2-261000debd70" />

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="730" height="238" alt="image" src="https://github.com/user-attachments/assets/22dc1adb-0695-4edd-80a3-3257f64058db" />

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
