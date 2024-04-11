# Operating Systems Project

## Description
* A small project in C that uses system functions to manipulate with the Linux operating system.
* The program processes various types of files like text files, bmp images and symbolic links.
* For BMP images encountered, the program creates a separate process to perform grayscale conversion.
* Output files are created in the specified output directory for each file processed, containing relevant information such as filename, size, permissions, and modification time.
* The program utilizes parallel processing techniques, creating separate processes for different tasks like file I/O and image processing
* It manages communication between parent and child and peer processes using inter-process communication mechanisms like pipes.
* The program incorporates error handling mechanisms, checking for errors during file operations, process creation, and system calls.
