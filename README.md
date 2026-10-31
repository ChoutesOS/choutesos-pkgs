<p align="center">
  <img src="https://raw.githubusercontent.com/ChoutesOS/.github/main/assets/banner.png" alt="ChoutesOS" width="100%">
</p>

<p align="center">
  <a href="https://choutes.com">Website</a> &middot;
  <a href="https://github.com/ChoutesOS/choutesos/discussions">Discussions</a> &middot;
  <a href="https://github.com/ChoutesOS/choutesos/issues/new/choose">Report an issue</a> &middot;
  <a href="https://github.com/ChoutesOS/.github/blob/main/CONTRIBUTING.md">Contributing</a>
</p>
<p align="center">
  <img alt="License: GPL-3.0-or-later" src="https://img.shields.io/badge/license-GPL--3.0--or--later-5B18E5">
  <img alt="Based on Arch Linux" src="https://img.shields.io/badge/based%20on-Arch%20Linux-9660F8">
  <img alt="Desktop: KDE Plasma" src="https://img.shields.io/badge/desktop-KDE%20Plasma-26223C">
</p>

# choutes-pkgs

Package sources and tooling for the signed ChoutesOS pacman repository.

## Status

This repository is at its initial setup stage. The package repository is under development and is not yet in use, so it should not be added to `pacman.conf` for now.

## Scope

- Package sources (`PKGBUILD` files) for ChoutesOS-specific packages
- Scripts to build, sign, and publish packages and to update the repository database
- Automation for continuous integration

Repository packages are signed with GPG. Private signing keys are never stored in this repository.

## Related repositories

- [choutesos](https://github.com/ChoutesOS/choutesos): official hub for bug reports, feature requests, and discussions
- [choutesos-iso](https://github.com/ChoutesOS/choutesos-iso): ISO build profile
- [choutesos-calamares-config](https://github.com/ChoutesOS/choutesos-calamares-config): installer configuration
- [choutes-pkgs](https://github.com/ChoutesOS/choutes-pkgs): package sources and pacman repository tooling

## Getting help and contributing

Report problems and ask questions in the [official hub](https://github.com/ChoutesOS/choutesos). To contribute, read the [contributing guide](https://github.com/ChoutesOS/.github/blob/main/CONTRIBUTING.md) and the [code of conduct](https://github.com/ChoutesOS/.github/blob/main/CODE_OF_CONDUCT.md).

## Independence

ChoutesOS is an independent project and is not affiliated with Arch Linux.

## License

Source code and documentation in this repository are licensed under the GNU General Public License, version 3 or (at your option) any later version. See [LICENSE](LICENSE).

The ChoutesOS name, logo and wallpapers are not covered by that license.
