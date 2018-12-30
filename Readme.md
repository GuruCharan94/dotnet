# MiniProfiler for .NET (and .NET Core)

[![Build status](https://ci.appveyor.com/api/projects/status/sieyhfuhjww5ur5i/branch/master?svg=true)](https://ci.appveyor.com/project/StackExchange/dotnet/branch/master)

Welcome to MiniProfiler for .NET, ASP.NET, ASP.NET Core, ASP.NET MVC and generally all the combinations of those words. Documentation for MiniProfiler for .NET is in `/docs`, accessible via GitHub pages at: [miniprofiler.com/dotnet](http://miniprofiler.com/dotnet/). General information for MiniProfiler across platforms can be found at [miniprofiler.com](http://miniprofiler.com/).

The current major version of MiniProfiler is v4.

## Handy Links

* Documentation
  * [Getting started for ASP.NET (*not* .NET Core)](http://miniprofiler.com/dotnet/AspDotNet)
  * [Getting started for ASP.NET Core](http://miniprofiler.com/dotnet/AspDotNetCore)
  * [How-To Profile Code](http://miniprofiler.com/dotnet/HowTo/ProfileCode)
  * [NuGet Packages](http://miniprofiler.com/dotnet/NuGet)
  * [How-To Upgrade From MiniProfiler V3](http://miniprofiler.com/dotnet/HowTo/UpgradeFromV3)
* Samples
  * [ASP.NET Core Sample App](https://github.com/MiniProfiler/dotnet/tree/master/samples/Samples.AspNetCore)
  * [ASP.NET MVC 5 Sample App](https://github.com/MiniProfiler/dotnet/tree/master/samples/Samples.Mvc5)
  * [Console Application](https://github.com/MiniProfiler/dotnet/tree/master/samples/Samples.Console)

## Building

To build the MiniProfiler solution in Visual Studio, you'll need:
- Visual Studio 2017 (or the .NET 2.x SDK)
- The [Web Compiler](https://marketplace.visualstudio.com/items?itemName=MadsKristensen.WebCompiler) extension
  - Note: no extension is needed if building via `buid.cmd` or `build.ps1` in the repository root. They pull it in via a package.

## Package Status

MyGet Pre-release feed: https://www.myget.org/gallery/miniprofiler

| Package | NuGet Stable | NuGet Pre-release | Downloads | MyGet |
| ------- | ------------ | ----------------- | --------- | ----- |
| [MiniProfiler](https://www.nuget.org/packages/MiniProfiler/) | [![MiniProfiler](https://img.shields.io/nuget/v/MiniProfiler.svg)](https://www.nuget.org/packages/MiniProfiler/) | [![MiniProfiler](https://img.shields.io/nuget/vpre/MiniProfiler.svg)](https://www.nuget.org/packages/MiniProfiler/) | [![MiniProfiler](https://img.shields.io/nuget/dt/MiniProfiler.svg)](https://www.nuget.org/packages/MiniProfiler/) | [![MiniProfiler MyGet](https://img.shields.io/myget/miniprofiler/vpre/MiniProfiler.svg)](https://www.myget.org/feed/miniprofiler/package/nuget/MiniProfiler) |
| [MiniProfiler.AspNetCore](https://www.nuget.org/packages/MiniProfiler.AspNetCore/) | [![MiniProfiler.AspNetCore](https://img.shields.io/nuget/v/MiniProfiler.AspNetCore.svg)](https://www.nuget.org/packages/MiniProfiler.AspNetCore/) | [![MiniProfiler.AspNetCore](https://img.shields.io/nuget/vpre/MiniProfiler.AspNetCore.svg)](https://www.nuget.org/packages/MiniProfiler.AspNetCore/) | [![MiniProfiler.AspNetCore](https://img.shields.io/nuget/dt/MiniProfiler.AspNetCore.svg)](https://www.nuget.org/packages/MiniProfiler.AspNetCore/) | [![MiniProfiler.AspNetCore MyGet](https://img.shields.io/myget/miniprofiler/vpre/MiniProfiler.AspNetCore.svg)](https://www.myget.org/feed/miniprofiler/package/nuget/MiniProfiler.AspNetCore) |
| [MiniProfiler.AspNetCore.Mvc](https://www.nuget.org/packages/MiniProfiler.AspNetCore.Mvc/) | [![MiniProfiler.AspNetCore.Mvc](https://img.shields.io/nuget/v/MiniProfiler.AspNetCore.Mvc.svg)](https://www.nuget.org/packages/MiniProfiler.AspNetCore.Mvc/) | [![MiniProfiler.AspNetCore.Mvc](https://img.shields.io/nuget/vpre/MiniProfiler.AspNetCore.Mvc.svg)](https://www.nuget.org/packages/MiniProfiler.AspNetCore.Mvc/) | [![MiniProfiler.AspNetCore.Mvc](https://img.shields.io/nuget/dt/MiniProfiler.AspNetCore.Mvc.svg)](https://www.nuget.org/packages/MiniProfiler.AspNetCore.Mvc/) | [![MiniProfiler.AspNetCore.Mvc MyGet](https://img.shields.io/myget/miniprofiler/vpre/MiniProfiler.AspNetCore.Mvc.svg)](https://www.myget.org/feed/miniprofiler/package/nuget/MiniProfiler.AspNetCore.Mvc) |
| [MiniProfiler.EF6](https://www.nuget.org/packages/MiniProfiler.EF6/) | [![MiniProfiler.EF6](https://img.shields.io/nuget/v/MiniProfiler.EF6.svg)](https://www.nuget.org/packages/MiniProfiler.EF6/) | [![MiniProfiler.EF6](https://img.shields.io/nuget/vpre/MiniProfiler.EF6.svg)](https://www.nuget.org/packages/MiniProfiler.EF6/) | [![MiniProfiler.EF6](https://img.shields.io/nuget/dt/MiniProfiler.EF6.svg)](https://www.nuget.org/packages/MiniProfiler.EF6/) | [![MiniProfiler.EF6 MyGet](https://img.shields.io/myget/miniprofiler/vpre/MiniProfiler.EF6.svg)](https://www.myget.org/feed/miniprofiler/package/nuget/MiniProfiler.EF6) |
| [MiniProfiler.EntityFrameworkCore](https://www.nuget.org/packages/MiniProfiler.EntityFrameworkCore/) | [![MiniProfiler.EntityFrameworkCore](https://img.shields.io/nuget/v/MiniProfiler.EntityFrameworkCore.svg)](https://www.nuget.org/packages/MiniProfiler.EntityFrameworkCore/) | [![MiniProfiler.EntityFrameworkCore](https://img.shields.io/nuget/vpre/MiniProfiler.EntityFrameworkCore.svg)](https://www.nuget.org/packages/MiniProfiler.EntityFrameworkCore/) | [![MiniProfiler.EntityFrameworkCore](https://img.shields.io/nuget/dt/MiniProfiler.EntityFrameworkCore.svg)](https://www.nuget.org/packages/MiniProfiler.EntityFrameworkCore/) | [![MiniProfiler.EntityFrameworkCore MyGet](https://img.shields.io/myget/miniprofiler/vpre/MiniProfiler.EntityFrameworkCore.svg)](https://www.myget.org/feed/miniprofiler/package/nuget/MiniProfiler.EntityFrameworkCore) |
| [MiniProfiler.Mvc5](https://www.nuget.org/packages/MiniProfiler.Mvc5/) | [![MiniProfiler.Mvc5](https://img.shields.io/nuget/v/MiniProfiler.Mvc5.svg)](https://www.nuget.org/packages/MiniProfiler.Mvc5/) | [![MiniProfiler.Mvc5](https://img.shields.io/nuget/vpre/MiniProfiler.Mvc5.svg)](https://www.nuget.org/packages/MiniProfiler.Mvc5/) | [![MiniProfiler.Mvc5](https://img.shields.io/nuget/dt/MiniProfiler.Mvc5.svg)](https://www.nuget.org/packages/MiniProfiler.Mvc5/) | [![MiniProfiler.Mvc5 MyGet](https://img.shields.io/myget/miniprofiler/vpre/MiniProfiler.Mvc5.svg)](https://www.myget.org/feed/miniprofiler/package/nuget/MiniProfiler.Mvc5) |
| [MiniProfiler.Providers.MongoDB](https://www.nuget.org/packages/MiniProfiler.Providers.MongoDB/) | [![MiniProfiler.Providers.MongoDB](https://img.shields.io/nuget/v/MiniProfiler.Providers.MongoDB.svg)](https://www.nuget.org/packages/MiniProfiler.Providers.MongoDB/) | [![MiniProfiler.Providers.MongoDB](https://img.shields.io/nuget/vpre/MiniProfiler.Providers.MongoDB.svg)](https://www.nuget.org/packages/MiniProfiler.Providers.MongoDB/) | [![MiniProfiler.Providers.MongoDB](https://img.shields.io/nuget/dt/MiniProfiler.Providers.MongoDB.svg)](https://www.nuget.org/packages/MiniProfiler.Providers.MongoDB/) | [![MiniProfiler.Providers.MongoDB MyGet](https://img.shields.io/myget/miniprofiler/vpre/MiniProfiler.Providers.MongoDB.svg)](https://www.myget.org/feed/miniprofiler/package/nuget/MiniProfiler.Providers.MongoDB) |
| [MiniProfiler.Providers.MySql](https://www.nuget.org/packages/MiniProfiler.Providers.MySql/) | [![MiniProfiler.Providers.MySql](https://img.shields.io/nuget/v/MiniProfiler.Providers.MySql.svg)](https://www.nuget.org/packages/MiniProfiler.Providers.MySql/) | [![MiniProfiler.Providers.MySql](https://img.shields.io/nuget/vpre/MiniProfiler.Providers.MySql.svg)](https://www.nuget.org/packages/MiniProfiler.Providers.MySql/) | [![MiniProfiler.Providers.MySql](https://img.shields.io/nuget/dt/MiniProfiler.Providers.MySql.svg)](https://www.nuget.org/packages/MiniProfiler.Providers.MySql/) | [![MiniProfiler.Providers.MySql MyGet](https://img.shields.io/myget/miniprofiler/vpre/MiniProfiler.Providers.MySql.svg)](https://www.myget.org/feed/miniprofiler/package/nuget/MiniProfiler.Providers.MySql) |
| [MiniProfiler.Providers.Redis](https://www.nuget.org/packages/MiniProfiler.Providers.Redis/) | [![MiniProfiler.Providers.Redis](https://img.shields.io/nuget/v/MiniProfiler.Providers.Redis.svg)](https://www.nuget.org/packages/MiniProfiler.Providers.Redis/) | [![MiniProfiler.Providers.Redis](https://img.shields.io/nuget/vpre/MiniProfiler.Providers.Redis.svg)](https://www.nuget.org/packages/MiniProfiler.Providers.Redis/) | [![MiniProfiler.Providers.Redis](https://img.shields.io/nuget/dt/MiniProfiler.Providers.Redis.svg)](https://www.nuget.org/packages/MiniProfiler.Providers.Redis/) | [![MiniProfiler.Providers.Redis MyGet](https://img.shields.io/myget/miniprofiler/vpre/MiniProfiler.Providers.Redis.svg)](https://www.myget.org/feed/miniprofiler/package/nuget/MiniProfiler.Providers.Redis) |
| [MiniProfiler.Providers.SqlServer](https://www.nuget.org/packages/MiniProfiler.Providers.SqlServer/) | [![MiniProfiler.Providers.SqlServer](https://img.shields.io/nuget/v/MiniProfiler.Providers.SqlServer.svg)](https://www.nuget.org/packages/MiniProfiler.Providers.SqlServer/) | [![MiniProfiler.Providers.SqlServer](https://img.shields.io/nuget/vpre/MiniProfiler.Providers.SqlServer.svg)](https://www.nuget.org/packages/MiniProfiler.Providers.SqlServer/) | [![MiniProfiler.Providers.SqlServer](https://img.shields.io/nuget/dt/MiniProfiler.Providers.SqlServer.svg)](https://www.nuget.org/packages/MiniProfiler.Providers.SqlServer/) | [![MiniProfiler.Providers.SqlServer MyGet](https://img.shields.io/myget/miniprofiler/vpre/MiniProfiler.Providers.SqlServer.svg)](https://www.myget.org/feed/miniprofiler/package/nuget/MiniProfiler.Providers.SqlServer) |
| [MiniProfiler.Providers.SqlServerCe](https://www.nuget.org/packages/MiniProfiler.Providers.SqlServerCe/) | [![MiniProfiler.Providers.SqlServerCe](https://img.shields.io/nuget/v/MiniProfiler.Providers.SqlServerCe.svg)](https://www.nuget.org/packages/MiniProfiler.Providers.SqlServerCe/) | [![MiniProfiler.Providers.SqlServerCe](https://img.shields.io/nuget/vpre/MiniProfiler.Providers.SqlServerCe.svg)](https://www.nuget.org/packages/MiniProfiler.Providers.SqlServerCe/) | [![MiniProfiler.Providers.SqlServerCe](https://img.shields.io/nuget/dt/MiniProfiler.Providers.SqlServerCe.svg)](https://www.nuget.org/packages/MiniProfiler.Providers.SqlServerCe/) | [![MiniProfiler.Providers.SqlServerCe MyGet](https://img.shields.io/myget/miniprofiler/vpre/MiniProfiler.Providers.SqlServerCe.svg)](https://www.myget.org/feed/miniprofiler/package/nuget/MiniProfiler.Providers.SqlServerCe) |
| [MiniProfiler.Shared](https://www.nuget.org/packages/MiniProfiler.Shared/) | [![MiniProfiler.Shared](https://img.shields.io/nuget/v/MiniProfiler.Shared.svg)](https://www.nuget.org/packages/MiniProfiler.Shared/) | [![MiniProfiler.Shared](https://img.shields.io/nuget/vpre/MiniProfiler.Shared.svg)](https://www.nuget.org/packages/MiniProfiler.Shared/) | [![MiniProfiler.Shared](https://img.shields.io/nuget/dt/MiniProfiler.Shared.svg)](https://www.nuget.org/packages/MiniProfiler.Shared/) | [![MiniProfiler.Shared MyGet](https://img.shields.io/myget/miniprofiler/vpre/MiniProfiler.Shared.svg)](https://www.myget.org/feed/miniprofiler/package/nuget/MiniProfiler.Shared) |

## License

MiniProfiler is licensed under the [MIT license](https://github.com/MiniProfiler/dotnet/blob/master/LICENSE.txt).
