---
layout: post
title: "Installing the Prep Course Virtual Machine"
author: "Léon Kuchenbecker"
categories: help
tags: [help]
---

This is a description how to install the *Vorkurs Linux Virtual Machine* on your Windows Desktop. These steps are **only required for Windows users**, if you attend the **Vorkurs** with a Mac or Linux Laptop, you do not need to follow these instructions!

## Download and Install Oracle VirtualBox for Windows

Download and install the latest version (6.1.x) of Oracle VirtualBox for Windows hosts from [here](https://www.virtualbox.org/wiki/Downloads). After the download has completed, run the installer and aggree to all driver installation requests. Reboot your system if requested.

## Download and Import the Linux Vorkurs Virtual Machine

Download the OVA file of the Virtual Machine from [here]({{ "https://compbio.de/vorkurs/assets/Linux%20Vorkurs.ova" | absolute_url }}) and store it on your harddrive. After the download has completed, double click the OVA file. An import window should appear:

![Import Dialog]({{ "/assets/img/import.png" | absolute_url }}){:style="max-width:600px"}

Confirm by pressing the **Import** button.

## Start up the Virtual Machine

After the import has completed, you should see the following window after starting Virtual Box:

![Main Window]({{ "/assets/img/main_window.png" | absolute_url }}){:style="max-width:600px"}

Double click **Linux Vorkurs** and your virtual machine should start up. After
it has successfully booted, you should see a window that looks like this:

![VM Window]({{ "/assets/img/running_vm.png" | absolute_url }}){:style="max-width:600px"}

**You are now all set for the Linux Vorkurs! :)**

## Potential Error

If you see the following error message or similar when starting up the virtual machine

![VM Window]({{ "/assets/img/error.png" | absolute_url }}){:style="max-width:600px"}

your computer does not have hardware accelerated virtualization enabled. On most computers, this requires changing a BIOS setting which enables the required feature. If you see this message and cannot fix it yourself, we will try to properly configure the computer when you attend the *Vorkurs*.
