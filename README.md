<h1>EX.4-LINUX-COMMANDS</h1>

<h1>AIM:</h1>

To study and execute the basis of UNIX commands

<h1>LINUX COMMANDS :</h1>

<h1>COMMAND1: ls - List Files and Directories</h1>

Syntax:

	ls [options] [directory]
Code: 

	ls -l /home/user
Output: 

	List of files and directories in /home/user with details.
<h1>Command 2 : cd - Change Directory</h1>

Syntax: 

	cd [directory]
Code: 

	cd /var/www
Output: 

	Change to the /var/www directory.
<h1>Command 3 : pwd - Print Working Directory</h1>

Syntax:

	pwd
Code: 

	pwd
Output: 

	/home/user (prints the current working directory).
<h1>Command 4 : mkdir - Create Directory</h1>

Syntax: 

	mkdir [directory]
Code: 

	mkdir my_directory
Output:	

	Creates a new directory named my_directory.
<h1>Command 5 : touch - Create Empty File</h1>

Syntax: 

	touch [filename]
Code: 

	touch newfile.txt
Output: 

	Creates a new empty file named newfile.txt.
<h1>Command 6 : cp - Copy Files and Directories</h1>

Syntax: 

	cp [options] source destination
Code: 

	cp file.txt /backup/
Output: 

	Copies file.txt to the /backup/ directory.
<h1>Command 7 : mv - Move/Rename Files and Directories</h1>

Syntax: 

	mv [options] source destination
Code: 

	mv oldfile.txt newfile.txt
Output:

	Renames oldfile.txt to newfile.txt.
<h1>Command 8 : rm - Remove Files and Directories</h1>

Syntax: 

	rm [options] [file/directory]
Code: 

	rm file.txt
Output: 

	Deletes file.txt.
<h1>Command 9 : cat - Concatenate and Display File Content</h1>

Syntax: 

	cat [filename]
Code: 

	cat file.txt
Output: 

	Displays the content of file.txt.
<h1>Command 10 : more - View File Content Page by Page</h1>

Syntax: 

	more [filename]
Code: 

	more longfile.txt
Output:

	Allows you to view the content of longfile.txt one page at a time.
<h1>Command 11 : less - View File Content with Navigation</h1>

Syntax: 

	less [filename]
Code: 

	less largefile.txt
Output: 

	Displays largefile.txt with navigation capabilities.
<h1>Command 12 : head - Display Top Lines of a File</h1>

Syntax: 

	head [options] [filename]
Code: 

	head -n 5 file.txt
Output:

	Shows the first 5 lines of file.txt.
<h1>Command 13 : tail - Display Bottom Lines of a File</h1>

Syntax: 

	tail [options] [filename]
Code: 

	tail -n 10 file.log
Output: 

	Shows the last 10 lines of file.log.
<h1>Command 14 : grep - Search Text in Files</h1>

Syntax: 

	grep [options] 'pattern' [file(s)]
Code: 

	grep 'keyword' file.txt
Output: 

	Lists lines containing 'keyword' in file.txt.
<h1>Command 15 : find - Search for Files and Directories</h1>

Syntax:

	find [path] [expression]
Code: 

	find /home/user -name '*.txt'
Output: 

	Finds all .txt files under /home/user.
<h1>Command 16 : chmod - Change File Permissions</h1>

Syntax: 

	chmod [options] permissions file(s)
Code: 

	chmod 644 file.txt
Output: 

	Sets read and write permissions for the owner and read-only permissions for others on file.txt.
<h1>Command 17 : chown - Change File Ownership</h1>

Syntax: 

	chown [options] user:group file(s)
Code: 

	chown user:group file.txt
Output:

	Changes the owner and group of file.txt.
<h1>Command 18 : tar - Archive and Compress Files</h1>

Syntax: 

	tar [options] [file(s)]
Code: 

	tar -cvzf archive.tar.gz dir/
Output: 

	Creates a compressed archive of the dir/ directory.
<h1>Command 19 : df - Display Disk Space Usage</h1>

Syntax: 

	df [options] [filesystem(s)]
Code: 

	df -h
Output: 

	Shows disk space usage in a human-readable format.
<h1>Command 20 : du - Display Directory Space Usage</h1>

Syntax: 

	du [options] [directory]
Code: 

	du -sh /var
Output: 

	Displays the total size of the /var directory in a human-readable format.
<h1>Command 21 : ps - Display Process Status</h1>

Syntax: 

	ps [options]
Code: 

	ps aux
Output: 

	Lists running processes with details.
<h1>Command 22 : kill - Terminate Processes</h1>

Syntax: 

	kill [signal] [PID]
Code: 

	kill -9 1234
Output: 

	Sends a SIGKILL signal to process with PID 1234.
<h1>Command 23 : ssh - Secure Shell</h1>

Syntax: 

	ssh [user@]hostname
Code: 

	ssh user@remote-server
Output: 

	Establishes a secure remote connection to remote-server.
<h1>Command 24 : scp - Securely Copy Files Over SSH</h1>

Syntax:

	scp [options] source destination
Code: 

	scp file.txt user@remote-server:/path/
Output: 

	Copies file.txt to a remote server over SSH.
<h1>Command 25 : wget - Download Files from the Internet</h1>

Syntax: 

	wget [options] [URL]
Code: 

	wget https://example.com/file.zip
Output: 

	Downloads file.zip from the specified URL.

<h1>Result:</h1>
Thus basis of UNIX commands are studied and executed.
