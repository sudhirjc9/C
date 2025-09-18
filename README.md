GDB Commands

- gdb ./prog to start the program
- gdb and the file ./prog to reload a program after changes
- n or next to move to next line
- l or list to list source code
- Ctrl+x 1 to enter the TUI mode
- Ctrl+x o to shift between windows
- s or step to step into the source code
- br or break to set a breakpoint followed by a line number or function name
- c or continue to continue from a breakpoint
- set var=value to set a variable value
- p or print followed by a variable. Note: You can also dereference a variable (e.g., print *px) to see the dereferenced value
- bt or backtrace to get the stack frame
- f or finish to execute a function to completion
- info args to get information about the incoming function arguments
