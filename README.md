## C#
---------------

This a C# tutorial. I hope that's usefull.

### Commands to initialize and run a console project
<br><br>

1. Create a new console project:
<br>

~~~~ c#
    dotnet new console --framework net7.0 // net[version]
~~~~

<br>
2. In _Program.cs_, replace all content for this: 
<br>

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

<br>
3. In Visual Studio Code, if this is your first project, a little box will appear at the bottom left of the screen. Click in "Yes".
<br>

4. Run:
<br>

~~~~ c#
    dotnet run
~~~~


