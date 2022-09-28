# 0x02-shell_redirections

## 0x02. Shell, I/O Redirections and filters

This directory contains my work for 0x02. Shell, I/O Redirections and filters

### Contents

0. A script that prints “Hello, World”, followed by a new line to the standard output^[0].

1. A script that displays a confused smiley ```"(Ôo)'```^[1].

2. A script that displays the content of the ```/etc/passwd``` file^[2].

3. A script that displays the content of ```/etc/passwd``` and ```/etc/hosts```^[3].

4. A script that displays the last 10 lines of ```/etc/passwd```^[4].

5. A script that displays the first 10 lines of ```/etc/passwd```^[5].

6. A script that  displays the third line of the file ```iacta``` in the working directory. Do not  use ```sed```^[6].

7. A shell script that creates a file named exactly ```\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)``` containing the text ```Best School``` ending by a new line^[7].

8. A script that writes into the file ```ls_cwd_content``` the result of the command ```ls -la```. If the file ```ls_cwd_content``` already exists, it will be overwritten. If the file ```ls_cwd_content``` does not exist, create it^[8].

9. A script that duplicates the last line of the file ```iacta``` in the working directory^[9].

10. A script that deletes all the regular files (not the directories) with a ```.js``` extension that are present in the current directory and all its subfolders^[10].

11. A script that counts the number of directories and sub-directories in the current directory. The current and parent directories will not be taken into account. Hidden directories will be counted^[11].

12. A script that displays the 10 newest files in the current directory. One file per line, Sorted from the newest to the oldest^[12].

13. A script that takes a list of words as input and prints only words that appear exactly once. Input format: One line, one word. Output format: One line, one word. Words will be sorted^[13].

14. A script that displays lines containing the pattern “root” from the file ```/etc/passwd```^[14].

15. A script that displays the number of lines that contain the pattern “bin” in the file ```/etc/passwd```^[15].

16. A script that displays lines containing the pattern “root” and 3 lines after them in the file ```/etc/passwd```^[16].

17. A script that displays all the lines in the file ```/etc/passwd``` that do not contain the pattern “bin”^[17].

18. A script that displays all lines of the file ```/etc/ssh/sshd_config``` starting with a letter. Include capital letters as well^[18].

19. A script that replaces all characters ```A``` and ```c``` from input to ```Z``` and ```e``` respectively^[19].

20. A script that removes all letters ```c``` and ```C``` from input^[20].

21. A script that reverses its input^[21].

22. A script that displays all users and their home directories, sorted by users. Based on the the ```/etc/passwd file```^[22].

23. A script that finds all empty files and directories in the current directory and all sub-directories. Only the names of the files and directories will be displayed (not the entire path). Hidden files will be listed. One file name per line. The listing will end with a new line. I did not use ```basename```, ```grep```, ```egrep```, ```fgrep``` or ```rgrep```^[23].

24. A script that lists all the files with a ```.gif``` extension in the current directory and all its sub-directories. Hidden files will be listed. Only regular files (not directories) will be listed. The names of the files will be displayed without their extensions. The files will be sorted by byte values, but case-insensitive (file ```aaa``` will be listed before file ```bbb```, file ```.b``` will be listed before file ```a```, and file ```Rona``` will be listed after file ```jay```). One file name per line. The listing will end with a new line. I did not use ```basename```, ```grep```, ```egrep```, ```fgrep``` or ```rgrep```^[24].

25. A script that decodes [acrostics](https://en.wikipedia.org/wiki/Acrostic) that use the first letter of each line. The ‘decoded’ ends with a new line. I did not use ```grep```, ```egrep```, ```fgrep``` or ```rgrep```^[25].

26. A script that parses web server logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests. Order by number of requests, most active host or IP at the top. I did not use ```grep```, ```egrep```, ```fgrep``` or ```rgrep```^[26].

If you have any questions, [contact me](https://www.linkedin.com/in/ianonjuguna)

[0]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/0-hello_world

[1]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/1-confused_smiley

[2]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/2-hellofile

[3]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/3-twofiles

[4]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/4-lastlines

[5]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/5-firstlines

[6]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/6-third_line

[7]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/7-file

[8]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/8-cwd_state

[9]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/9-duplicate_last_line

[10]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/10-no_more_js

[11]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/11-directories

[12]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/12-newest_files

[13]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/13-unique

[14]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/14-findthatword

[15]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/15-countthatword

[16]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/16-whatsnext

[17]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/17-hidethisword

[18]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/18-letteronly

[19]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/19-AZ

[20]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/20-hiago

[21]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/21-reverse

[22]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/22-users_and_homes

[23]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/100-empty_casks

[24]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/101-gifs

[25]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/102-acrostic

[26]: https://github.com/IanoNjuguna/alx-system_engineering-devops/blob/main/0x02-shell_redirections/103-the_biggest_fan