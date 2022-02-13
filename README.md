# Arch Linux Repository

A set of meta-packages and tooling for managing Arch Linux installs via a custom
repository.

This is a fork of [Michael Daffin](https://gitlab.com/mdaffin/arch-pkgs) work.

For more details see these blog posts:

- [Managing Arch Linux with Meta Packages]
- [Creating a Custom Arch Linux Installer]

[managing arch linux with meta packages]: https://disconnected.systems/blog/archlinux-meta-packages
[creating a custom arch linux installer]: https://disconnected.systems/blog/archlinux-installer

## Contributing

I welcome fixes for bugs or better ways of doing something. But these packages
and installers are for my personal use and as such I will not approve pull
requests for features I do not need. Feel free to raise issues if you want help
with your own packages, have an interesting idea, want some clarification or
want to discuss something generally.

## Install

**WARNING** This will wipe a drive and install Arch Linux on it. **DO NOT** run
unless you have read through it first.

```bash
curl -sL https://bit.ly/3sWTxt8 | bash
```

## Build

Builds packages and creates the database for the repository.

```bash
./build
```
