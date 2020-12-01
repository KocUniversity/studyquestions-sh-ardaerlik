1. Please write “file1 is awesome” into a file called file1. Then, please append file1 with the contents of file1. 

2. Let us assume we have the plain text file fruits.txt with the following 12 lines of content:
peach
apple
banana
orange
avocado
cherry
strawberry
pineapple
blueberry
pear
kiwi
clementine
What will be the outcome of the following commands:?
cat fruits.txt | head | wc 
    A)	Nothing as head and wc do not have any input files
    B)	12
    C)	10
    D)	10 10 77

3. Write a sequence of vim commands to go to line 8, delete 3 words, go to the end of the file, go to the end of the current line, and paste the deleted words 5 times. This should not take you more than 13 key presses (Including pressing shift, alt-gr etc.).

4. Write a sequence of key pressed for vim that will enter visual block mode, move the cursor to the bottom of the current screen (not the file!), move to the end of the third word, yank the selected text, then go to the start of the current line. This should not take you more than 8 key presses.(Including pressing shift, alt-gr etc.)


5. Echo all the directory files in the directory called comp100_mt. Your command should only output the directory names in seperate lines.

6. Write a command which creates a directory and if the directory exists, do not give an error. For example, if there is a directory called comp100 and we are trying to create a directory called comp100, your command should not give any output and if the directory does not exist, it should create it.
7. Find your bash version with an appropriate command.
8. Recall that we can pass arguments to shell scripts like in the following:

```
$ ./script.sh "arg1" "arg2"..."argn"
```
Write a shell script that prints the first three arguments line by line. Call the script ./script.sh at least 3 arguments to make it work.
9. As a practice, create a directory: 'test'. Change the directory to test and create three .txt files. Then, return to the main directory and try to delete the test directory with rm command. You'll get an error. Get help from rm --help, and find a way to delete all files with rm command.

10. How do we search for the occurrences of a text in vim?

11. How do we cut/copy/paste in vim? 
