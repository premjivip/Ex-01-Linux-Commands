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
 ![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/d1312d89-f7f6-4270-9621-feef2aac4acc)



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/bfdbeef3-42c9-41d7-9f0c-73f0d18780f7)


 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/ee13028c-0c42-4a85-9739-df744732be92)



### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/741ec338-97f5-4091-b662-04d316846cdb)



### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/e8ab8f29-cb77-41a3-8881-a811bd134e30)



### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/8bf041d4-8dcd-4fc1-be4b-c3155b24bc30)


 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/a26d4b4e-726d-48e0-8c1e-ec902aaefb27)




### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/ccea4949-16a2-4e44-a1ba-6ec8b00c75e1)



### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/78ef1d9d-21e6-4c29-9b62-ada21e3225e0)



### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/deaa7c54-4189-48a5-a761-ac7cc379e1ae)


 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/ff661799-b5c5-4659-92bf-6f5193eeee1e)



### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/9bebc38c-e3c6-40c7-a3fc-4a43847e96fc)



### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/13b4b274-63eb-46c2-95d8-662a8e9750c5)


 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/97f79370-da9b-44c8-8c14-5677e35e0961)



### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/8894a9d1-fe7f-4cfb-b343-eb5d7a30bb00)



### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/385c9629-79fe-4cc1-b24b-1cc254d75620)


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
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/f60d6d59-71c9-4277-9ebf-bf28d6651f30)


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/51c84672-71ad-4fcb-b720-a2a2ad72e281)



### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/dcfeb134-c2ba-42c9-af37-e784a228b692)


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/61160c5a-2278-43cd-a90e-b59e93a46ff5)



### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/0285c4f4-f313-4ff4-8010-f32158e4b21e)



### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/4fb9813b-4717-4a21-8c63-07fd050b5e1c)


 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/7c4d11e3-f5da-4d88-95ec-af0d50315cf2)



### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/0bf9371b-df9c-4852-99de-5a1ba7882609)



### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/d47b9840-5c28-49ae-8cd0-70e241188446)


 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
![image](https://github.com/snoopydj911/Ex-01-Linux-Commands/assets/122033587/4fe817bb-7b4e-431a-b49d-2c4f5ce373d9)


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
