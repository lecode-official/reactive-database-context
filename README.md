# Reactive Database Context

![Reactive Database Context Logo](https://github.com/lecode-official/reactive-database-context/blob/master/Documentation/Images/Banner.png "Reactive Database Context Logo")

> **IMPORTANT** This project is no longer actively in development.

A simple and light-weight wrapper around Entity Framework's `DbContext`, which makes it possible to react to changes using the Reactive Extensions.

## Using the Project

The project is available on NuGet. You can find the WPF version here: https://www.nuget.org/packages/System.Data.Entity.Reactive.

```batch
PM> Install-Package System.Data.Entity.Reactive
```

If you want to you can download and manually build the solution. The project was built using Visual Studio 2015. Basically any version of Visual Studio 2015 will
suffice, no extra plugins or tools are needed (except for the `System.Windows.Mvvm.nuproj` project, which needs the
[NuBuild Project System](https://visualstudiogallery.msdn.microsoft.com/3efbfdea-7d51-4d45-a954-74a2df51c5d0) Visual Studio extension for building the NuGet
package). Just clone the Git repository, open the solution in Visual Studio, and build the solution.

```batch
git clone https://github.com/lecode-official/reactive-database-context
```

## Contributions

Currently we are not accepting any contributors, but if you want to help, we would greatly appreciate feedback and bug reports. To file a bug, please use GitHub's
issue system. Alternatively, you can clone the repository and send us a pull request.
