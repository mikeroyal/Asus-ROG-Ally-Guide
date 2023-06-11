# Operating Systems

[Back to Home](/README.md#table-of-contents)

## Table of Contents

- [Windows](#windows)
- [Linux](#linux)
  - [SteamOS](#steamos)
  - [Other Linux Distributions](#other-linux-distributions)
- [MacOS](#macos)

## Windows

[Back to the Top](#operating-systems)

**Note: Windows 11 comes presinstalled on the ASUS ROG Ally device.**
* If you upgrade your SSD you can easily reinstall Windows on your device by using **ASUS Cloud Recovery** in the **Advanced** section of the BIOS menu.
* **How to access BIOS** - Restart your ROG Ally by pressing the power button and hold the **Volume Down button**.

<p align="center">
 <img src="https://github.com/mikeroyal/Asus-ROG-Ally-Guide/assets/45159366/bab54540-9472-43bd-8e5d-7f5a543e7ed6">
  ROG Ally BIOS menu. Image Credit: ASUS
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124997795-20cf2400-e000-11eb-8954-4944286b8ea8.png">
  Windows 11 Desktop
</p>

## Linux

[Back to the Top](#operating-systems)

### Creating a Linux Bootable Device (MicroSD or USB)

[Rufus](https://rufus.ie/) is a utility that helps format and create bootable USB flash drives.

<p align="center">
 <img src="https://github.com/mikeroyal/Asus-ROG-Ally-Guide/assets/45159366/86c50e13-a851-42aa-b49c-2220894e5be8">
  <br />
  Rufus
</p>


[Etcher](https://www.balena.io/etcher/) is an open source, cross-platform software that makes it easy to flash operating system images to a microSD card or USB device.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/157350348-e43ea5a2-2346-4b0b-acc0-fc3352c3d820.png">
  <br />
  Etcher UI
</p>

 
## SteamOS

[ChimeraOS](https://chimeraos.org/) is a linux operating system that provides an out of the box couch gaming experience. It boots directly into Steam Big Picture and start playing your favorite games. **Note: If you're planning to put Linux on your ROG Ally I would recommend using ChimeraOS.**

<p align="center">
  <img src="https://github.com/mikeroyal/Steam-Deck-Guide/assets/45159366/b916cd2f-1b8e-43c7-8833-3c3b0d0715ef">
</p>

 ChimeraOS Desktop. Credit: [ChimeraOS](https://chimeraos.org/)

[Steam OS 3.0](https://store.steampowered.com/steamdeck) is an [immutable](https://en.wikipedia.org/wiki/Immutable_object) Operating System(OS) using the [KDE Plasma](https://kde.org/plasma-desktop) desktop. This allows you to install applications in containers using [Flatpak](https://flatpak.org/), rather than onto the root filesystem. This means not only that the installation of applications is isolated from the core filesystem, but also that the ability for malicious applications to compromise/break your system is significantly reduced. **Note: SteamOS 3.0 is not available for download yet.**

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/157353163-6f5c4c1a-a89f-4ee5-9ffe-1d9f991c773c.png">
  <br />
    SteamOS 3.0 with KDE Plasma Desktop
</p>

[SteamOS Btrfs](https://gitlab.com/popsulfr/steamos-btrfs/) is a project that will help get you from using ext4 on your device's microSD card or home directory, to [Btrfs](https://btrfs.wiki.kernel.org/).

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/172273657-f184233d-56d8-429b-9a63-d8a2b8e7412b.png">
</p>

[HoloISO](https://github.com/theVakhovskeIsTaken/holoiso) is a SteamOS 3 (Holo) archiso configuration. It aims to bring the Steam Deck's Holo OS into a generic, installable format, and provide a close-to-official SteamOS experience.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/167318762-c54fffa2-9ed4-4695-9d7d-4d03eb5ba49d.png">
    <br />
</p>

HoloISO Desktop. Credit: [theVakhovskeIsTaken](https://github.com/theVakhovskeIsTaken/)

## Other Linux Distributions

[Back to the Top](#operating-systems)

[Batocera](https://batocera.org/)

<p align="center">
  <img src="https://user-images.githubusercontent.com/4238928/163190916-d39124bb-c67e-42e4-a97c-dac78684c452.png">
    <br />
      Emulation Station Front End
</p>

[Nobara Project](https://gitlab.com/GloriousEggroll/nobara-images) is an unofficial Fedora Linux Spin that's tailored for Gaming. It adds the necessary packages/tools (such as [Lutris](https://lutris.net/) and [ProtonUp-Qt](https://davidotek.github.io/protonup-qt/)), and fixes issues to make Fedora awesome for gaming. This project is developed and maintained by [Thomas Crider AKA Glorious Eggroll](https://gitlab.com/GloriousEggroll).

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/179671757-008ac6ef-ee95-43e9-b6eb-2f9bb928f91b.png">
    <br />
</p>

[NixOS](https://nixos.org/) is a Linux distribution built on top of the [Nix package manager](https://nixos.wiki/wiki/Nix). It has tools dedicated to DevOps and deployment tasks.

 * [NixOS Guide](https://github.com/mikeroyal/NixOS-Guide)
 * [Nix on the Steam Deck - Determinate Systems](https://determinate.systems/posts/nix-on-the-steam-deck)
 
<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/128645111-b2a92dd2-f246-4df0-b05c-5b0ffce05448.png">
  <br />
  NixOS with the Plasma Desktop
</p>

[WinesapOS](https://github.com/LukeShortCloud/winesapOS) is a project developed by [LukeShortCloud](https://github.com/LukeShortCloud) that provides an easy to setup installation of Linux. It can be used on a flash drive, SD card, HDD, SSD, NVMe, or any other storage device. The [release images](https://github.com/LukeShortCloud/winesapOS/releases) are based on SteamOS 3 and the KDE Plasma desktop environment to align with what Valve's [Steam Deck](https://store.steampowered.com/steamdeck/) uses.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/163284898-ca65b1ac-8ebc-4adc-b5aa-bd6b5195295e.jpg">
    <br />
</p>

WineapOS Desktop. Credit: [LukeShortCloud](https://github.com/LukeShortCloud)

[EndeavourOS](https://endeavouros.com/)

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/107439882-9e414780-6ae7-11eb-819e-e87e7bcc7a97.png">
    <br />
      EndeavourOS Desktop
</p>

[Garuda Linux](https://garudalinux.org/)

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/127042105-f6a6d97e-77bd-402e-af4f-df7af588eb08.png">
    <br />
      Garuda Linux Desktop
</p>

[ArcoLinux](https://arcolinux.com/)

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/128940632-9e2a198f-f84d-490b-b4a2-22f6217ee574.png">
    <br />
      ArcoLinux Desktop
</p>

[Fedora Linux](https://getfedora.org/)

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/205604774-0a91b502-0381-431a-acc4-823c1b477615.png">
    <br />
      Fedora Desktop
</p>

[Pop!_OS](https://pop.system76.com) created by [System76](https://system76.com).

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/142779593-390dfd58-a246-4299-baf2-adf0207da696.png">
    <br />
      Pop!_OS Desktop
</p>


## MacOS

[Docker OSX](https://github.com/sickcodes/Docker-OSX) is a tool that lets you run macOS VM in a Docker container atnear native OSX-KVM in Docker with X11 Forwarding. This project is developed and mantained by [sickcodes](https://github.com/sickcodes).

 * [Docker-OSX on Docker Hub](https://hub.docker.com/r/sickcodes/docker-osx)

**MacOS Ventura**

```
docker run -it \
    --device /dev/kvm \
    -p 50922:10022 \
    -v /tmp/.X11-unix:/tmp/.X11-unix \
    -e "DISPLAY=${DISPLAY:-:0.0}" \
    -e GENERATE_UNIQUE=true \
    -e MASTER_PLIST_URL='https://raw.githubusercontent.com/sickcodes/osx-serial-generator/master/config-custom.plist' \
    sickcodes/docker-osx:ventura

# docker build -t docker-osx --build-arg SHORTNAME=ventura .
```

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/205603964-f8c6c954-6215-4573-a028-bd8f1d1e5c8d.png">
  </br>
  MacOS Ventura
</p>
