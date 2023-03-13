- Task 0 Hello World
	
	- Command `echo -e <PRINTED TEXT\n>` to print out the text 

- Task 1 Confused Smiley

	- Command `echo "\<SPECIAL_CHAR>" to escape special charaters.

- Task 2 Let's Display a file

	- Command `cat <filename>` to display a file's content.

- Task 3 What about 2?

	- Command `cat <filename> <another_file>` to display multi files contents

- Task 4 Last lines of life

	- Command `tail -n <number> <file>` Display specified number of lines at the end of a file

- Task 5 I'd Prefer the first one actually

	- Command `head -n <number> <file>` Display specified number of lines from the tom of a file

- Task 6 Line #2

	- Command `cat <filename> | head -n 3 | tail -n 1` or `awk "NR==3" <filename>` to display the 3rd line

- Task 7 It's a good life that cutst iron without making a noise

	- Command `echo -e > "FILENAME WITH \ESCAPED CHARS" "text"` create a file with special chars name and add content to it with new line

- Task 8 Save current state of directory

	- Command `ls -al | cat > <filename>` to print listing result inside a file

- Task 9 Duplicate last line 

	- Command `tail -n 1 <filename> | cat >> <filename>` duplicate the last line at a file

- Task 10 No more javascript

	- Command `find *.ext -type f -delete` to delete only files with some extension

- Task 11 Don't just count your directories, make your directories count 

	- Command `find . -mindepth 1 -type d | wc -l` count directories/sub-directories into the current working directory

- Task 12 What's new

	- Command `ls -t | head` display the last 10 new files

- Task 13 Being unique is better than being perfect

	- Command `uniq -u | sort` to return sorted unique items

- Task 14 It must be in that file

	- Command `cat <filename> | grep <filter>` search text inside the file to get all matchs the filter

- Task 15 Count the word 

	- Command `cat <filename> | grep <filter> | wc -l` Count lines of filtered results

- Task 16 What's next?

	- Command `grep <filter> <filename> -<length>` display file contents which matches the filter and additional number of linex after it

- Task 17 I hate bins

	- Command `grep -v <filter> <filename>` is used to return all results that not matchs the filter

- Task 18 Letters only please 

	- Command `cat <filename> | grep ^[A-Za-z]` use filters to return all lines that start with Letters only.

- Task 19 A to Z

	- use `tr` to replace matched words
