# ASCOM-Device-Template

## Introduction

The official ASCOM .NET Templates available with the [ASCOM Platform Developer Components](https://ascom-standards.org/Downloads/PlatDevComponents.htm) use the Visual Studio template wizard. Therefore, it is required to use Visual Studio to benefit of the template. To use the template in an other IDE, the only way is to uncompress the template zip file provided by the [ASCOM Platform Developer Components](https://ascom-standards.org/Downloads/PlatDevComponents.htm) and manually edit the files, removing not required files, ...

This project, allows to create an ASCOM device project with the `dotnet new` command (require the .NET Core/.NET 5 SDK).

More information on dotnet templating : https://github.com/dotnet/templating#info-for-dotnet-new-users

# Install

The installation and the use of the template require the [.NET Core or .NET 5](https://dotnet.microsoft.com/download) to be installed.

## From the sources

Download or clone the [source code](https://github.com/elendil-software/ASCOM-Device-Template/tree/main).

Open a command line terminal (cmd or powershell) in the template root directory 

Run the command `dotnet new --install ./content/`

## From the NuGet package

Download the NuGet package from the [releases page](https://github.com/elendil-software/ASCOM-Device-Template/releases)

Execute the command : `dotnet new -i .\ASCOM.Device.Template.0.1.0-beta.1.nupkg`

# Usage

To create a new driver project, execute the command `dotnet new ascomdevice --name MyDome --deviceType Dome`

For complete help, execute `dotnet new ascomdevice -h`
