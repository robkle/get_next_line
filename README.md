# get_next_line
C function that allows you to read a line ending with a newline character (or EOF), from a file descriptor.

## Usage<br />
int	get_next_line(const int fd, char **line)<br />
The file desciptor (fd) and pointer (**line) are passed to funtion get_next_line.<br />
The next line upto a newline character (or EOF) is stored in **line.<br />
The return value can be 1, 0 or -1 depending on whether a line has been read, the reading is completed, or an error occured.<br />
When implemented in a loop it will read the text line by line until the end of file is reached.<br />
The function is able to handle multiple file descriptors.

### Notes:
This project is part of my studies at Hive Helsinki. It was tested by 3 fellow Hive students as well as an automated evaluation system.


