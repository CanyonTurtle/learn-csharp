# Learn C#!

Here is some helpful information for how to learn c#, starting with setting up a command-line workflow on a windows 10 computer. My hope is that this document makes it easier for you to start your journey with learning to write programs, in the best way I know from my experience. This involves essentially learning 2 fundamentals at once.
1) how to use the command line
2) the basics of computer programming languages (with c# programs being the medium).

## 1. Learn enough to be fluent with the Command Line
This pays off big time. The best resource for this is here, and you don't have to do the whole thing,
but you can skim it at least. You will want to know the concept of files vs. directories, how to navigate to different directories, add/delete files, and move files.

http://rik.smith-unna.com/command_line_bootcamp/?id=e47yelvtdtk

## 2. Setup for C#
Linux is the best command line OS, it's far better than windows CMD, so you should use it!
- Install Windows Subsystem for Linux - https://docs.microsoft.com/en-us/windows/wsl/install-win10 This link tells you to open powershell (press the windows key and type powershell), run a command, restart your computer, and then open the windows store and search for ubuntu, and install it (it's orange). the first time you use it, it will have you set up a user account for your local computer, so do that and don't forget the password!

Next, we need a way to compile c# source code (the file you write) into c# programs. Monodevelop is a .NET platform (basically a collection of tools to work with c# in different scenarios, but for our purposes, it lets us compile and run programs on the command line).
- go here to install mono for Linux: https://www.mono-project.com/download/stable/#download-lin You should follow the instructions for ubuntu 16.04, you just copy and paste the terminal commands for step 1, and then run step 2.

- Now, you should have the `csc` unix command. In order to compile a program, you do something like this. Open a unix shell (aka a ubuntu terminal) within the same directory as a c# program file.
```
csc hello-world.cs
./hello-world.exe 
```
Line 1 will compile the hello-world source code into an executable program.
Line 2 will run the resulting executable.

That should be all you need to run a c# program on the command line!
Now, in order to make new c# programs, you can use whatever text editor you prefer (I suggest VScode or Vim), write or modify a program, save it, and then use the above steps to compile and run the program.

## 3. Learn about how to write programs in the C# programming language

Here is the best resource I know of:

https://www.tutorialspoint.com/csharp/index.htm

This is a comprehensive tutorial on c#, starting with the very basics. If you read it carefully and make example programs to follow along, this is the best way to do things. I think the best lesson to start on is the [program structure lesson](https://www.tutorialspoint.com/csharp/csharp_program_structure.htm), because the first two (overview and environment) don't necessarily apply to you, but you can read them anyhow.

Here is a roadmap of things you will want to learn how to do:

### beginning
This stuff is essential to starting, and it can be the most daunting. But stick with it!
- write a simple program
- compile a simple program
- run a simple program on the command line

### novice
The foremost information about writing programs.
- program layout
- variables
- for/if/while (control statements)
- functions

### intermediate
More involved and complex topics, but still highly essential knowledge.
- arrays
- classes / objects
- enums

### advanced (literally at the level of APCS at dougherty, so if you get to this point, you are doing very well)
Very relevant especially to game design with Unity.
- inheritance
- polymorphism
- file i/o (but this is really useful!!)

