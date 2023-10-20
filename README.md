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
![Screenshot 2023-10-20 085452](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/adc6dea0-b9a4-4dce-b283-74ab4747b623)


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
![Screenshot 2023-10-20 085659](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/049d0f76-ffd4-436b-9c38-a5179dc803ac)

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
![Screenshot 2023-10-20 085747](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/541d34b1-a446-414e-8b20-448475d9b743)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
![Screenshot 2023-10-20 085840](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/c244d991-05ac-4b3a-be33-2f6b8d9b4cb3)


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
![Screenshot 2023-10-20 085914](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/ade4dbdf-5e6f-42fc-82e2-d5ea703b3ea8)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
![Screenshot 2023-10-20 085952](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/c3c145da-cdaa-4784-a53f-3e962752dc2d)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>
![Screenshot 2023-10-20 090027](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/9e4840ea-8036-4432-8ab2-3214579e2162)



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
![Screenshot 2023-10-20 090059](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/57d90ac0-1ddb-4bbf-9353-fe80b1607c7c)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
![Screenshot 2023-10-20 090135](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/ff9d408d-c453-4a0b-9e47-228315e4f455)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

![Screenshot 2023-10-20 090200](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/f591a849-b418-4f46-941e-25bde867e17c)

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

![Screenshot 2023-10-20 090217](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/cc8d880b-edd6-4ee2-8d85-f84dc4270365)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

![Screenshot 2023-10-20 090238](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/23ec96fc-0243-4831-902a-0c7278513a3c)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

![Screenshot 2023-10-20 090256](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/a917d3db-21ab-464f-b623-09c9eb853b46)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![Screenshot 2023-10-20 090311](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/70297239-c843-4f27-9215-d71a04a50e99)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![Screenshot 2023-10-20 090423](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/d40c849c-a5d3-4cac-8d8b-7e1d86c8fc20)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![Screenshot 2023-10-20 090440 - Copy](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/65c7e634-f5eb-4a6e-b4fb-b03aaf525ce1)


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

![Screenshot 2023-10-20 090440](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/f0b5715a-612c-4635-aab1-defe0f7b48fb)


### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c

![Screenshot 2023-10-20 090450](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/b087e61e-86a2-497f-8268-89baa732f92b)

### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

![Screenshot 2023-10-20 090505](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/454722ab-3deb-4fad-965c-44a34ccf14c1)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![Screenshot 2023-10-20 090525](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/28e352d4-b2db-4a6a-9e5e-94e0901ac148)


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

![Screenshot 2023-10-20 090546](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/09fb6187-42d5-404a-a325-606027bda32d)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

 ![Screenshot 2023-10-20 090604](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/b694d100-7b4e-4558-b546-0a3ad13779f9)

### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>


![Screenshot 2023-10-20 090618](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/f1e84777-c193-4211-8dfb-ec0159aa8e35)




### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..


![Screenshot 2023-10-20 090629](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/a9ebd059-0124-4330-bc2e-f63f003c194a)





### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

![Screenshot 2023-10-20 090640](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/88ad9c3d-ac3f-48be-a194-a53a12e2bb7a)



 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal



### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![Screenshot 2023-10-20 090604](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/8f5087de-07c7-4b26-a6c4-5a1e463231da)


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

![Screenshot 2023-10-20 090618](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/e03a4593-fec1-46de-8a41-d8c0b023895d)

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

![Screenshot 2023-10-20 090648](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/e65f7b50-5093-47fc-99eb-30011273330c)


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

![Screenshot 2023-10-20 090702](https://github.com/premjivip/Ex-01-Linux-Commands/assets/143831886/1f1c1c1e-d0b7-4ab9-8d7b-99e3fa11d8ff)





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
