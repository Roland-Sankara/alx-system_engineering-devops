## 0x02-Shell_Redirections
This doc descridbes what each script file does.

### 0-hello_world
This script prints "Hello, World" followed by a newline to the standard ouput. it uses the echo commad to achieve this.

### 1-confused_smiley
This script displays a confused smiley to the standard output. It uses the echo command with the -e flag.

### 2-hellofile
This script displays the content of the /etc/passwd file. It used the cat command.

## 3-twofiles
This script displays the contents of two files. /ectc/passwd and /etc/hosts with the helpf of the cat command.

### 4-lastlines
This script displays the last 10 lines of the /etc/passwd file.This is by the help of the tail command.

### 5-firstlines
This scrit displays the fist 10 lines of the /etc/passwd file. Uses the head command

### 6-third_line
This script displays the third line of the file iacta. It uses a pipeline of command: cat head and tail

### 8-cwd_state
This script writes the output of the command `ls -la` into the file ls_cwd_content. This is by using the `ls -la > ls_cwd_content`

### 9-duplicate_last_line
This script duplicate the last ine of the file iacta. It uses the tail command to get the last linein the file and appends it to the file iacta
