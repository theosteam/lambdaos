# LambdaOS Documentation

Welcome to the LambdaOS documentation! This guide covers everything you need to know to get started with LambdaOS, from installation to advanced usage.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Installation Guide](#installation-guide)
3. [Getting Started](#getting-started)
4. [System Requirements](#system-requirements)
5. [Customizing LambdaOS](#customizing-lambdaos)
6. [Troubleshooting](#troubleshooting)
7. [AAQs](#aaqs)
8. [Contributing](#contributing)
9. [Contact](#contact)

---

## Introduction

LambdaOS is a Kubuntu-based Linux distribution that emphasizes aesthetics and performance. Whether you're new to Linux or a seasoned user, LambdaOS provides a sleek and efficient environment tailored to your needs.
<sub>Believe me, it's possible to have both.</sub>
<sub>-SDCast</sub>

## Installation Guide

### System Requirements

Before installing LambdaOS, make sure your system meets the following minimum requirements:

- **Processor**: 64-bit dual-core processor
- **Memory**: 4 GB RAM
- **Storage**: 20 GB of free disk space
- **Graphics**: Integrated or dedicated GPU with OpenGL support
- **Internet Connection**: Required for updates and additional software

### Installation Steps

1. **Download the ISO**: Get the latest version of LambdaOS from the [releases page](https://drive.google.com/file/d/1vrZ7_jmjTdc_1lPE_mvkyO74ilKF2D6V/view?usp=sharing).
2. **Create a Bootable USB**: Use a tool like `Rufus` or `balenaEtcher` to create a bootable USB drive.
3. **Boot from USB**: Insert the USB into your computer and restart. Select the USB as the boot device in your BIOS/UEFI settings.
4. **Install LambdaOS**: Follow the on-screen instructions to install LambdaOS on your system.

## Getting Started

Once LambdaOS is installed, here are a few things to help you get started:

- **First Login**: Log in using the username and password you set during installation.
- **Update the System**: Open the terminal and run the following command to update your system:
  ```
  sudo apt update && sudo apt upgrade -y
  ```
- **Explore the Desktop**: LambdaOS uses the KDE Plasma desktop environment. Familiarize yourself with the menu, taskbar, and system settings.

## Customizing LambdaOS

LambdaOS is highly customizable, given the Plasma environment. Here are a few ways to make it your own:

- **Change the Wallpaper**: Right-click on the desktop and select "Configure Desktop" to change the wallpaper.
- **Install New Themes**: Use the "System Settings" to install and apply new themes.
- **Add Widgets**: Customize your desktop by adding widgets from the Plasma Widget store.

## Troubleshooting

Encountering issues? Here are some common problems and solutions:

- **Black Screen After Boot**: Try booting into recovery mode and updating your graphics drivers.
- **Wi-Fi Not Working**: Ensure your Wi-Fi drivers are installed. You can check with:
  ```
  sudo lshw -C network
  ```
- **Slow Performance**: Disable unnecessary startup applications using the "System Settings." (You shouldn't have a startup application anyways)

## AAQs (Already Answered Questions)

### Q1: How do I install software on LambdaOS?

You can install software using the terminal with `apt` or through the Discover software center.

### Q2: How do I update LambdaOS?

Run the following command in the terminal:
```
sudo apt update && sudo apt upgrade -y
```

### Q3: Can I dual-boot LambdaOS with another OS?

Yes, LambdaOS supports dual-booting. Follow the installation guide and select "Install alongside other OS" during setup.

## Contributing

We welcome contributions to LambdaOS! If you're interested in helping out, here are a few ways to contribute:

- **Report Bugs**: Found a bug? [Submit an issue](https://github.com/theosteam/lambdaos/issues).
- **Submit Features**: Have a great idea? Let us know!
- **Code Contributions**: Fork the repo, make changes, and submit a pull request. See our [contributing guide](contributing.md) for more details.

## Contact

If you have any questions, feedback, or need support, feel free to reach out:

- **Email**: [opensystemteam1@gmail.com](mailto:opensystemteam1@gmail.com)
- **Discord**: [Join our community](https://discord.com/invite/T2wwXw4yrp)
