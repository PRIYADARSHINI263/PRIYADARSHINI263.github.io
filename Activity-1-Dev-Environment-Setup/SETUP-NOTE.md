Activity 1 – C/C++ Development Environment Setup



While setting up the C/C++ environment in VS Code, I faced an issue where the `gcc` command was not recognized in the terminal.

The problem was related to the compiler path not being properly added to the Windows PATH environment variable.

I checked the MinGW-w64 installation and found the compiler folder.

I added the required compiler `bin` folder to the PATH variable.

After restarting the terminal, I ran `gcc --version` to verify the setup.

The GCC version was displayed successfully, and I was able to compile and run my `hello.c` program.

The program successfully displayed Hello, World! in the terminal.



