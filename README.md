# Live Property Explorer bug
[![Bug Link](https://developercommunity.visualstudio.com/content/problem/428997/live-property-explorer-shows-incorrect-style-for-w.html)](https://developercommunity.visualstudio.com/content/problem/428997/live-property-explorer-shows-incorrect-style-for-w.html)

## Repro Steps

* Build LivePropertyExplorerIncorrectStyle.sln 
* Ensure that XAML debug tools are enabled
* Debug LivePropertyExplorerIncorrectStyle.csproj (a WPF application)
* Select MainWindow in the Live Visual Tree

Observe that 'Style (Window Default)' in app.xaml is listed for the window and a SolidColorBrush of #FBADF00D is shown for the Background
The runtime background of the window instead has the default white background.

NOTE: While this example only modifies the background property I've observed the same behavior for any properties set in a Style targetting {x:Type Window}


## Visual Studio version info
Microsoft Visual Studio Professional 2017 
Version 15.9.5
VisualStudio.15.Release/15.9.5+28307.280
Microsoft .NET Framework
Version 4.7.03056

Installed Version: Professional

Visual C++ 2017   00370-20005-91345-AA208
Microsoft Visual C++ 2017

ASP.NET and Web Tools 2017   15.9.04012.0
ASP.NET and Web Tools 2017

ASP.NET Core Razor Language Services   15.8.31590
Provides languages services for ASP.NET Core Razor.

ASP.NET Web Frameworks and Tools 2017   5.2.60913.0
For additional information, visit https://www.asp.net/

Azure App Service Tools v3.0.0   15.9.03024.0
Azure App Service Tools v3.0.0

C# Tools   2.10.0-beta2-63501-03+b9fb1610c87cccc8ceb74a770dba261a58e39c4a
C# components used in the IDE. Depending on your project type and settings, a different version of the compiler may be used.

Cake for Visual Studio   0.1.2.0
Adds support for the Cake build tool in Visual Studio 2015 and 2017. Includes support for the Task Runner Explorer, new templates and bootstrapping important Cake files.

Common Azure Tools   1.10
Provides common services for use by Azure Mobile Services and Microsoft Azure Tools.

JavaScript Language Service   2.0
JavaScript Language Service

JetBrains ReSharper Ultimate 2018.3.1   Build 183.0.20181225.200351
JetBrains ReSharper Ultimate package for Microsoft Visual Studio. For more information about ReSharper Ultimate, visit http://www.jetbrains.com/resharper. Copyright © 2019 JetBrains, Inc.

Microsoft Continuous Delivery Tools for Visual Studio   0.4
Simplifying the configuration of Azure DevOps pipelines from within the Visual Studio IDE.

Microsoft JVM Debugger   1.0
Provides support for connecting the Visual Studio debugger to JDWP compatible Java Virtual Machines

Microsoft Library Manager   1.0
Install client-side libraries easily to any web project

Microsoft MI-Based Debugger   1.0
Provides support for connecting Visual Studio to MI compatible debuggers

Microsoft Visual C++ Wizards   1.0
Microsoft Visual C++ Wizards

Microsoft Visual Studio Tools for Containers   1.1
Develop, run, validate your ASP.NET Core applications in the target environment. F5 your application directly into a container with debugging, or CTRL + F5 to edit & refresh your app without having to rebuild the container.

Microsoft Visual Studio VC Package   1.0
Microsoft Visual Studio VC Package

MLGen Package Extension   1.0
MLGen Package Visual Studio Extension Detailed Info

NuGet Package Manager   4.6.0
NuGet Package Manager in Visual Studio. For more information about NuGet, visit http://docs.nuget.org/.

P4VS - Helix Plugin for Visual Studio   2018.4.174.6096
P4VS is the Helix Plugin for Microsoft Visual Studio. P4VS provides developers working within Visual Studio access to Helix version control features, including check in/check out, view file history, and more.

ProjectServicesPackage Extension   1.0
ProjectServicesPackage Visual Studio Extension Detailed Info

ResourcePackage Extension   1.0
ResourcePackage Visual Studio Extension Detailed Info

ResourcePackage Extension   1.0
ResourcePackage Visual Studio Extension Detailed Info

SQL Server Data Tools   15.1.61901.03220
Microsoft SQL Server Data Tools

Test Adapter for Boost.Test   1.0
Enables Visual Studio's testing tools with unit tests written for Boost.Test.  The use terms and Third Party Notices are available in the extension installation directory.

Test Adapter for Google Test   1.0
Enables Visual Studio's testing tools with unit tests written for Google Test.  The use terms and Third Party Notices are available in the extension installation directory.

TypeScript Tools   15.9.20918.2001
TypeScript Tools for Microsoft Visual Studio

Visual Basic Tools   2.10.0-beta2-63501-03+b9fb1610c87cccc8ceb74a770dba261a58e39c4a
Visual Basic components used in the IDE. Depending on your project type and settings, a different version of the compiler may be used.

Visual Studio Code Debug Adapter Host Package   1.0
Interop layer for hosting Visual Studio Code debug adapters in Visual Studio

Visual Studio Tools for CMake   1.0
Visual Studio Tools for CMake

Visual Studio Tools for Containers   1.0
Visual Studio Tools for Containers