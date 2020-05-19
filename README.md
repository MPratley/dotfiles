# dotfiles
Dotfiles, for a little bit of system mobility

## How to use

You need to install GNU Stow.

On executing:
```
stow folder_name
```
The contents of folder_name are intelligently symlinked in the home directory by stow. Very useful!

## What works where

- Systemd configs will only work on linux distros that use systemd (suprise!)
- Binaries or packages should be installed in whatever manner seems reasonable for the system in use. The following is my current setup:
    - Rust packages (eg librespot) are installed by `cargo`, in turn by `rustup`
    - Python & pip are installed by `brew`
    - apt/dnf etc are package-managers of last resort.
 
