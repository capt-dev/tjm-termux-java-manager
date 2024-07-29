# TJM Termux Java Manager
TJMTermux Java Manager is a tool designed to simplify the installation and management of Java versions within Termux. It provides an easy way to download, install, and switch between different Java versions on your Termux environment.
## Installation
To install TJM Termux Java Manager, follow the steps below:Update your package list and upgrade your installed packages:
```sh
pkg update && pkg upgrade
```
Install wget if it's not already installed:
```sh
pkg install wget
```
Download and run the installation script:
```sh
cd ~ && wget https://github.com/capt-dev/tjm-termux-java-manager/releases/download/v1.0.0/install.sh && bash ~/install.sh
```
# installation script for copying
```sh
cd ~ && pkg update && pkg upgrade && pkg install wget && wget https://github.com/capt-dev/tjm-termux-java-manager/releases/download/v1.0.0/install.sh && bash ~/install.sh
```
# Usage
After installation, you can use the TJM Termux Java Manager to manage your Java installations. The tool allows you to easily switch between different Java versions and ensures that your environment is correctly configured.
# Features
### Easy Installation:
Quickly set up Java environments with a single script.
### Version Management:
Seamlessly switch between multiple Java versions.
### Termux Integration:
Designed specifically for the Termux environment
