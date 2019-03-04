

1. Setup a way to compile and run C# programs
Linux is the best command line OS, it's far better than windows CMD, so you should use it!
- Install Windows Subsystem for Linux - https://docs.microsoft.com/en-us/windows/wsl/install-win10 This link tells you to open powershell (press the windows key and type powershell), run a command, restart your computer, and then open the windows store and search for ubuntu, and install it (it's orange). the first time you use it, it will have you set up a user account for your local computer, so do that and don't forget the password!
Next, we need a way to run c# programs. Monodevelop is a .NET platform (basically a collection of tools to work with c# across multiple platforms, but for our purposes, it lets us compile and run c# on the command line).
- go here to install mono for Linux: https://www.mono-project.com/download/stable/#download-lin You should follow the instructions for ubuntu 16.04, you just copy and paste the terminal commands for step 1, and then run step 2.

- Now, you should have the `csc` unix command. In order to compile a program, you do something like this. Open a unix shell (aka a ubuntu terminal) within the same directory as a c# program file.
```
csc hello-world.cs # this will compile the hello-world source code into an executable program
./hello-world.exe # this will run the resulting executable
```

That should be all you need to run a c# program on the command line!
