The 6 Steps to C++ Development are as follows:

# Step 1: Define the Problem that you want to Solve
# Step 2: How are you going to solve the problem

Typically, good solutions have the following characteristics:

- They are straightforward (not overly complicated or confusing).
- They are well documented (especially around any assumptions being made or limitations).
- They are built modularly, so parts can be reused or changed later without impacting other parts of the program.
- They can recover gracefully or give useful error messages when something unexpected happens.

# Step 3:  Write The Program

# Step 4: Compiling your Source Code

First, the compiler checks your C++ code to make sure it follows the rules of the C++ language. If it does not, the compiler will give you an error (and the corresponding line number) to help pinpoint what needs fixing. The compilation process will also be aborted until the error is fixed.

Second, the compiler translates your C++ code into machine language instructions. These instructions are stored in an intermediate file called an **object file**. The object file also contains other data that is required or useful in subsequent steps

Object files are named .o

![[Pasted image 20260202210331.png]]

# Step 5: Linking object files and libraries and creating the desired output file

The linkers job is to combine all the object files and produce the desired output file.

# Steps 6 & 7, Testing and Debugging the Program
