## C#

This a C# tutorial. I hope that's usefull.

### Commands to initialize and run a console project

1. Create a new console project:
    ~~~~ c#
        dotnet new console --framework net7.0 // net[version]
    ~~~~

2. In _Program.cs_, replace all content for this:

    ~~~~ c#
        namespace HelloWorld
        {
            class Program
            {
                static void Main(string[] args)
                {
                    Console.WriteLine("Hello, World!");
                }
            }
        }
    ~~~~
 
3. In Visual Studio Code, if this is your first project, a little box will appear at the bottom left of the screen. Click in "Yes".

4. Run:
    ~~~~ c#
        dotnet run
    ~~~~