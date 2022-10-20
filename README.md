# VSCode For C# Developers
Every C# developer should know how to build C# applications using VSCode. This repo will help you do just that.

## Getting Started
* Get VSCode: [code.visualstudio.com](https://code.visualstudio.com/)
* Get the .NET SDK: [.NET SDK Downloads](https://dotnet.microsoft.com/en-us/download/visual-studio-sdks)
* Install the C# extension: [C# Extension for VSCode](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)

## dotnet Commands
* `dotnet --info` - Gets you all of the information about the installed SDKs
* `dotnet new --list` - Gives you the list of installed templates
* `dotnet new <template> --name <name>` - Creates a new template item with the name you specify
* `dotnet sln <SolutionName> add <ProjectName>` - Adds a project to a solution
* `dotnet add <ProjectName> reference <LibraryName>` - Adds a reference to a library in a project
* `dotnet add package <PackageName>` - Adds a package to a project

## Tips
* If the `lauch.json` and `tasks.json` files do not get created, in the VSCode Command Pallette, run `.NET: Generate Assets for Build and Debug` to generate the files.
* To run a Console application that utilizes the `ReadLine` method, change the `console` entry to `integratedTerminal` from `integratedConsole`.
* To specify which web profile to use, add `"launchSettingsProfile": "<profileName>"` to the `launch.json` file.
* To allow for Hot Reload, change the `preLaunchTask` value from `build` to `watch` in the `launch.json` file.