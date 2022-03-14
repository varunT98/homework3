Homework 03 is to implement the linux commands in C programs.
I have used the given homework 02 from the canvas and extended with -e and -E commands.
For -E,-e commands i have declared two more flags for -E and -e commands in flagargs structure.
Using switch case and optarg i declared the flag value to 1 in the command line arguments.
Declare an array to optarg to get command line command "ls-l" and it is passed to an array. Similar process is carried out to E flag also.
We use fork() and execvp() functions here, fork() for creating a child process and execvp() for running commands. 
Arguments are passed to print function for checking the conditions. -E and -e is concatinated in an linux array, file path and also "".
for -e command i printed all files but not directories. -E created tar file that satisfies before the file conditions.
