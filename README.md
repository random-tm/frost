# frost
A wrapper for the yaourt package manager on Arch Linux

The goal of this project is to reduce the number of commands and commandline switches a user needs in order to update an Arch Linux machine

Commands:

-upgrade: Upgrades the machine using the AUR repository and offical repos

-clean: Removed unneeded and orphaned packages

-install: Install a package; syntax: frost -install package_name

-remove: Remove a package along, this will also remove dependencies and config files; syntax: frost -remove package_name

-mirror-change: Open the new mirror file and replace the old mirror file with it