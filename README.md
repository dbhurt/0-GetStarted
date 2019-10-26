# Getting started
You only need to be here if you have NEVER setup your machine to execute or build .net

While there are many tools, many languages, many environments, and a million different ways to do the same thing in this field, I'm only going to focus our efforts on .Net 3 and Visual Studio Code.

## Lets start:
1. Open a console window and enter *dotnet --version*
    1. If you have dotnet installed, you should get a version number returned. If you get a return like *3.0.100* move on
    1. If you don't get a number, or if you get a number lower than 3, or any other response, you need to install [.Net Core 3 SDK](https://dotnet.microsoft.com/download)
1. Assuming you don't have a IDE for development, we'll be focusing on Visual Studio Code which is a free tool.  Feel free to use whatever tool you want.  Download [Visual Studio Code](https://code.visualstudio.com/)
1. Since you're here, you already have a github account. Git is a separate beast used for version control. Don't worry about what that is for now.

## Let's make sure you're setup!
For some reason, doing things in the console has become the cool new (old) thing again, so if you aren't used to using the console, I'm sorry. Console aside, let's make sure everything is setup by creating a new console project, compile it, and execute it.
1. Open a console and change directory to a place you want your files to live, in my case *cd C:\mygit*
1. Enter this into the console: *dotnet new console -o "ConsoleApplication"*
        1. This tells .Net to create a new console application and will name the parent directory "ConsoleApplication", you can name this whatever you like
        1. Once you get a success message, cd into that directory *cd ConsoleApplication*
1. Now open it in Visual Studio: *code .*
1. Your Visual Studio Code should have openned with the newly created project and Hello World code already for you in Program.cs
1. Press F5, this code should compile for you and automatically execute.  You should see a bunch of jargon in your Terminal window and finally "Hello world!" printed within.  If so, congratulations, you have successfully setup your computer to develop with .net
