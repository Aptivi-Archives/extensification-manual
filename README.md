---
description: Welcome to Extensification!
---

# 👋 Welcome!

Welcome to Extensification! It's a group of extensions that improve your experience of programming for .NET Core and .NET Framework applications.

To use this library, go to any page in the left side of the screen.

## Installation

This library is very easy to install. It's available at [NuGet](https://www.nuget.org/packages/Extensification/). Just follow these steps:

1. Open your project file (`.csproj` or `.fsproj`)
2. Place the `PackageReference` line on a property group like so:
   * `<PackageReference Include="Extensification" Version="x.x.x" />`
   * ...where `Version` is the current version of the library
3. Run a package restore using `dotnet restore`

If you follow these steps correctly, you should be able to use Extensification's functions.

Alternatively, you can repeat the above steps for different variants of Extensification, depending on the use-case:

* `Extensification.External`: If you want to use extensions supported by this library that extend external libraries, like Newtonsoft.Json
* `Extensification.Legacy`: If you rely on `Microsoft.VisualBasic` and you're coding in Visual Basic, you can use this variant.
* `Extensification.NetFX`: If you want to use some of the .NET features in .NET Framework projects
