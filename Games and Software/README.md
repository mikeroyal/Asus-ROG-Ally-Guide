# Games and Software

[Back to Home](/README.md#table-of-contents)

## Table of Contents

- [Getting Software](#getting-software)
- [Gaming on Windows](./windows%20gaming.md)
- [Gaming on Linux](./linux%20gaming.md)
- [Operating Systems](./Operating%20Systems.md)
  - [Windows](./Operating%20Systems.md#windows)
  - [Linux](./Operating%20Systems.md#linux)

## Getting Software

[Back to the Top](https://github.com/mikeroyal/Steam-Deck-Guide#table-of-contents)


### Getting Software on Windows

[Windows Package Manager](https://docs.microsoft.com/en-us/windows/package-manager/) is a comprehensive [package manager solution](https://docs.microsoft.com/en-us/windows/package-manager/#understanding-package-managers) that consists of a command line tool and set of services for installing applications on Windows 10. Developers can use the winget command line tool to discover, install, upgrade, remove and configure a curated set of applications. After it is installed, developers can access winget via the [Windows Terminal](https://docs.microsoft.com/en-us/windows/terminal/), [PowerShell](https://docs.microsoft.com/en-us/powershell/), or the Command Prompt.

**[Using the winget tool to install and manage software packages](https://docs.microsoft.com/en-us/windows/package-manager/winget/)**

**[Submitting packages to Windows Package Manager](https://docs.microsoft.com/en-us/windows/package-manager/package/)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/115297923-9e764880-a111-11eb-9eb6-7bb9ab0b6192.png">
  <br />
</p>

[WingetUI](https://github.com/martinet101/WingetUI) is a GUI Store for the most common cli package managers, such as Winget and Scoop. It's developed by [Martí Climent AKA martinet101](https://github.com/martinet101).

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/169711126-0d56a8fe-229e-4d4b-a8c5-d44c1a074b59.png">
  <br />
</p>

[Microsoft PowerToys](https://github.com/microsoft/PowerToys) is a set of utilities for power users to tune and streamline their Windows 10 experience for greater productivity. To get more information on [PowerToys](https://docs.microsoft.com/windows/powertoys/), or any other tools and resources for [Windows development environments](https://docs.microsoft.com/windows/dev-environment/overview), go to [docs.microsoft.com](https://docs.microsoft.com/windows/powertoys/).

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/111210946-17223c00-858b-11eb-90c1-be411aab7107.png">
</p>

[Homebrew](https://brew.sh) is the missing Package Manager for your macOS, Linux, and Windows 10 (with [Windows Subsystem for Linux (WSL)](https://docs.microsoft.com/en-us/windows/wsl/)) system. Homebrew is an essential tool for any developer/engineer.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/115158810-ee3b0e00-a044-11eb-98b4-3c0dc35ff972.png">
  <br />
</p>

[Ninite](https://ninite.com/) is a package management system offering that enables users automatically install popular applications for their Windows 10 OS.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/110880123-f740fe80-8292-11eb-9599-b4cc34b38552.png">
<br />

</p>

[Ninite Pro](https://ninite.com/pro) is the commercially-licensed version of Ninite. It will update/deploy more apps and popular plugins than the free home-use version. Other functionalities include Ninite Pro's audit mode that shows you the apps on each machine and whether they are up-to-date.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/115158813-f09d6800-a044-11eb-9584-702f82734fcd.png">
  <br />
</p>

[Chocolatey](https://chocolatey.org/) is a software management solution unlike anything else you've ever experienced on Windows. It focuses on simplicity, security, and infinite scalability. The GUI is perhaps the best way to start for beginners. It can be installed by using `choco install chocolateygui` after having installed choco as described [here](https://chocolatey.org/install).

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/110880124-f7d99500-8292-11eb-9e7d-e9c335cbc173.png">
<br />

</p>

[Scoop](https://scoop.sh/) is an open source package manager for Windows 10. It gives Windows users an efficient way to download programs without having to visit each site manually, downloading the files, and running the installer.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/115158811-ef6c3b00-a044-11eb-9988-a705d35115ff.png">
  <br />
</p>

[Nix package manager](https://nixos.org/) is a cross-platform package manager that utilizes a purely functional deployment model where software is installed into unique directories generated through cryptographic hashes. Choose from Thousands of Packages The Nix Packages collection (Nixpkgs) is a set of over 80 000 packages for the Nix package manager.

**Single-user installation on Windows(WSL2):**

```$ sh <(curl -L https://nixos.org/nix/install) --no-daemon```


### Getting Software on Linux

[Discover](https://apps.kde.org/discover/) is an software center that let's you manage software from multiple sources, including your operating system's software repository, Flatpak repos, the Snap store, or even AppImages from store.kde.org. Also, Discover allows you to find, install, and manage add-ons for Plasma and all your favorite KDE apps.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/156265563-1e9776f6-048f-4c20-b93b-d06ddcafed6d.png">
<br />
 KDE Plasma Discover App Store
</p>

[Flathub](https://flathub.org/) is an app store and build service for hundreds of apps which can be easily installed on any Linux distribution. Browse the apps online, from your app center or the command line.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/156265570-56fe8837-3963-49c8-b3f9-24a219929625.png">
<br />
 Flathub App Store
</p>

**Note:** Flathub app search will be integrated in Discover, if you want to limit the app search to Flathub you can mark Flatpak as default by clicking on the star.

[Flatseal](https://github.com/tchx84/flatseal) is a graphical utility to review and modify permissions from your [Flatpak](https://flatpak.org/) applications. [Get it on Flathub store](https://flathub.org/apps/details/com.github.tchx84.Flatseal).
