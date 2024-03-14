# linux-shell
It is a basic shell that works on two principles.

1. **REPL loop**: This is the command line interface that consists of a loop which reads, evaluates the input, and prints the output and a new line for entering command/input.

2. **Parser-Executor**: This is the core part of a shell. 
    - The parser scans the input command and a process called tokenization takes place, which tokenizes the input. Tokens can be flags, keywords, numbers, etc. 
    - Then the parse converts the tokens into an AST (Abstract Syntax Tree). 
    - The executor executes the AST, and the process is completed or output is shown.

This shell can execute basic bash commands.
