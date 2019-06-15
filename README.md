# Getting Started With Bash Commands

## List of Commands
-   [ls](#ls)
-   [cat](#cat)
-   [grep](#grep)

### ls
File and directory listing command

1.  ls with no option.  
    It list the files and directories in bare format.
    ```
    $ ls
    ````

2.  ls with -l option.
    It shows file or directory, size, modified date and time, file or folder name and owner of file and its permission.
    ```
    $ ls -l
    ```

3.  ls with -a option.
    It shows all the files hidden with '.'.
    ```
    $   ls -a
    ```

4.  ls with -t option.
    It sorts the file by modification time, showing the last edited file first.
    ```
    $ ls -t
    ```

5.  ls with -1 option.
    It displayes one file per line.
    ```
    $ ls -1
    ```

6.  ls with -ld option.
    It displays the information about the directory.
    ```
    $ ls -ld
    ```

7.  ls with -F option.
    It displays the visual classification of files.
    ```
    $ ls -ld
    ```

### cat
It reads data from the file and gives their content as output.

1.  cat with one argument.
    It displays the contents of a single file. 
    ```
    $ cat HW.c
    ````

2.  cat with multiple argument.
    It displays the contents of a all the files.
    ```
    $ cat HW.c Lines.txt
    ````

3. cat with -n option
    It displays contents of a file preceding with line numbers.
    ```
    $ cat -n HW.c
    ```
        
4.  cat with > option
    It creates a new file with filename passed.
    ```
    $ cat >new_file.txt
    ```
        
5.  cat with > option in between of two file names
    It copies the contents of one file to another file.
    ```
    $ cat new_file.txt >my_new_file.txt
    ```        

6.  cat with -s option
    It supress the empty lines in a file.
    ```
    $ cat -s new_file.txt
    ```

7.  cat with >> option
    It appends the content of one file to the end of another file.
    ```
    $ cat new_file.txt >> my_new_file.txt
    ```
        
8.  tac command
    It displays content of a file in reverse order.
    ```
    $ tac HW.c
    ```

### grep
Searches a file for a particular pattern of characters, and displays all lines that contain that pattern.

1.  grep with -i option  
    It performs a case insensitive search on a file.
    ```
    $ grep -i "bash" new_file.txt
    ````

2.  grep with -c option  
    It counts the number of matches in a file.
    ```
    $ grep -c "bash" new_file.txt
    ````

3.  grep with -l option  
    It displayes the file names that matches the pattern.
    ```
    $ grep -l "bash" *
    ````

3.  grep with -n option  
    It displayes line number with the output.
    ```
    $ grep -n "bash" new_file.txt
    ````

4.  grep with -v option  
    It displayes the negation of the result.
    ```
    $ grep -v "bash" new_file.txt
    ````

5.  grep with ^ option  
    It displayes the lines that starts with the arguments passed.
    ```
    $ grep "^bash" new_file.txt
    ```
    
6.  grep with $ option  
    It displayes the lines that ends with the arguments passed.
    ```
    $ grep "bash$" new_file.txt
    ```
