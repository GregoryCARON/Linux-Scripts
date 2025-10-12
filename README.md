# Linux-Scripts

## cache_pacman_aur

cache_pacman_aur clears the package and build caches for ArchLinux

## clefs-ssh

clefs-ssh allows to list, create, and delete SSH keys that allow you to connect to a remote server without a password.

This script goes further by allowing you to manage your connections and send the key directly to the desired connection.

## passphp

passphp create a password that can be used in PHP, for example for htpasswd

## venup

venup is a script that makes it easy to update Discord and Vencord on ArchLinux. Sometimes, an update for Discord is available, but it's not yet in the AUR repositories. Simply download the tar.gz file provided by Discord, pass the archive name (e.g., discord-canary-0.0.755.tar.gz), and that's it! The script will take care of updating Discord by fetching the file from the download folder and applying Vencord. Remember to quit Discord before running the script.

### usage

`venup discord-canary-0.0.755.tar.gz`

## repair-install

If your ArchLinux becomes unstable, a repair installation may be necessary. This script reinstalls only the official packages installed on your system. No configuration will be altered; only the binaries will be reinstalled.
