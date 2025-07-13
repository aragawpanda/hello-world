---
title: "Basic usage of Hugo"
date: 2025-07-05T23:52:32+09:00
draft: false
toc: false
images:
tags:
  - untagged
---

①Advance preparation

■1. Installing Hugo

Steps
Downloading Hugo
Go to the official Hugo release page (https://github.com/gohugoio/hugo/releases).
Select the latest stable version (e.g. hugo_extended_0.128.0_windows-amd64.zip) and download the .zip file for Windows.
*The "extended" version includes additional features, but the normal version is sufficient for basic use.
Unzipping and arranging
Right-click the downloaded .zip file and select "Extract All" to unzip it.
Move the hugo.exe file contained in the unzipped folder to a directory such as C:\Hugo\bin.
*If the directory does not exist, create C:\Hugo\bin in Explorer.
Setting environment variables
Add C:\Hugo\bin to the system PATH environment variable so that hugo.exe can be run directly from the command prompt.
How to set it:
Press the Windows key, search for "environment variables", and select "Edit system environment variables".
In the "Environment Variables" window, find "Path" under "System variables" and click "Edit".

Click "New", enter C:\Hugo\bin and click "OK".

Click "OK" to close all windows.

Confirm installation

Open a command prompt (Windows key + R → type cmd) and enter hugo version.

If version information (e.g. hugo v0.128.0) is displayed, the installation was successful.

Terminology explanation


■Download Git

Go to the official website Go to the official Git website.

Click "Download for Windows" and download the latest installer (e.g. Git-2.46.0-64-bit.exe).

■Install Git Run the installer
Double-click the downloaded .exe file to launch it.
Click "Next" to proceed.

Select installation options The following are recommended settings (default is often sufficient): Installation destination: Leave it as the default (e.g. C:\Program Files\Git).

Components: Use the default selection (Git Bash, Git GUI, etc.).
Editor: If you want to edit code with Hugo, you can select VS Code or Notepad++ (if you like).
PATH settings: Select "Git from the command line and also from 3rd-party software" (this will allow you to use git commands from the command prompt).
Line endings: On Windows, we recommend "Checkout Windows-style, commit Unix-style line endings".
Other settings are fine as default.

Installation complete Click "Install" to start the installation.

When it's complete, click "Finish".

■Git settings Initial settings for Git
If you are using it for the first time, please register your account.


（I will continue to update）