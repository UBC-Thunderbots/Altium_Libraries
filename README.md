# Altium_Libraries README

## Description

This repository contains Altium PCB files for UBC Thunderbots' Altium component library. Only the designated Component Librarian may push changes. If you wish to have a component added, or have noticed that there is an issue with an existing component, please contact the current librarian to have it added.

This library is integrated as a submodule in the designated PCB respositories.

## Getting Started

### Required software

1. git
2. Altium Designer

### Instructions

1. Either create a new working branch or select an existing branch other than `master`.
2. Clone your working branch of the repository to your PC (i.e. `C:/Documents/thunderbots/Altium_Libraries/`).
3. In Altium Designer, navigate to *Preferences -> Data Management -> Version Control* and ensure **SVN - Subversion** is enabled and **Version 1.9** is selected.
4. In Altium Designer, navigate to *Preferences -> Data Management -> Design Repositories*.
5. Within *Design Repositories* click on on *Connect To* -> **SVN**.
6. In the dialogue box that comes up, fill in the following information:

Field|Selection/Input
---|---
Name|Altium_Libraries
Default Checkout Path|location of local repository (i.e. `C:/Documents/thunderbots/Altium_Libraries/`)
Method|https
Server|github.com
Server Port|Default
Repository Subfolder|/UBC-Thunderbots/PCB_MotorDriver
User Name|*your github login username*
Password|*your github login password*

7. Click **Test**.

After your repository is connected, you can add or remove files like a regular Altium Project folder and then commit and push your changes to the remote repository.

[Reference](https://forum.live.altium.com/#posts/235981/718003)
