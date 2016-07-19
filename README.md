# Fedora 24 Configuration Guide for DevOps 

## Recommended Installs

### Update Fedora Packages

First thing to do after a fresh install is to update packages. This may take a couple of minutes:

	dnf update

## Optional Installs

These are not required but may be selected based on user preference.

### Install Gnome Tweak Tool

Fedora 24 uses the gnome-shell desktop environment. To change some of gnome-shell's settings, you can install the Gnome Tweak Tool: 	

	dnf install gnome-tweak-tool

### 

### Activate RPMFusion Repository

The RPMFusion provides some free and non-free software for Fedora. The repo can be used via the command line. The repository is meant to provide stable and tested packages for Fedora so it is highly recommended to activate it on your system with:

	rpm -ivh http://download1.rpmfusion.org/free/fedora/rpmfusion-free-release-stable.noarch.rpm

###

