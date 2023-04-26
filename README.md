# File-Management-Component

This program focuses on the development of a file management component for a distributed file management system in Python using nested dictionaries structure. This structure deals with handling files and directories. 

## About the Program
Files are organized insides directories. Directories can also contain further subdirectories. The management structure provides ways to <br>

•	Create directories <br>
•	Create files and directories inside root directory <br>
•	Access the files <br>
•	Update and query files in multiple mode (read, write, reposition, truncate etc) <br>
•	Move the files <br>
•	Delete the files <br>
•	Change the directory <br>
•	Get Memory Map <br>

## Program Functionalities

1.	Create → creates a file entry in the file structure.
2.	Delete → removes the file from the file structure. 
3.	Move → changes the association of a file in the directory structure and does not require physical movement of the content.
4.	Open file → returns a file Object and all read, write, move, and truncate will be through this object.
5.	Write to a file → a function having two modes: <br>
<t> a.	append mode → writes to the end of the file. <br>
<t> b.	write_at → writes to a specific point in the file. <br>
6.	Read from a file → a function having two modes: <br>
<t> a.	Sequential access → reads from the first word and returns the entire content. <br>
<t> b.	readFrom (start, size) → reads from the start memory location for size number of  characters. <br>
7.	Move content within a file → allows the user to move forward or back data. The input should be of the form: Move(filename, from, to, size) where filename is the name of the file, from is the starting location of data to be moved, to is the location where the data should be placed and size is the size of the data to be moved.
8.	Truncatefile(size) → reduces the size of the file to size.
9.	Show memory map → shows the distribution of files in the memory.
A single data file is to be created which contains all the internal structure and data of the user-created files.

## Group Members

• Hafsa Malik (341303) <br>
• Syeda Fatima Shahid (337346)


