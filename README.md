<p align="center">
<img height="128" src="BetaSharp.Launcher/logo.png" alt="BetaSharp">
<h1 align="center">BetaSharp: Offline Mode Restored</h1>
<p align="center">An enhanced version of Minecraft Beta 1.7.3, written in C#.</p>
</p>
<p align="center">
<img src="https://img.shields.io/badge/language-C%23-512BD4" alt="C#">
<img src="https://img.shields.io/badge/framework-.NET-512BD4" alt=".NET">
</p>


# Notice

> [!IMPORTANT]
> To use this software, you must own a legally obtained copy of the game. The offline mode provided by the launcher is intended solely for debugging, testing, and software development purposes. It is not intended to bypass licensing or authentication systems, or to enable use of the game without a valid license. Please purchase Minecraft at [minecraft.net](https://www.minecraft.net).

## Running

The launcher is the recommended way to play, it authenticates with your Microsoft account and starts the client automatically. \
Clone the repository and run the following commands.

```
cd BetaSharp.Launcher
dotnet run --configuration Release
```

## Building

Clone the repository and make sure the .NET 10 SDK is installed. For installation, visit [dotnet.microsoft.com](https://dotnet.microsoft.com/en-us/download). \
The Website lists instructions for downloading the SDK on Windows, macOS and Linux.

It is recommended to build with `--configuration Release` for better performance. \
The server and client expect the JAR file to be in their running directory.

```
cd BetaSharp.(Launcher/Client/Server)
dotnet build
```
