A set of scripts for integrating Neovim Qt executable with Windows Explorer — registering a program ID, creating file associations and adding the `Edit with Neovim` file & folder context menu option.

IMPORTANT: Set the `nvim-qt.exe` location path in `\*\*.reg` files and the `\set-file-associations\associations-list.conf` contents according to YOUR setup and requirements before applying them.

## Actions

- `\set-progid-nvim-qt\*.reg` adds/removes the `Applications\nvim-qt.exe` program ID in Windows Registry.
- `\set-context-menu-edit-with-neovim\*.reg` adds/removes `Edit with Neovim` right click file and directory context menu item which corresponds to `Applications\nvim-qt.exe` program ID.
- `\set-file-assocations\set-associations.bat + associations-list.conf` associates the `Applications/nvim-qt.exe` program ID with a long list of plaintext file format extensions.

## Requirements

`\set-file-associations\set-associations.bat` script requires the `setUserFTA` utility: https://kolbi.cz/blog/2017/10/25/setuserfta-userchoice-hash-defeated-set-file-type-associations-per-user/
