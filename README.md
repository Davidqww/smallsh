# smallsh

### Third Project for Operating Systems I (CS_344_400_F2017)

A basic shell that supports three built-in commands: exit, cd, status.
Handles all other commands by spawning child processes to perform
execvp().  

USAGE: [arg1 arg2 ...] [< input_file] [> output_file] [&]
