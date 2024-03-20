# buffer-overflow-detection-prevention 

This is a simple C program demonstrating buffer overflow detection and prevention using stack canaries.

## Instructions

1. Compile the code using the following command: gcc -o buffer_overflow buffer_overflow.c
2. Run the program: ./buffer_overflow
3. Enter input when prompted. Test within buffer size and exceeding buffer size to observe detection and prevention mechanisms.

## Example
Enter input: abcde
No buffer overflow detected. Buffer contents: abcde

Enter input: abcdefghijkl
Error: Input exceeds buffer size. Potential buffer overflow detected.


## Contributing
Contributions are welcome. Feel free to fork and submit pull requests.



