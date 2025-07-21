# File-management-tool
*COMPANY*:CODTECH IT SOLUTIONS

*NAME*:SAPKAL VAISHNAVI GANESH

*INTERN ID*: CTO8DG447

*DOMAIN*: C++

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTOSH 

The provided C++ program is a simple and interactive file management tool that demonstrates basic file input and output (I/O) operations. It allows users to perform three primary actions on a file named example.txt: write new content to the file, append additional content to the existing file, and read the contents of the file. The program utilizes standard libraries such as <iostream> for input and output, <fstream> for file handling, and <string> for string manipulation.

The program is structured using three functions: writeToFile, appendToFile, and readFromFile. Each function is responsible for a specific file operation. The writeToFile function opens the file in output mode (ios::out), which clears any existing content in the file before writing new data. It first checks if the file opens successfully; if not, it displays an error message. It then prompts the user to enter text input, reads the entire line using getline, and writes it to the file.

The appendToFile function, on the other hand, opens the file in append mode (ios::app), ensuring that new data is added to the end of the file without modifying its existing content. Like the writeToFile function, it validates that the file opens successfully and then appends the user input using getline.

The readFromFile function is used to read and display the contents of the file. It opens the file in input mode (ios::in) and reads it line by line using a while loop with getline. Each line is printed to the console until the end of the file is reached. If the file cannot be opened, an error message is shown.

The main function acts as the user interface for the program. It continuously displays a menu using a do-while loop, giving users four options: write, append, read, or exit. The user's input is captured through cin, and a switch statement determines which function to execute based on the user's choice. If the user inputs an invalid choice, the program prompts them to try again. The loop continues until the user selects option 4 to exit the program.

One notable detail in both the writeToFile and appendToFile functions is the use of cin.ignore() before getline(). This is necessary to clear any leftover newline characters from previous cin operations, ensuring that the user’s input is read correctly.

Overall, this program is a useful demonstration of file handling in C++, combining file streams with user input in a simple, menu-driven format. It teaches key programming concepts such as file I/O, error handling, string manipulation, and control structures, making it an excellent example for beginners learning about file operations in C++
