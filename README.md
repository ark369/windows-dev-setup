# windows-dev-setup
Instructions and tools for setting up a windows10 PC for programming in a linux-like environment

## Raw notes
1. Used wsl 2 to download and set up an Ubuntu distribution.
    * Note that PowerShell 7 could not find "Wsl" executable on its path (?), so had to use Command Prompt instead.
2. Installed Docker Desktop, which integrates with wsl.
    * Needed to update the Ubuntu distribution in wsl to be a version 2 distribution, otherwise Docker Desktop could not use it.
3. Installed vscode, and then installed the "Remote - WSL" extension.

## Alternatives
* Tried using PowerShell 7 along with chocolatey (package manager for windows), but gave up quickly.
