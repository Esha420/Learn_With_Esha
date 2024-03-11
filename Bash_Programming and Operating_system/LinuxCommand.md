# Basic Linux Commands
---
### List Directory contents:

* ls -> To list the content of the current directory  ```ls```
* ls -l -> To list the contents of a specific directory in long format: ```ls -l path/to/directory```
* ls -a -> To list all files (including hidden) in the current directory: ```ls -a```
* ls -la -> To list all files and directories (including hidden) in the current directory in long format: ```ls -la```
  ![alt text](<img/Screenshot 2024-03-11 163920.png>)

  
### Changing Directories

* cd -> Changing to a directory within the current directory: ```cd directory_name ```
* Changing to a directory by providing an absolute path: ```cd path/to/directory```
* Changing to the parent directory: ```cd ..```
* Changing to the root directory: ```cd /```
* Changing to the previous directory ```cd -```
  ![alt text](<img/Screenshot 2024-03-11 164803.png>)

### Making a directory

* mkdir -> Make directory (creates a new directory): ```mkdir new```
* Creating directory giving absolute path: ```mkdir path/to/directory```
  
### Present working Directory
* pwd -> Shows present working directory ```pwd```
  
### Remove Directory
* rmdir -> Removes directory ```rmdir directory_name```
* rm -> Removes file ```rm file_name```
* rm -r -> to remove a directory and its contents recursively ```rm -r directory_name```
  
### Copy and Move Files
* cp -> Copies files ```cp source_file destination_file```
* mv -> Moves file ```mv source_file destination_file```
  
### Touch and Cat Command
* touch -> Create new empty file ```touch new.txt```
* cat -> Concatenate and display the contents of files ```cat file_name```

### Head and Tail Command
* head ->  Display the first few lines of a file ```head file_name```
* tail ->  Display the last few lines of a file ```tail file_name```

### Grep and Find Command
* grep -> Searching for specific text patterns within files ```grep "pattern" file.txt```
* find -> Search for files and directories ```find /path/to/search -name "filename```

### chmod/chown/sudo Command
* chmod -> Change permissions of files and directories ```chmod file_name```
* chown -> Change ownership of files and directories ```chown user:group file_name```
* sudo -> Execute a command with superuser (administrative) privileges ```sudo command```

### Manual Command
* man -> Display the manual pages for commands ```man command```
