# AmiBroker .NET SDK and Community Plug-ins

This is yet another [AmiBroker](http://www.amibroker.com) plug-in SDK for .NET developers. As opposed to the official
C++ based [AmiBroker Development Kit](http://www.amibroker.com/download.html) (ADK) it can be used for data and/or
optimization plug-in authoring with .NET 4.5 / C#.

It is 100% free, no hidden charges, allowed for both personal and commercial use under [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0).

Contributions of any kind are welcome! Feel free to [fork](https://github.com/kriasoft/amibroker/fork_select)
this repo and send [pull requests](https://help.github.com/articles/using-pull-requests) with your updates.

### Prerequisites for Developers

 - [Visual Studio 2012](http://www.visualstudio.com) (preferred) or Visual Studio 2010
 - [NuGet Package Manager](http://www.nuget.org) a free Visual Studio extension
 - Microsoft .NET Framework 4.5 (can be easily downgraded by you if needed in project settings)

### Community Plug-ins for AmiBroker

 - [Yahoo Finance](http://finance.yahoo.com) real-time data plug-in for AmiBroker (planned)
 - [Finam](http://www.finam.ru) real-time data plug-in for AmiBroker (beta)

   **Download at** [sourceforge.net/projects/amibroker/files/](https://sourceforge.net/projects/amibroker/files/)

### Demo

![AmiBroker .NET SDK](http://i.imgur.com/PFYUlLw.png)

### Getting Started

Download and install [GitHub for Windows](http://windows.github.com/) if you havn't done it already. Click
[[Clone in Windows](github-windows://openRepo/https://github.com/kriasoft/amibroker)] button at the top of this page
in order to download the latest version of this project to your local folder.

Open 'AmiBroker .NET SDK.sln' solution file in Visual Studio, update information about your plug-in inside
`Plugin/Plugin.cs/GetPluginInfo()` method, add quotes related logic inside `Plugin/Plugin.cs/GetQuotesEx()` method,
build the project and you're done. Your first data plug-in is ready to be tested and debugged.

Note, that this project is just a port of the oficial C++ based ADK. In order to understand how it works it is
strongly recommended to read the official ADK manual which can be found inside
[ADK.zip](http://www.amibroker.com/bin/ADK.zip) file.

### Support & Feedback

Visit our [discussions board](https://groups.google.com/forum/?fromgroups=#!forum/amidev), feel free to ask questions
and leave feature requests.