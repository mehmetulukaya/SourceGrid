[![Build status](https://ci.appveyor.com/api/projects/status/rgpayylq208kwt3g/branch/master?svg=true)](https://ci.appveyor.com/project/mehmetulukaya/sourcegrid-mehmetulukaya/branch/master) 
 ![NuGet Downloads](https://img.shields.io/nuget/dt/SourceGrid-mehmetulukaya?style=flat) [![NuGet version](https://badge.fury.io/nu/SourceGrid-mehmetulukaya.svg)](https://badge.fury.io/nu/SourceGrid-mehmetulukaya)


## SourceGrid

SourceGrid is a free open source grid control. Supports virtual grid, custom cells and editors, advanced formatting options and many others features
SourceGrid is a Windows Forms control written entirely in C#, goal is to create a simple but flexible grid to use in all of the cases in which it is necessary to visualize or to change a series of data in a table format. There are a lot of controls of this type available, but often are expensive, difficult to be customize or not compatible with .NET. SourceGrid allows users to have customizable datasource which is not in DataSet format.

![Overview Image](/Doc/Images/SourceGrid_Overview.png)

For more detailed information, Refer article at [CodeProject](https://www.codeproject.com/Articles/3531/SourceGrid-Open-Source-C-Grid-Control)

Note: this fork is created by Mehmet Ulukaya to support .NET 8.

# Preconditions

- Visual Studio 2022
- .NET 8

# Recent Changes

- Upgraded project file format to SDK-style using [.NET Upgrade Assistant](https://docs.microsoft.com/en-us/dotnet/core/porting/upgrade-assistant-overview).
- Changed target framework from .NET 3.5 to .NET 8.
- Fixed obsolete code. For example: ContextMenu is replaced by ContextMenuStrip.
- Removed unused code files.
- Use [MinVer](https://github.com/adamralph/minver) for easy versioning with tag name.
- Automatically deploy the package to NuGet.org.

See [CHANGELOG.md](CHANGELOG.md) for more information.

See https://github.com/siemens/sourcegrid for original README.

# License
This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/siemens/sourcegrid/blob/master/LICENSE) file for details 


