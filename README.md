# ShellDeck releases

ShellDeck is a terminal and connection manager for network engineers, for Windows 10 (2004 or later) and Windows 11
x64. Its layout and terms follow Devolutions RDM and VanDyke SecureCRT.

This repository holds only the installers. Download them from
[Releases](https://github.com/arthur-trovon/ShellDeck-releases/releases).

## Install

- **ShellDeck-Setup-x.y.z.exe**: installs for your user only, so it needs no administrator rights. The default folder
  is `%LOCALAPPDATA%\Programs\ShellDeck`. The .NET runtime is included.
- **ShellDeck-x.y.z-win-x64-portable.zip**: the same files without an installer. Extract the zip anywhere and run
  `ShellDeck.exe`.

Your vault, settings and logs are kept in the `Data` and `Logs` folders next to `ShellDeck.exe`. Installing a newer
version over an older one keeps them, and uninstalling never deletes them.

The files are not code-signed yet, so Windows SmartScreen may warn you the first time. Choose **More info › Run
anyway**. Each release lists its files' SHA-256 checksums in `SHA256SUMS.txt`.
