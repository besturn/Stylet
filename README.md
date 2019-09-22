![Project Icon](StyletIcon.png) Stylet
======================================

[![NuGet](https://img.shields.io/nuget/v/Stylet.svg)](https://www.nuget.org/packages/Stylet/)
[![Build status](https://ci.appveyor.com/api/projects/status/nqucthach0x6gkil?svg=true)](https://ci.appveyor.com/project/canton7/stylet)

Introduction
------------

Stylet is a small but powerful ViewModel-first MVVM framework for WPF (.NET 4.5+ and .NET Core 3.0+), which allows you to write maintainable and extensible code in a way which is easy to test.
Stylet's aims are to:

 - Solve the blockers, niggles, and annoyances which hamper MVVM development without a framework, using simple but powerful concepts.
 - Be obvious to people picking up your project for the first time: there's very little magic
 - Be easy to verify/validate. The LOC count is low, and it comes with a very comprehensive test suite. The code is well-written and well-documented.
 - Be flexible while providing sensible defaults. Almost any part of the framework can be overridden if you wish, but you probably won't want to.

It is inspired by [Caliburn.Micro](http://caliburnmicro.com/), and shares many of its concepts, but removes most of the magic (replacing it with more powerful alternatives), and simplifies parts considerably by targeting only MVVM, WPF and .NET 4.5.


Getting Started
---------------

### .NET Framework

For .NET Framework projects, the quickest way to get started is to create a new "WPF Application" project, then install the NuGet package [Stylet.Start](https://www.nuget.org/packages/Stylet.Start).
This will install Stylet, and set up a simple skeleton project.

See [Quick Start](https://github.com/canton7/Stylet/wiki/Quick-Start) for more details.

If you want to set up your project manually, install the [Stylet](https://www.nuget.org/packages/Stylet) package, then follow the instructions in the [Quick Start](https://github.com/canton7/Stylet/wiki/Quick-Start).

Stylet requires .NET 4.5 (Visual Studio 2012 or higher).

### .NET Core

For .NET Core projects, install the [Stylet](https://www.nuget.org/packages/Stylet) package, then follow the instructions in the [Quick Start](https://github.com/canton7/Stylet/wiki/Quick-Start).

Stylet requires .NET Core 3.0.


Documentation
-------------

[The Wiki is the documentation source](https://github.com/canton7/Stylet/wiki).
There's loads of information there - go and have a look, or start with the [Quick Start](https://github.com/canton7/Stylet/wiki/Quick-Start).

Symbols
------

The source is also available when you are debugging, using [Source Link](https://github.com/dotnet/sourcelink).
Go to Debug -> Options and Settings -> General, and make the following changes:

 - Turn **off** "Enable Just My Code"
 - Turn **on** "Enable Source Link support"
 - Turn **off** "Enable .NET Framework source stepping". Yes, it is misleading, but if you don't, then Visual Studio will ignore your custom server order and only use its own servers.


Contributing
------------

Contributions are always welcome.
If you've got a problem or a question, [raise an issue](https://github.com/canton7/Stylet/issues).
If you've got code you want to contribute, please read [the Contributing guidelines](https://github.com/canton7/Stylet/wiki/Contributing) first of all.
Create a feature branch off the `develop` branch, add your changes there, and submit it as a pull request.
