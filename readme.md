<p align="center"> 	<a href="./readme.md"> 	English 	</a> 	/ 	 <a href="./readme-ru.md"> Русский </a>  /  <a href="./readme-zh-cn.md"> 	简体中文 	</a>  /  <a href="./readme-ar.md"> 	اَلْعَرَبِيَّةُ 	</a>  /  <a href="./readme-fa.md"> 	فارسی 	</a> </p>


<div align="center">

<img src="DragonFruit.OnionFruit/Assets/onionfruit.svg" width="100"/>

# OnionFruit™
Connect to the Tor network with minimal effort

</div>

## Overview
OnionFruit™ is a Tor Proxy Gateway that bootstraps Tor and updates the appropriate system settings to allow a wide range of applications to use the network (primarily Browsers) with a range of customisation and features through a clean, modern interface.

This is an open-source rewrite of the legacy OnionFruit™ Connect, originally published in late 2016 (with the last major redesign in 2020).

## Status
Currently, the program is still in development but is in a usable state.
Users are encouraged to download and use the program (either side-by-side or as a replacement for the legacy version) and report any bugs they encounter/provide feedback.

## Running OnionFruit™
> [!WARNING]
> This is a pre-release version of OnionFruit™ and may contain bugs. Please report any issues you encounter.
> Want the stable version? Check out the [legacy info page](https://github.com/dragonfruitnetwork/onionfruit/tree/onionfruit-connect-legacy-info).

OnionFruit™ builds are provided for the platforms below. Click the links to download the latest version:

- [Windows 10+ (x64)](https://github.com/dragonfruitnetwork/onionfruit/releases)

**NOTE: install.exe is the installer for the legacy version of OnionFruit™ Connect.**

## Features
🌍 Entry/Exit Location selection (with regular database updates)  
🌉 Bridge support: webtunnel snowflake meek conjure plain(vanilla) scramblesuit obfs3 obfs4  
🧱 Set allowed ports on restrictive firewalls  
🌐 Custom launch pages  
🛡️ No administrator privileges required to install and use  
🎮 Optional Discord status  
✨ Based on Windows 11 Fluent 2 Design  
⚖️ Fully open source

## Developing
You'll need the .NET 8 SDK and an IDE (Visual Studio or JetBrains Rider are recommended).
If working on the UI, familiarise yourself with [Avalonia UI](https://avaloniaui.net/) and [ReactiveUI](https://www.reactiveui.net/) as they're used everywhere.

To get started, clone the repo then open the solution file `DragonFruit.OnionFruit.sln`.

```bash
git clone https://github.com/dragonfruitnetwork/onionfruit
cd onionfruit
```

### Building from IDE
To build the project, use the provided build/run/debug functions provided by your IDE.

### Building from CLI
Build and run the project using `dotnet run` in a terminal of your choice:

```bash
dotnet run --project DragonFruit.OnionFruit.Windows
```

If you intend to work on a new feature/large change, it's recommended to open a new issue stating what you'd like to change to get an idea of what needs to be done/whether it's in scope, as we don't want to waste effort.

## License
> [!NOTE]
> This does not apply to dependencies used by OnionFruit (such as Tor) as they are licensed under different terms.

OnionFruit is licensed under LGPL-3. See [licence.md](licence.md) or reach out via inbox@dragonfruit.network for more info.
